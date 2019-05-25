# Configuration Management with Ansible

We will be using Ansible as it is the fastest to get going and learn to a useable state.

If you have not already please review the Workstation section for your chosen platform. If you already have Ansible installed please continue on, otherwise please install ansible for your chosen platform

The first thing is to understand what Ansible does and does not do. Ansible is a configuration management tool that can be used automate just about anything these days. The best way to explain what it is, is to compare it to something you may be familiar with. Bash scripts are probably the closest thing that comes to mind when starting to use Ansible. You use Ansible in much the same way.

In a Bash srript to install Apache (or httpd) you would do something like this:

```
#!/bin/bash
sudo yum install httpd
```

This does solve this one scenario, but how do you get this script onto a machine? 
