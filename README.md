# nextjs-devcontainer-template

This template provides an example for setting up a development environment for Next.js applications using Dev Containers. 
To set up the container, please follow the instructions below:

## Prerequisites

Ensure that you have the following installed on your machine:

- [VS Code](https://code.visualstudio.com/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) for VS Code

## Setup Instructions

1. Create a New Repository:

    - Navigate to the [original repository page](https://github.com/matsu3m/nextjs-devcontainer-template) on GitHub.
    - Click on `Use this template` to create a new repository based on this template.

2. Clone the Project:

    - Clone the newly created repository to your local machine.
    - Open the cloned project in VS Code.

3. Reopen in Container:

    - Open the Command Palette in VS Code.
    - Select `Dev Containers: Reopen in Container`. VS Code will then start building the container and open the project inside it.

4. Start the Dev Server:

    - Once the container is running, open the terminal in VS Code.
    - Run the command `npm run dev` to start the dev server.
    - Access your application by navigating to http://localhost:3000 in your local web browser.
