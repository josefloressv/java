# Demo Application

This is a demo application built with Kotlin and Spring Boot.

## Stack

- **Kotlin**: Programming language
- **Spring Boot**: Framework for building Java-based applications
- **Gradle**: Build tool
- **JUnit 5**: Testing framework

## Prerequisites

- JDK 21 (managed by SDKMAN)
- Gradle

## Setup

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd kotlin_app/demo
    ```

2. **Install SDKMAN**:
    ```sh
    curl -s "https://get.sdkman.io" | bash
    source "$HOME/.sdkman/bin/sdkman-init.sh"
    ```

3. **Install JDK 21**:
    ```sh
    sdk install java 21.0.5-amzn
    sdk use java 21.0.5-amzn
    ```

4. **Install Gradle**:
    ```sh
    sdk install gradle
    ```

## Running the Application

1. **Build the application**:
    ```sh
    ./gradlew build
    ```

2. **Run the application**:
    ```sh
    ./gradlew bootRun
    ```

The application will start on `http://localhost:8080`.

## Running Tests

To run the tests, use the following command:
```sh
./gradlew test