package(default_visibility = ["//visibility:public"])

# cc_library(
#     name = "imgui",
#     hdrs = glob(["**/*.h",]),
#     srcs = glob(["**/*.cpp",]),
#     # includes = ["**/*"],
#     copts = ["-Wno-deprecated-enum-enum-conversion"],
# )

cc_library(
    name = "imgui",
    hdrs = [
        "imconfig.h",
        "imgui.h",
        "imgui_internal.h",
        "imstb_rectpack.h",
        "imstb_textedit.h",
        "imstb_truetype.h",
        "backends/imgui_impl_opengl3.h",
        "backends/imgui_impl_opengl3_loader.h",

    ],

    srcs = [
        "imgui.cpp",
        "imgui_draw.cpp",
        "imgui_widgets.cpp",
        "imgui_demo.cpp",
        "imgui_tables.cpp",
        "backends/imgui_impl_opengl3.cpp",
    ],
    includes = [
        "",
        "backends",
    ],
    copts = ["-Wno-deprecated-enum-enum-conversion"],
)
