# croatapps-scripts

In order to run this scripts you must have an Ubuntu 20.04 server/desktop base already setup. You can be connected in local or via SSH.

<img src="https://avatars.githubusercontent.com/u/37509725?v=4" align="right"
     alt="CroatApps logo" width="200" height="200">

## How It Works

1. Download the install script.
2. Edit variables to tune up your environment setup.
3. Run the script and wait until finish setting all up and ready to go.

<details><summary><b>Show instructions</b></summary>

### Download

Choose from below using `wget` or `curl` for download.

A. Download it using `wget`:


    wget https://github.com/CroatApps/croatapps-scripts/raw/main/install_croat.sh


B. Download it using `curl`:


    curl https://github.com/CroatApps/croatapps-scripts/raw/main/install_croat.sh



### Edit variables

For configuring the variables, we will be using `nano`, but you can chose whatever editing tools like.

1. Edit using `nano`:

    ```sh
     nano -l install_croat.sh
    ```

2. The most important variables are between lines 8-12, this ones tells the script if it will be a simple node, needs a wallet, it needs the pool setup... Please do not edit lines below line 40 unless you know what you are doing.


### Run it

1. Make it executable

    ```sh
    chmod +x install_croat.sh
    ```

2. Run must be done with `sudo` rights but can't be done under user `root` account:

    ```sh
    sudo ./install_croat.sh
    ```

### Ending

1. Leave the script running, depending on what you have selected it can take up to several hours.
2. At the end will notify when it's all done and fully setup or will print errors in console with exitting the script.
