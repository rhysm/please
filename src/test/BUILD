subinclude("//test/build_defs")

go_library(
    name = "test",
    srcs = [
        "coverage.go",
        "gcov_coverage.go",
        "go_coverage.go",
        "go_results.go",
        "istanbul_coverage.go",
        "results.go",
        "surefire.go",
        "test_step.go",
        "xml_coverage.go",
        "xml_results.go",
    ],
    pgo_file = "//:pgo",
    visibility = ["PUBLIC"],
    deps = [
        "///third_party/go/github.com_jstemmer_go-junit-report_v2//gtr",
        "///third_party/go/github.com_jstemmer_go-junit-report_v2//parser/gotest",
        "///third_party/go/github.com_peterebden_tools//cover",
        "//src/build",
        "//src/cli",
        "//src/cli/logging",
        "//src/core",
        "//src/fs",
        "//src/process",
    ],
)

go_test(
    name = "test_test",
    srcs = [
        "coverage_test.go",
        "results_test.go",
        "xml_results_test.go",
    ],
    data = ["test_data"],
    deps = [
        ":test",
        "///third_party/go/github.com_peterebden_tools//cover",
        "///third_party/go/github.com_stretchr_testify//assert",
        "///third_party/go/github.com_stretchr_testify//require",
        "//src/core",
    ],
)

go_test(
    name = "go_test_panic",
    srcs = ["go_test_panic.go"],
    labels = ["manual"],
    deps = [
        "///third_party/go/github.com_stretchr_testify//assert",
    ],
)

# This test runs the test above (go_test_panic), which panics, and checks that
# we capture the panic output.
plz_e2e_test(
    name = "go_test_output_test",
    cmd = "plz test //src/test:go_test_panic",
    expect_output_contains = "panic: goodbye world",
    expected_failure = True,
)
