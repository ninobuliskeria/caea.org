# Hugo Conference Theme Demo

A demo conference website built with the [Hugo Conference Theme](https://github.com/medialesson/hugo-theme-conference).

See it in action on https://medialesson.github.io/hugo-theme-conference-demo.

## Getting started

### Prerequisites

1. [Hugo](https://gohugo.io/installation/) is installed on your machine.
2. You're familiar with [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

### Installation

1. Open a shell of your choice.
2. Clone this repository with SSH and submodules.
    ```shell
    git clone --recurse-submodules git@github.com:medialesson/hugo-theme-conference-demo.git
    ```
    **WARNING**: As the submodule requires authentication, you must clone the repository with SSH.
3. Switch to the repository directory.
4. Run Hugo in development mode:
    ```shell
    hugo server
    ```
5. View the demo conference website on http://localhost:1313/.