# Loom Build Tool

Loom is a modern build tool for Java based projects.
It focuses on simplicity, conventions, ease of use and performance.
It uses a very simple, declarative configuration (YAML) and
convention over configuration to reduce the configuration to a bare minimum.


# Requirements

Loom requires **JDK 9** to build and run but it can build projects
**targeting Java 6-9** through JDKs cross-compile functionality.


# Use Loom in your project

Change to your project directory and enter:

    curl -s https://loom.builders/installer.sh | sh

After installation succeeded, run your first build by entering:

    ./loom build

This builds sources beneath `src/main/java/` without external dependencies.


For more info, visit the
[Loom documentation](https://loom-build-tool.readthedocs.io) and our
[example projects](https://github.com/loom-build-tool/loom-examples).


# Loom quick demonstration (Video)

<iframe width="560" height="315" src="https://www.youtube.com/embed/g8lLM5AovTI" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
