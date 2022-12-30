## Installing NodeJS and NPM

To run react, you would need to dwonload NodeJS and NPM. This can first be done by downloading NPM, which will then be used to download NPM.

Firstly, run:

```
sudo apt update
```


1. Download NVM using the following command:

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

To check if has been succesfuuly isntalled, run the follwoing command:

```
nvm -v
```

Note: To get the latest version of nvm, you can go on the [nvm github repository](https://github.com/nvm-sh/nvm#installing-and-updating)


2. Download NPM and NodeJS

To download NPM and NodeJS, run the following command:

```
nvm install --lts
```

You can verify the download from the following command:

```
node -v
```
```
npm -v
```


## Creating a New Project

**Note: Before starting a project, you will need to install NodeJs and NPM.**

To set up a development environment for React, you can use the **'create-react-app'** tool, which is a command-line utility that generates a basic React development environment.

Here is an outline of the steps you can follow to set up a React development environment using **'create-react-app'**:

1. Run the following command:

```
npx create-react-app my-app
```

Replace **'my-app'** with the desired name for your app. This will create a new directory with the same name and generate a basic React development environment inside it.

2. Starting up the react website can be done by going into the directory created and using npm to start it as follows:

```
cd my-app
```

```
npm start
```



