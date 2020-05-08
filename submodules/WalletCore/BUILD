load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "WalletCore",
    module_name = "WalletCore",
    srcs = glob([
        "Sources/**/*.swift",
    ]),
    deps = [
	    "//submodules/SSignalKit/SwiftSignalKit:SwiftSignalKit",
        "//submodules/TonBinding:TonBinding",
    ],
    visibility = [
        "//visibility:public",
    ],
    copts = [
        "-I/Users/bondanprasetyo/Documents/SwiftPlayground/Telegram-iOS/submodules/TonBinding",
        "-I/Users/bondanprasetyo/Documents/SwiftPlayground/Telegram-iOS/submodules/SSignalKit/SSignalKit/Source"
    ]
)
