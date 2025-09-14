# MyAngularProject

```
npm run build
npm run serve:ssr:angularCrud
```

1. Build the application with the command as ng build. This will generate a dist folder in your directory for both browser and server. 
2. Run the server by using the command: node dist/<your-ssr-aap-name>/server/server.mjs

    -   app.config.server.ts: Used for server application configuration.
    -   src/main.server.ts: It serves as the server-side rendering logic’s entry point. We can manage the main server application startup with the aid of this file.
    -   src/app/app.server.module.ts: Includes the server-side application module for Angular Universal SSR.
    -   src/server.ts: This file is used by the Express server to render the Angular application on the server-side.