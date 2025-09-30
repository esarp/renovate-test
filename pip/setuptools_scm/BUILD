package(default_visibility = ["//visibility:public"])

load("//build_tools/py:py.bzl", "dbx_py_pypi_piplib")

licenses(["notice"])  # MIT

dbx_py_pypi_piplib(
    name = "setuptools_scm",
    pip_version = "8.0.4",
    setup_requires = [
        "//pip/setuptools",
        "//pip/tomli",
        "//pip/packaging",
    ],
    sha256 = ["b5f43ff6800669595193fd09891564ee9d1d7dcb196cab4b2506d53a2e1c95c7"],
    deps = [
        "//pip/packaging",
        "//pip/setuptools",
        "//pip/tomli",
        "//pip/typing_extensions",
    ],
)
