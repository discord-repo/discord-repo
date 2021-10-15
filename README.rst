Discord deb repo
----------------

Usage::

    sudo apt install apt-transport-https
    echo deb https://discord-repo.github.io/apt/ubuntu focal main | sudo tee /etc/apt/sources.list.d/discord.list
    sudo apt update
    sudo apt install discord
