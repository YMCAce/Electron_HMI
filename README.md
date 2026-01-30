# Electron_HMI

This Electron App is made from me to gain some knowledge in building web based solutions, with my knowledge in industrial automation (plc) in mind.

The goal is to create an app that runs on a plc, that takes less resources than C# based WPF apps.

## How to make the project work on your machine

Due to the size of the __node_modules__ file using __Electron__ the project size is bigger than the allowed size to upload on GitHub.

Since the __node_modules__ is ignored in the __.gitignore__ file and will not be uploaded, you have to build it your self after cloning the repository.

For that, use the __npm install__ command to rebuild your __node_modules directory__.
All dependencys for the rebuild ar kept in the __package.json__ file inside the project.
