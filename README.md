

# Photino.Vite.Dotnet Hello World Template
### Photino is a lightweight open-source framework for building native, cross-platform desktop applications with Web UI technology
### Vite is a build tool and a local development server that enhances the front-end development experience. It lets you configure a development environment for Vue or React frameworks with TS support


## Workflow
The solution has a DEBUG and a RELEASE config defined. They are meant to be used accordingly for Development and Production workflows.

### Development workflow:
The workflow is designed to allow smooth work on either the frontend or the backend independently. Therefore in the Development(DEBUG) mode the frontend is designed to be run separately from the backend. To get going

 - open 'frontend' dir in you favorite editor/terminal
 - npm run dev
 - open the main solution file in you favorite backend IDE
 - choose the DEBUG compiler configuration
 - Run or Debug the project

After executing the above steps the backend will serve up the view from the vite dev server and you should have HMR, exactly like you would in a browser window.

### Production workflow
This template doesn't change the original building workflow which was designed by Photino therefore refer to the Photino documentation for all details: https://docs.tryphotino.io/Photino-.NET

## Want to replace React ?
Easiest thing in the world. Remove everything from the 'frontend' directory and replace with your own framework. The only requirement is that it builds into 'dist' (for production builds) and serves files on port 5173 for development workflows.