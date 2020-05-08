objc_library(
    name = "TonBinding",
    module_name = "TonBinding",
    enable_modules = True,
    srcs = glob([
        "Sources/**/*.m",
        "Sources/**/*.mm",
    ]),
    hdrs = glob([
        "Sources/**/*.h",
    ]),
    copts = [
        "-std=c++14",
        "-I/Users/bondanprasetyo/Documents/SwiftPlayground/Telegram-iOS/submodules/SSignalKit/SSignalKit/Source"
    ],
    includes = [
        "Sources",
    ],
    deps = [
        "//submodules/SSignalKit/SSignalKit:SSignalKit",
        "//submodules/openssl:openssl",
        "//submodules/ton:ton",
    ],
    visibility = [
        "//visibility:public",
    ]
)
