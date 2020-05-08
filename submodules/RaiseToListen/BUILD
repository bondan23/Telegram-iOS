load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "RaiseToListen",
    module_name = "RaiseToListen",
    srcs = glob([
        "Sources/**/*.swift",
    ]),
    deps = [
        "//submodules/RaiseToListen/Impl:RaiseToListenImpl",
    ],
    visibility = [
        "//visibility:public",
    ],
    copts = [
        '-I/Users/bondanprasetyo/Documents/SwiftPlayground/Telegram-iOS/submodules/RaiseToListen/Impl/PublicHeaders'
    ]
)
