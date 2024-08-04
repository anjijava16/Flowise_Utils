# Flowise_Utils
Low Code Generations Gen AI

# Pre Requests
1. npm i -g pnpm

   
# Steps
1. git clone https://github.com/FlowiseAI/Flowise.git

2. cd Flowise


## Download and Install NodeJS >= 18.15.0

1. Install Flowise

2. npm install -g flowise
2.  Start Flowise
3. npx flowise start

### With username & password

4. npx flowise start --FLOWISE_USERNAME=user --FLOWISE_PASSWORD=1234

5. http://localhost:3000

# Local Setup
1. welcome@jaisairams-Laptop Flowise % pwd
/Users/welcome/Desktop/Techzone_2024/LLM_FLOW_NPM/Flowise
2. welcome@jaisairams-Laptop Flowise %



elcome@jaisairams-Laptop Flowise % npx flowise start
2024-08-04 18:30:02 [INFO]: Starting Flowise...
(node:23738) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
(Use `node --trace-deprecation ...` to show where the warning was created)
2024-08-04 18:30:02 [ERROR]: uncaughtException:  listen EADDRINUSE: address already in use :::3000
Error: listen EADDRINUSE: address already in use :::3000
    at Server.setupListenHandle [as _listen2] (node:net:1902:16)
    at listenInCluster (node:net:1959:12)
    at Server.listen (node:net:2061:7)
    at Object.start (/opt/homebrew/lib/node_modules/flowise/dist/index.js:1839:12)
    at async /opt/homebrew/lib/node_modules/flowise/dist/commands/start.js:148:17
    at async Start.run (/opt/homebrew/lib/node_modules/flowise/dist/commands/start.js:144:9)
    at async Start._run (/opt/homebrew/lib/node_modules/flowise/node_modules/@oclif/core/lib/command.js:80:22)
    at async Config.runCommand (/opt/homebrew/lib/node_modules/flowise/node_modules/@oclif/core/lib/config/config.js:301:25)
welcome@jaisairams-Laptop Flowise %

