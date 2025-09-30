package(default_visibility = ["//visibility:public"])

load("//build_tools/py:py.bzl", "dbx_py_pypi_piplib")

licenses(["notice"])  # MIT

dbx_py_pypi_piplib(
    name = "setuptools_scm",
    pip_version = "8.3.1",
    setup_requires = [
        "//pip/setuptools",
        "//pip/tomli",
        "//pip/packaging",
    ],
    sha256 = ["3d555e92b75dacd037d32bafdf94f97af51ea29ae8c7b234cf94b7a5bd242a63"],
    deps = [
        "//pip/packaging",
        "//pip/setuptools",
        "//pip/tomli",
        "//pip/typing_extensions",
    ],
)
