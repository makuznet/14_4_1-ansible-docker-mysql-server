# Ansible playbook examples
> This repo comprises two examples of Ansible playbooks:
1. Installing Docker app.
2. Installing MySQL-Server app.

## Usage
To check connectivity:
```bash
ansible localhost -m ping
```
To install Docker:
```bash
ansible-playbook docker.yml
```
To install MySQL server:
```bash
ansible-playbook mysql-server.yml
```
## Installation
### Ansible (MacOS)
```bash
https://www.python.org/ftp/python/3.9.5/python-3.9.5-macosx10.9.pkg
python get-pip.py
pip install ansible
```
## Acknowledgments
This repo was inspired by [skillfactory.ru](https://skillfactory.ru/devops#syllabus) team

## See also 
- [ansible.builtin.apt](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/apt_module.html)

## License
Follow all involved parties licenses terms and conditions.