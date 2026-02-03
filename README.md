# Basic Dockerfile

A basic Dockerfile to create a Docker image containing a single instruction to print `Hello, Captain!` to the console before exiting.

## How to run

1. Build the image from the Dockerfile

    ```bash
    docker build -t basic-dockerfile .
    ```

2. Run the container image

    ```bash
    docker run --rm basic-dockerfile
    ```

## Acknowledgements

This project was inspired by [roadmap.sh](https://roadmap.sh/projects/basic-dockerfile).
