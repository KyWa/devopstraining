# DevOps Training

The purpose of this guide is to provide a one stop shop to get setup and start using "DevOps" tooling in your enviornment. The order of things is making sure the workstation is setup and ready to use certain tooling. The tools in question have been chosen not only because this is what I use, but because they are somewhat industry standard as being easy to use and have good documentation and great communities (Ansible especially). The current modern IT tool landscape is a bloated mess and can seem hard to navigate. That is what we hope to do here, get someone to a point of being able to use tooling in an effective manner and translate that into real value.

## Workstation Setup (Linux, Mac, Windows, ChromeOS [coming soon])
* Tools, configs, applications

## Scripting (Bash, Python)
* Basic usage
* getting files

## Config Management (Ansible)
* Explination
* Setup
* how to run
* ways to run
* Ansible Vault

## Tooling (Git, Terraform)
* source control
* tags
* usage

Support Matrix

| Distribution   | < MongoDB 3.2 |    MongoDB 3.4     |    MongoDB 3.6     |    MongoDB 4.0     |
| -------------- | :-----------: | :----------------: | :----------------: | :----------------: |
| Ubuntu 14.04   |  :no_entry:   | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Ubuntu 16.04   |  :no_entry:   | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Ubuntu 18.04   |  :no_entry:   |        :x:         | :white_check_mark: | :white_check_mark: |
| Debian 8.x     |  :no_entry:   | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Debian 9.x     |  :no_entry:   |        :x:         | :white_check_mark: | :white_check_mark: |
| RHEL 6.x       |  :no_entry:   | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| RHEL 7.x       |  :no_entry:   | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Amazon Linux 2 |  :no_entry:   | :white_check_mark: | :white_check_mark: | :white_check_mark: |

- :white_check_mark: - fully tested, should works fine
- :interrobang: - maybe works, not tested
- :x: - don't have official support
- :no_entry: - MongoDB has reached EOL
