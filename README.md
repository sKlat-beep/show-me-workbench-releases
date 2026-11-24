# show-me workbench releases

Prebuilt binaries of the show-me workbench, the desktop window that the `show-me` agent skill opens to collect answers from its operator.

Each release holds one program file per platform. The skill pins the exact file it expects in its `release.json`, by version, tag and SHA-256, downloads it on first use, and refuses any file whose hash differs. The binaries are built locally from the private source, so this repository holds releases only.

The executables are not code-signed, so Windows SmartScreen may warn on first run.
