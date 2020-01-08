degited https://github.com/Microsoft/vscode-remote-try-node and tweaked

# Try Out Development Containers: [Reason](https://reasonml.github.io)

This is a sample project that lets you try out the **[VS Code Remote - Containers](https://aka.ms/vscode-remote/containers)** extension in a few easy steps.

> **Note:** If you're following the quick start, you can jump to the [Things to try](#things-to-try) section.

## Setting up the development container

Follow these steps to open this sample in a container:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To use this repository, you can either open a locally cloned copy of the code:

   - Clone this repository to your local filesystem.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

   Or open the repository in an isolated Docker volume:

    - Press <kbd>F1</kbd> and select the **Remote-Containers: Try a Sample...** command.
    - Choose the "Node" sample, wait for the container to start and try things out!
        > **Note:** Under the hood, this will use **Remote-Containers: Open Repository in Container...** command to clone the source code in a Docker volume instead of the local filesystem.

## Things to try

Once you have this sample opened in a container, you'll be able to work with it like you would locally.

> **Note:** This container runs as a non-root user with sudo access by default. Comment out `"remoteUser": "node"` in `.devcontainer/devcontainer.json` if you'd prefer to run as root.

## Credits

https://github.com/Microsoft/vscode-remote-try-node

## License

Copyright © Microsoft Corporation All rights reserved.<br />
Licensed under the MIT License. See LICENSE in the project root for license information.
