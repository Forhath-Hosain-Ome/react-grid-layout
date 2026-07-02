## Linux

# Install the version you want (if not already installed)
nvm install 20

# Switch the current terminal session to that version
nvm use 20


## Windows

# Install the version
nvm install 20.11.0

# Switch to that version system-wide
nvm use 20.11.0



nvm install 20.20.2
nvm use 20.20.2
npm install -g yarn
rm -rf node_modules package-lock.json
yarn install
yarn dev