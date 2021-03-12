# Really Simple WAR Application

This is an extremely basic "WAR" style application that can be deployed to Cloud Foundry or with the Java Cloud Native Buildpacks.

The app just serves up some static content, but that can often be enough for a demo or for troubleshooting the deployment of an application using Tomcat.

## Instructions

1. [Optional] Edit `manifest.yml` and update the route.
2. Run `cf push`.

There is nothing to build or compile.

The app should deploy & you should see Tomcat installed by the Java buildpack. Accessing the application should result in the bundled static resources being accessible.
