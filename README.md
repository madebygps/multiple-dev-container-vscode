## Demo Idea

Rough steps to debug in both containers using a single VS Code window:

- Open local VS Code window on cloned repo.
- `Dev Containers: Reopen in Container`, pick Container 1. (Reloads window on container 1.)
- Open hello.go, place breakpoint on "Hello, world!" line and start debugging.
- `Dev Containers: Switch Container`, pick Container 2. (Reloads window on container 2.)
- Open hello.js, place breakpoint on "Hello, world!" line and start debugging.
