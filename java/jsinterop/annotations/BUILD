# Description:
#   Jsinterop Annotations for J2CL/GWT
#

load("@com_google_j2cl//build_defs:rules.bzl", "j2cl_import")

package(
    default_visibility = ["//:__pkg__"],
)

licenses(["notice"])  # Apache2

java_library(
    name = "annotations",
    srcs = glob(["*.java"]),
)

j2cl_import(
    name = "annotations-j2cl",
    jar = ":annotations",
)
