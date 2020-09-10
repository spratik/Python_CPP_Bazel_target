load("@rules_cc//cc:defs.bzl", "cc_library")


cc_library(
    name = "python",
    hdrs = glob(["include/*.h", "include/cpython/*.h", "include/internal/*.h"]),
	srcs = glob(["libs/*.lib"]),
    visibility = ["//visibility:public"],
)