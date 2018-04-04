# Apollo and GraphQL with React Webinar Demonstration

## Requirements

- Node.js (version 8 or later)
- Web Browser

## Instructions

1. Clone/Download this repository. If downloading the zip file, then extract the zip file.
1. Open a terminal window and change to the folder containing the "package.json" file.
1. Run the following commands:

```bash
npm install

npm run start-server
```
1. Open a second terminal window and change to the folder containing the "package.json" file.
1. Run the following command:

```bash
npm run start-client
```

1. Your system's default web browser should open and browse to the URL http://localhost:3000.

## Modifying the Project

The server files can be modified in the "server-src" folder. The "server-dist" folder is generated by the "start-server" command. Do not edit the files in the "server-dist" folder as they will be overwritten. The client files can be modified in the "public" and "src" folders. The "src" folder contains the JavaScript code for the Apollo Client and React Components.