# Java Playground

## Mac OS environment setup
### Visual Studio Code

Follow this guide https://code.visualstudio.com/docs/java/java-tutorial
1. Installed Coding Pack for Java
2. Installed the Extension Pack for Java (from Microsoft)

### JDK Manager
Installed SDKMAN from https://sdkman.io/
SDKMAN is a version manager for Java, Kotlin, Maven, and other JVM tools.
this also manage JAVA_HOME variable

```sh
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
```

Configuration
```sh
# Enable sdkman_auto_env=true
vim ~/.sdkman/etc/config
```

Commands
```sh
# Install Specific JDK Versions
sdk install java 17-open
sdk install java 21.0.5-amzn
sdk install java 23.0.1-amzn

# List JDK Candidates
sdk list java

# Switch between versions in the current terminal
sdk use java 17-open

# Set default version
sdk default java 17-open

# Get the current version
sdk current java

# Pin current JDK version for a project, create .sdkmanrc file
sdk env init

# To use the version pinned (should be used when open a shell from the project folder)
sdk env

```