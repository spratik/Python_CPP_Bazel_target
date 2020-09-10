load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")

cc_binary(
    name = "python_cpp",
    srcs = ["python_cpp.cc"],
	copts = ["-IthirdParty/tensorflow/include", "-LthirdParty/tensorflow/lib"],
    deps = [
        "//thirdParty/tensorflow:python",
    ]
)
