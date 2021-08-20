<h1 align="center">
    build2 Default Options
</h1>

<p align="center">
    Some Tool Config Files for the build2 Toolchain for My Personal Defaults
</p>

## Usage
First, clone the repository and change into its root.

    git clone https://github.com/lyrahgames/build2-default-options.git
    cd build2-default-options

For simplicity, you should use an in-source build.

### Temporary Configuration
Install the files by using a temporary configuration.

    b install config.install.root=$HOME

For uninstallation, you have to remember the variables.

    b uninstall config.install.root=$HOME

### Persistent Configuration
Set the persistent installation directory where the `.build2` folder will be located.

    b configure: config.install.root=$HOME

For install, run the install command.

    b install

For uninstall, run the uninstall command.

    b uninstall

