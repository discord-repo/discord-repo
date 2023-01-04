.. image:: https://github.com/discord-repo/discord-repo/actions/workflows/nightly.yml/badge.svg?branch=master
    :target: https://github.com/discord-repo/discord-repo/actions/workflows/nightly.yml

Discord deb repo
----------------

Usage::

    sudo apt install apt-transport-https curl
    echo deb https://discord-repo.github.io/apt/ubuntu focal main | sudo tee /etc/apt/sources.list.d/discord.list
    curl -s https://discord-repo.github.io/apt/public.key | sudo apt-key add -
    sudo apt update
    sudo apt install discord
