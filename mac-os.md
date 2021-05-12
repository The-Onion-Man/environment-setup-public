### Install Homebrew
Homebrew is a package manager for macOS and Linux - it’s what you’ll use to install just about everything else. To install it, navigate [here](https://brew.sh/) and paste the provided script into your terminal.
Once Homebrew is set up, you’ll be able to use the command `brew install` to install any of the other packages.

### Install git
You’ll be using Git and Github for version control - you can read more on that [here](https://github.com/CodesmithLLC/precourse-part-1/blob/master/GitHub.md), and it’s important that you take the time to become familiar with it.
To install git, run the command `brew install git`.

### Node & Node version manager
The next thing you’ll need to install is Node.js, a server-side runtime environment for JavaScript which allows us to use it for backend code. All of the units you work on at Codesmith will use Node, so it’s important that you set this up as early as possible! 

You’ll want to install the latest stable version of Node. Something to note, however, is that you might sometimes find yourself using other packages that don’t support Node’s latest stable version - so you may occasionally need to upgrade or downgrade your version of Node to prevent compatibility issues. This probably won’t happen too frequently, but since it’s sometimes inevitable, we recommend that you install Node using a version manager such as `nvm`. This will allow you to quickly and easily switch between different Node versions when necessary.

1.  To install nvm, run `brew install nvm`.

2.  Verify the installation by running the following command:

    `command -v nvm`

    This should return 'nvm' in your terminal. If you receive 'command not found' or no response at all, close your current terminal, reopen it, and run the command again.


3.  Install the latest stable LTS release of Node.js by running the following command:

    `nvm install --lts`

    Note: At the time of writing, the latest stable LTS release of Node.js is 14.16.0.


4.  Verify what version of Node is installed by running the following command:

    `nvm ls`

5.  Verify that Node.js is installed and the currently default version with the following command:

    `node --version`

    Then verify that you have npm as well with:

    `npm --version`
