# This file existed originally to enable quick local development via local_repository.
    # See ./ImplementationReadme.md for details on local development.
    # Why? local_repository doesn't work without a WORKSPACE, and new_local_repository requires overwriting the BUILD file (as of Bazel 7).

workspace(name = "hedron_compile_commands")

load("@hedron_compile_commands//:workspace_setup.bzl", "hedron_compile_commands_setup")
hedron_compile_commands_setup()
