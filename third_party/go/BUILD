subinclude("///go//build_defs:go")

package(default_visibility = ["PUBLIC"])

go_toolchain(
    name = "toolchain",
    hashes = [
        "27014fc69e301d7588a169ca239b3cc609f0aa1abf38528bf0d20d3b259211eb",  # darwin-amd64
        "65302a7a9f7a4834932b3a7a14cb8be51beddda757b567a2f9e0cbd0d7b5a6ab",  # darwin-arm64
        "6e74f65f586e93d1f3947894766f69e9b2ebda488592a09df61f36f06bfe58a8",  # freebsd-amd64
        "1241381b2843fae5a9707eec1f8fb2ef94d827990582c7c7c32f5bdfbfd420c8",  # linux-amd64
        "fc90fa48ae97ba6368eecb914343590bbb61b388089510d0c56c2dde52987ef3",  # linux-arm64
    ],
    install_std = True,
    version = "1.21.3",
)

go_stdlib(
    name = "std",
)

go_mod_download(
    name = "build_tools_dl",
    module = "github.com/please-build/buildtools",
    version = "24cce64e067d6147dcfff2a7059fa00c28537597",
)

go_repo(
    download = ":build_tools_dl",
    module = "github.com/bazelbuild/buildtools",
)

go_repo(
    module = "gopkg.in/op/go-logging.v1",
    version = "v1.0.0-20160211212156-b2cb9fa56473",
)

go_repo(
    module = "golang.org/x/text",
    version = "v0.3.7",
)

go_repo(
    module = "golang.org/x/tools",
    version = "v0.1.5",
)

go_repo(
    module = "github.com/yuin/goldmark",
    version = "v1.2.1",
)

go_repo(
    module = "github.com/x1ddos/csslex",
    version = "v0.0.0-20160125172232-7894d8ab8bfe",
)

go_repo(
    module = "github.com/matttproud/golang_protobuf_extensions",
    requirements = ["github.com/golang/protobuf"],
    version = "v1.0.1",
)

go_repo(
    module = "github.com/shirou/gopsutil/v3",
    version = "v3.22.6",
)

go_repo(
    module = "github.com/chzyer/readline",
    version = "v0.0.0-20180603132655-2972be24d48e",
)

go_repo(
    module = "github.com/coreos/go-semver",
    version = "v0.3.0",
)

go_repo(
    module = "github.com/Masterminds/semver/v3",
    version = "v3.1.1",
)

go_repo(
    module = "github.com/stretchr/testify",
    version = "v1.8.4",
)

go_repo(
    module = "github.com/peterebden/go-cli-init/v5",
    version = "v5.2.0",
)

go_repo(
    module = "gopkg.in/yaml.v3",
    version = "v3.0.0-20210107192922-496545a6307b",
)

go_repo(
    module = "github.com/klauspost/compress",
    version = "v1.13.6",
)

go_repo(
    module = "github.com/jellydator/ttlcache/v2",
    version = "v2.11.1",
)

go_repo(
    module = "github.com/please-build/gcfg",
    version = "9b4d14cddd6148920e11c8bb7ee19369473b1019",
)

go_repo(
    module = "github.com/ProtonMail/go-crypto",
    version = "3900d675f39ba9686203d137886d74fad620ae87",
)

go_repo(
    module = "golang.org/x/net",
    version = "v0.17.0",
)

go_repo(
    module = "github.com/prometheus/client_model",
    version = "v0.2.0",
)

go_repo(
    module = "github.com/peterebden/go-sri",
    version = "v1.1.1",
)

go_repo(
    module = "github.com/zeebo/blake3",
    version = "v0.2.3",
)

go_repo(
    module = "github.com/thought-machine/go-flags",
    version = "v1.6.2",
)

go_repo(
    module = "github.com/theupdateframework/go-tuf",
    version = "v0.5.1",
)

go_repo(
    module = "golang.org/x/oauth2",
    version = "v0.4.0",
)

go_repo(
    module = "github.com/google/shlex",
    version = "v0.0.0-20181106134648-c34317bd91bf",
)

go_repo(
    module = "github.com/mostynb/zstdpool-syncpool",
    version = "v0.0.7",
)

go_repo(
    module = "github.com/peterebden/buildtools",
    version = "f7a36c689cc9e038956d51005332c67ade7aa9c6",
)

go_repo(
    module = "google.golang.org/genproto",
    version = "v0.0.0-20221206210731-b1a01be3a5f6",
)

