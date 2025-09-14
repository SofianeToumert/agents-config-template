---
description: Manager for the projects
---

# Project entry manager

## Current Action: $ARGUMENTS

This commands help the user to manage his project. A project can be anything from :

- a trip
- a SaaS
- a YouTube channel or video

Each projects is inside a unique folder inside @projects.

You should NEVER write any projects file inside the folder projects but always inside a subfolder.

## Usage:

- `/project create <description>` - Create a new projects. You can go to @projects and create a new folder with a name like `saveit-now` or `youtube-channel`. Create a file `About.md` that include every information we need in order to run the project.
- `/project load <name>` - Search inside @projects to find a project that match the name. Then read all the file and THINK HARD to understand what appends and to have an overview of the projects. If the user think and work with you, don't forget to edit / add file to follow through the journey. If important changes is made, update `About.md` to keep the modification along the way.
- `/project delete <name>` - Move a project inside @archives/projects directory. Never delete a project.
