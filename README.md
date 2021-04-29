## Context
Just a simple todo app so I can figure out spring boot and all it's quirks.

## Setup
These steps are mainly for future me but also double as installation docs


1. Install VSCode: https://code.visualstudio.com/


2. Within VSCode install these extension packs:
> Java Extensions Pack

> Spring Boot Extension Pack


3. Ctrl+Shift+P (Windows) and search `Spring Initializer: Generate Maven Project`


4. Follow the prompts. For dependencies select:
> Spring Boot Dev Tools

> Spring Web


5. To run, Project\<project name>\src\main\java\com\<Group Id>\<Artifact>\<project>.java


6. To edit port: Project\<project name>\src\main\resources\application.properties. Add `server.port=<port>`