go_repo(
    module = "github.com/djherbis/atime",
    version = "v1.1.0",
)

go_repo(
    module = "github.com/hashicorp/go-retryablehttp",
    version = "v0.7.0",
)

go_repo(
    module = "github.com/texttheater/golang-levenshtein",
    version = "v1.0.1",
)

go_repo(
    module = "github.com/golang/snappy",
    version = "v0.0.3",
)

go_repo(
    module = "github.com/tklauser/go-sysconf",
    version = "v0.3.9",
)

go_repo(
    module = "github.com/ulikunitz/xz",
    version = "v0.5.10",
)

go_repo(
    module = "github.com/mattn/go-isatty",
    version = "v0.0.14",
)

go_repo(
    module = "github.com/google/go-containerregistry",
    version = "v0.12.0",
)

go_repo(
    module = "github.com/tklauser/numcpus",
    version = "v0.3.0",
)

go_repo(
    module = "github.com/prometheus/client_golang",
    version = "v1.11.0",
)

go_repo(
    module = "github.com/lunixbochs/vtclean",
    version = "v1.0.0",
)

go_repo(
    module = "golang.org/x/term",
    version = "v0.0.0-20210615171337-6886f2dfbf5b",
)

go_repo(
    module = "github.com/google/go-cmp",
    version = "b1c9c4891a6525d98001fea424c8926c6d77bb56",
)

go_repo(
    module = "github.com/hashicorp/go-multierror",
    version = "v1.1.1",
)

go_repo(
    module = "github.com/grpc-ecosystem/go-grpc-middleware",
    version = "v1.3.0",
)

go_repo(
    module = "github.com/pborman/uuid",
    version = "v1.2.0",
)

go_repo(
    module = "github.com/sigstore/sigstore",
    version = "v1.5.0",
)

go_repo(
    module = "gopkg.in/warnings.v0",
    version = "v0.1.2",
)

go_repo(
    module = "github.com/pkg/errors",
    version = "v0.9.1",
)

go_repo(
    module = "github.com/googleapis/gax-go/v2",
    version = "v2.7.0",
)

go_repo(
    module = "github.com/golang/groupcache",
    version = "v0.0.0-20200121045136-8c9f03a8e57e",
)

go_repo(
    module = "google.golang.org/grpc/cmd/protoc-gen-go-grpc",
    version = "v1.1.0",
)

go_repo(
    module = "github.com/golang/protobuf",
    version = "v1.5.2",
)

go_repo(
    module = "golang.org/x/sync",
    version = "v0.1.0",
)

go_repo(
    module = "github.com/dustin/go-humanize",
    version = "v1.0.0",
)

go_repo(
    module = "golang.org/x/mod",
    version = "v0.5.0",
)

go_repo(
    module = "github.com/googleapis/enterprise-certificate-proxy",
    version = "v0.2.0",
)

go_repo(
    module = "github.com/peterebden/ar",
    version = "v0.0.0-20181115090543-a0ae3a11a518",
)

go_repo(
    module = "cloud.google.com/go",
    version = "v0.65.0",
)

go_repo(
    module = "cloud.google.com/go/compute/metadata",
    version = "v0.2.3",
)

go_repo(
    module = "github.com/mattn/go-colorable",
    version = "v0.1.8",
)

go_repo(
    module = "github.com/peterebden/go-deferred-regex",
    version = "v1.0.0",
)

go_repo(
    module = "github.com/hashicorp/errwrap",
    version = "v1.1.0",
)

go_repo(
    module = "github.com/karrick/godirwalk",
    version = "v1.16.1",
)

go_repo(
    module = "github.com/beorn7/perks",
    version = "v1.0.1",
)

go_repo(
    module = "github.com/juju/ansiterm",
    requirements = [
        "github.com/lunixbochs/vtclean",
        "github.com/mattn/go-colorable",
        "github.com/mattn/go-isatty",
    ],
    version = "720a0952cc2ac777afc295d9861263e2a4cf96a1",
)

go_repo(
    module = "github.com/davecgh/go-spew",
    version = "v1.1.1",
)

go_repo(
    module = "golang.org/x/sys",
    version = "v0.0.0-20220315194320-039c03cc5b86",
)

go_repo(
    module = "github.com/shurcooL/sanitized_anchor_name",
    version = "v1.0.0",
)

