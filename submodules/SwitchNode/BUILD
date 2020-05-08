load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "SwitchNode",
    module_name = "SwitchNode",
    srcs = glob([
        "Sources/**/*.swift",
    ]),
    deps = [
    	"//submodules/AsyncDisplayKit:AsyncDisplayKit",
	    "//submodules/Display:Display",
        "//submodules/LegacyComponents:LegacyComponents",
    ],
    visibility = [
        "//visibility:public",
    ],
    copts = [
        "-I/Users/bondanprasetyo/Documents/SwiftPlayground/Telegram-iOS/bazel-Telegram-iOS/submodules/LegacyComponents/PublicHeaders",
        "-I/Users/bondanprasetyo/Documents/SwiftPlayground/Telegram-iOS/bazel-Telegram-iOS/submodules/AsyncDisplayKit/Source/PublicHeaders",
        "-I/Users/bondanprasetyo/Documents/SwiftPlayground/Telegram-iOS/submodules/SSignalKit/SSignalKit/Source"
    ]
)
