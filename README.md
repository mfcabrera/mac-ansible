mac-ansible
===========

Simple Ansible role to setup a Mac from scratch. Adapted from https://github.com/adamchainz/mac-ansible

Getting Started
---------------

1. Install [homebrew](http://brew.sh/) with the command from the site
2. `brew install pyenv`
3. `pyenv install <latest_python_version>` (Check playbook up to date) and finish the installation via Homebrew as described
    on the [Pyenv docs](https://github.com/pyenv/pyenv#homebrew-on-macos).
4. Make sure pyenv's python on path (it will be after my shell settings are in place from playbook)
5. `python -m venv venv`
6. `source venv/bin/activate`
5. `pip install ansible` (always the best way to install Ansible)
6. Then `./playbook.yml`

Copy! Adapt!
------------------
I recommend to copy this repo and adapt it to the particular needs.
