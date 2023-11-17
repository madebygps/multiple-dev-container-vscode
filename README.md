# Working with multiple dev containers in VS Code

## Prerequisites

- [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed in VS Code.

## How to use multiple dev containers in a single VS Code window

- Open local VS Code window on cloned repo.
- From the command palette `Dev Containers: Reopen in Container`, pick Python Container. 
- This will open a new VS Code window connected to the selected container. 
- From the command palette `Dev Containers: Switch Container`, pick Node Container.
- This will reload the VS Code window connected to the selected container.

## How to use multiple dev containers in a multiple VS Code window

1. Open local VS Code window on cloned repo.
2. From the command palette `Dev Containers: Reopen in Container`, pick Python Container.
3. This will open a new VS Code window connected to the selected container.
4. Go to File > New Window.
5. In this new window, from the command palette `Dev Containers: Reopen in Container`, pick Node Container.
6. This will open a new VS Code window connected to the selected container.

## Additional Resources

- [Dev Containers Supporting tools and services](https://containers.dev/supporting)
- [Dev Containers Documentation for VS Code](https://code.visualstudio.com/docs/remote/containers)
- [Dev Containers Documentation](https://containers.dev/)