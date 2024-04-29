This is an unmodified vite + react + typescript + SWC template (created completely with `npm create vite@latest`)

To see error, run:

1. `npm config set '@caspeco:registry' https://node.bit.cloud`
2. `npm install @caspeco/casper-ui-library.base-ui.theme`
3. Error:
    ```
    npm error code ERESOLVE
    npm error ERESOLVE unable to resolve dependency tree
    npm error
    npm error While resolving: vite-project@0.0.0
    npm error Found: react@18.3.1
    npm error node_modules/react
    npm error   react@"^18.2.0" from the root project
    npm error   peer react@">=18" from @chakra-ui/react@2.8.2
    npm error   node_modules/@chakra-ui/react
    npm error     peer @chakra-ui/react@"^2.8.2" from @caspeco/casper-ui-library.base-ui.theme@2.2.1
    npm error     node_modules/@caspeco/casper-ui-library.base-ui.theme
    npm error       @caspeco/casper-ui-library.base-ui.theme@"*" from the root project
    npm error   4 more (@emotion/react, @emotion/styled, framer-motion, react-dom)
    npm error
    npm error Could not resolve dependency:
    npm error peer react@"18.2.0" from @caspeco/casper-ui-library.base-ui.theme@2.2.1
    npm error node_modules/@caspeco/casper-ui-library.base-ui.theme
    npm error   @caspeco/casper-ui-library.base-ui.theme@"*" from the root project
    npm error
    npm error Fix the upstream dependency conflict, or retry
    npm error this command with --force or --legacy-peer-deps
    npm error to accept an incorrect (and potentially broken) dependency resolution.
    npm error
    npm error
    npm error For a full report see:
    npm error C:\Users\<username>\AppData\Local\npm-cache\_logs\2024-04-29T15_53_22_883Z-eresolve-report.txt

    npm error A complete log of this run can be found in: C:\Users\<username>\AppData\Local\npm-cache\_logs\2024-04-29T15_53_22_883Z-debug-0.log
    ```
