# Data Science Portfolio

Welcome to my Data Science Portfolio! This repository contains my data science projects and blog posts, built using Jekyll.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)

## Introduction

This portfolio showcases my data science projects and blog posts. It is built using Jekyll, a static site generator, and hosted on GitHub Pages [here](https://meeslindhout.github.io/)

## Setup

To set up the development environment, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/meeslindhout/meeslindhout.github.io.git
    cd meeslindhout.github.io
    ```

2. **Open the project in VS Code**:
    ```sh
    code .
    ```

3. **Build and run the development container**:
    - Ensure you have Docker installed and running. You can download Docker from the [official website](https://www.docker.com/products/docker-desktop).
    - Open the Command Palette (Ctrl+Shift+P) and select `Remote-Containers: Reopen in Container`.
    - This will build the development container and open the project in a containerized environment. (This may take a few minutes the first time you run it as it needs to download the necessary container image and dependencies.)

4. **Install dependencies**:
    The `postCreateCommand` in the `.devcontainer/devcontainer.json` will automatically run `bundle install` to install the necessary gems that are used for the website.

## Usage

To serve the site locally and preview your changes:

1. **Run Jekyll**:
    ```sh
    bundle exec jekyll serve
    ```

2. **Open the site**:
    - The site will be available at `http://localhost:4000`.
    - The port 4000 is forwarded and will open the generated website in the preview window in VS Code for convenience.

## Acknowledgements
- Theme is based on [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)
- Custom css has been sourced from [Chris Tan](https://github.com/chriskhanhtran)