go_repo(
    module = "github.com/peterebden/tools",
    version = "v0.0.0-20190805132753-b2a0db951d2a",
)

go_repo(
    module = "github.com/opencontainers/go-digest",
    version = "v1.0.0",
)

go_repo(
    module = "google.golang.org/grpc",
    version = "v1.51.0",
)

go_repo(
    module = "github.com/sourcegraph/jsonrpc2",
    version = "v0.1.0",
)

go_repo(
    module = "golang.org/x/xerrors",
    version = "5ec99f83aff198f5fbd629d6c8d8eb38a04218ca",
)

go_repo(
    module = "github.com/cespare/xxhash/v2",
    version = "v2.1.2",
)

go_repo(
    module = "github.com/googlecodelabs/tools/claat",
    version = "v0.0.0-20210914205149-d1177395e3b8",
)

go_repo(
    module = "github.com/klauspost/cpuid/v2",
    version = "v2.2.1",
)

go_repo(
    module = "github.com/gogo/protobuf",
    version = "v1.3.2",
)

go_repo(
    module = "github.com/stretchr/objx",
    version = "v0.3.0",
)

go_repo(
    module = "github.com/bazelbuild/remote-apis-sdks",
    version = "v0.0.0-20221114180157-e62cf9b8696a",
)

go_repo(
    module = "github.com/alessio/shellescape",
    version = "v1.4.1",
)

go_repo(
    module = "golang.org/x/crypto",
    version = "v0.5.0",
)

go_repo(
    module = "google.golang.org/protobuf",
    version = "v1.25.0",
)

go_repo(
    module = "github.com/golang/glog",
    patch = ["glog_disable.patch"],
    version = "v0.0.0-20160126235308-23def4e6c14b",
)

go_repo(
    module = "github.com/sourcegraph/go-lsp",
    version = "v0.0.0-20200429204803-219e11d77f5d",
)

go_repo(
    module = "github.com/pkg/xattr",
    version = "v0.4.3",
)

go_repo(
    module = "cloud.google.com/go/iam",
    version = "v0.8.0",
)

go_repo(
    module = "go.uber.org/automaxprocs",
    version = "v1.4.0",
)

go_repo(
    module = "github.com/pmezard/go-difflib",
    version = "v1.0.0",
)

go_repo(
    module = "gopkg.in/square/go-jose.v2",
    requirements = ["golang.org/x/crypto"],
    version = "v2.6.0",
)

go_repo(
    module = "github.com/prometheus/common",
    version = "v0.30.0",
)

go_repo(
    module = "github.com/titanous/rocacheck",
    version = "afe73141d399b0c79c3d6412d4bdcf4c672c496a",
)

go_repo(
    module = "google.golang.org/api",
    version = "v0.106.0",
)

go_repo(
    module = "github.com/hashicorp/go-cleanhttp",
    version = "v0.5.2",
)

go_repo(
    module = "go.opencensus.io",
    version = "v0.24.0",
)

go_repo(
    module = "cloud.google.com/go/longrunning",
    version = "v0.4.0",
)

go_repo(
    module = "github.com/prometheus/procfs",
    version = "v0.6.0",
)

go_repo(
    module = "github.com/manifoldco/promptui",
    version = "v0.7.0",
)

go_repo(
    module = "sourcegraph.com/sqs/pbtypes",
    version = "v0.0.0-20180604144634-d3ebe8f20ae4",
)

go_repo(
    module = "github.com/google/uuid",
    version = "v1.1.2",
)

go_repo(
    module = "github.com/letsencrypt/boulder",
    version = "cfa524a7a139bd4cf21c4c09ab47b994a96fd11f",
)

go_repo(
    module = "github.com/fsnotify/fsnotify",
    version = "v1.5.1",
)

go_repo(
    module = "github.com/bazelbuild/remote-apis",
    version = "3e816456ee28f01ab2e0abf72306c1f340c7b229",
)

go_repo(
    module = "go.starlark.net",
    version = "v0.0.0-20210901212718-87f333178d59",
)

go_repo(
    module = "cloud.google.com/go/kms",
    version = "v1.8.0",
)

go_repo(
    module = "github.com/sourcegraph/go-diff",
    version = "v0.6.1",
)

go_repo(
    module = "golang.org/x/exp",
    version = "1de6713980dea447778ef6e71194d5eb54288072",
)

go_repo(
    module = "github.com/jstemmer/go-junit-report/v2",
    version = "v2.0.0",
)
