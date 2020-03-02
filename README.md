mac-ansible
===========

Simple Ansible role to setup a Mac from scratch. Adapted from https://github.com/adamchainz/mac-ansible

Getting Started
---------------

1. Install [homebrew](http://brew.sh/) with the command from the site
2. `brew install pyenv`
3. `pyenv install <latest_python_version>` (Check playbook up to date) and finish the installation via Homebrew as described
    on the [Pyenv docs](https://github.com/pyenv/pyenv#homebrew-on-macos).
4. `python -m venv venv`
5. `source venv/bin/activate`
6. `pip install ansible` (always the best way to install Ansible)
7. Then `./playbook.yml`

Structure
----------
This is just a single ansible role. It installs software using brew/brew casks and links configuiration files to the standard location so it can be source controlled. Most of the tasks have one or more tags so it can be run individually if needed.
You can see the list of installed apps by looking at vars [main.yml](roles/macsetup/vars/main.yml) file.


Copy! Adapt!
------------------
I recommend to copy this repo and adapt it to the particular needs.
