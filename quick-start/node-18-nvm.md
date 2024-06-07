---
description: 'Last update: June 6, 2024,'
---

# Node 18: NVM

\
As of today, Agua is only supported with Node.js version 18 LTS. If you are using a more recent version of Node.js, we recommend installing and using NVM to manage your Node.js versions.

NVM (Node Version Manager) allows you to install different versions of Node.js and switch between them as needed with a single command.

[https://github.com/coreybutler/nvm-windows/](https://github.com/coreybutler/nvm-windows/)

## For Windows

1. Navigate to the NVM GitHub repository releases page:\
   [https://github.com/coreybutler/nvm-windows/releases](https://github.com/coreybutler/nvm-windows/releases)
2. In the latest commit, go to the assets section and download the `nvm-setup.exe` file.
3. Run the `nvm-setup.exe` file to install NVM on your system.

#### Verifying the Installation

After installing NVM, you can verify the installation and check the current Node.js version by running:

```sh
nvm current
```

Output:

```
v18.17.1
```

This command shows the version of Node.js currently in use.

#### Basic NVM Commands

#### List Installed Versions

```sh
nvm list
```

Output:

```arduino
* 18.17.1 (Currently using 64-bit executable)
```

This command shows the versions of Node.js installed on your system.

#### Switch to a Specific Version

```sh
nvm use 18.17.1
```

Output:

```arduino
Now using node v18.17.1 (64-bit)
```

This command switches to the specified version of Node.js.

#### Install a Specific Version

```sh
nvm install 18.17.1
```

Output:

```rust
Downloading node.js version 18.17.1 (64-bit)...
Extracting node and npm...
Complete
npm v9.6.7 installed successfully.
Installation complete. If you want to use this version, type nvm use 18.17.1
```

This command installs the specified version of Node.js.

#### List Available Versions

```sh
nvm list available
```

Output:

```sql
sqlCopy code|   CURRENT    |     LTS      |  OLD STABLE  | OLD UNSTABLE |
|--------------|--------------|--------------|--------------|
|    21.5.0    |   20.10.0    |   0.12.18    |   0.11.16    |
|    21.4.0    |    20.9.0    |   0.12.17    |   0.11.15    |
|    21.3.0    |   18.19.0    |   0.12.16    |   0.11.14    |
|    21.2.0    |   18.18.2    |   0.12.15    |   0.11.13    |
|    21.1.0    |   18.18.1    |   0.12.14    |   0.11.12    |
|    21.0.0    |   18.18.0    |   0.12.13    |   0.11.11    |
|    20.8.1    |   18.17.1    |   0.12.12    |   0.11.10    |
|    20.8.0    |   18.17.0    |   0.12.11    |    0.11.9    |
|    20.7.0    |   18.16.1    |   0.12.10    |    0.11.8    |
|    20.6.1    |   18.16.0    |    0.12.9    |    0.11.7    |
|    20.6.0    |   18.15.0    |    0.12.8    |    0.11.6    |
|    20.5.1    |   18.14.2    |    0.12.7    |    0.11.5    |
|    20.5.0    |   18.14.1    |    0.12.6    |    0.11.4    |
|    20.4.0    |   18.14.0    |    0.12.5    |    0.11.3    |
|    20.3.1    |   18.13.0    |    0.12.4    |    0.11.2    |
|    20.3.0    |   18.12.1    |    0.12.3    |    0.11.1    |
|    20.2.0    |   18.12.0    |    0.12.2    |    0.11.0    |
|    20.1.0    |   16.20.2    |    0.12.1    |    0.9.12    |
|    20.0.0    |   16.20.1    |    0.12.0    |    0.9.11    |
|    19.9.0    |   16.20.0    |   0.10.48    |    0.9.10    |
```

This command shows the Node.js versions available for installation. For a complete list, visit [https://nodejs.org/en/download/releases](https://nodejs.org/en/download/releases).

#### Verifying the NVM Installation

To verify if NVM is installed correctly, run:

```sh
nvm version
```

This command will show the version of NVM installed on your system.

## MacOS

#### 1. Run the NVM Installer

In your terminal, run the NVM installer like this:

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

or

```sh
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

You can use curl or wget depending on the command available on your device. These commands will clone the NVM repository to a `~/.nvm` directory on your device.

#### 2. Update Your Profile Configuration

The installation process from step 1 should also automatically add the NVM configuration to your profile. If you're using zsh, that would be `~/.zshrc`. If you're using bash, that would be `~/.bash_profile` or another profile file.

If it doesn't automatically add the NVM configuration, you can add it yourself to your profile file:

```sh
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

This command loads NVM for use.

#### 3. Reload the Shell Configuration

With your profile configuration updated, now you will reload the configuration for your terminal to use:

```sh
source ~/.bashrc
```

With this command executed, NVM is ready for you to use. You can confirm that NVM is installed correctly by running:

```sh
nvm -v
```

This should show the version of NVM installed.

By following these steps, you can manage your Node.js versions efficiently using NVM and ensure compatibility with Agua's requirements.
