# Project Guidelines

## Rules

- Always use Bun as the package manager and runtime environment.
- Always use TypeScript instead of Javascript.
- Always use Ultracite (Biome's zero-config preset) for code formatting and linting.
- Get up-to-date info with the Context7 MCP.
- Document and explain why the code is for.

## Architecture

- Follow the existing architecture patterns.

```txt
apps/
  - macos-desktop-controller - The main application that runs on macOS and controls the sumo-robot.
    - Built with Tauri v2, React, TypeScript and Tailwind CSS.
    - Provides the full UI to control the robot, telemetry, and settings.
```

## References

- [Ultracite Code Standards](ULTRACITE.md).