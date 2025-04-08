# Hello Jenkins

This is a simple Java application to test Jenkins pipelines.

## Structure

- `src/HelloJenkins.java` — prints a greeting message

## How to Run

1. Compile:
    ```bash
    javac -d build src/HelloJenkins.java
    ```

2. Run:
    ```bash
    java -cp build HelloJenkins
    ```

## Jenkins Integration

This app is used to test a Jenkins pipeline with build, test (if added), and deploy stages.
