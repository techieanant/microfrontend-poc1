POC application which uses micro frontend architecture and lerna monorepo pattern to share dependencies between apps using webpack 5 module federation.


Install and Run: `yarn && yarn start`


# Notes

- App 1 and App2 share the root node_modules
- `yarn start` will start host app `app1` and remote app `app2` on http://localhost:3001/ & http://localhost:3002/ respectively
- app1 uses `styled-components` dependancy from app2
