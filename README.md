# k3s Ansible playbook

<!-- vim-markdown-toc GFM -->

* [Supported distro](#supported-distro)
* [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Acknowledgement](#acknowledgement)

<!-- vim-markdown-toc -->

## Supported distro

- [x] CentOS
- [ ] Debian
- [ ] Ubuntu

## Prerequisites

```sh
pipenv shell
pipenv install -r requirements.txt
```

## Usage

```sh
ansible-playbook -k -K playbook.yml -i hosts.ini
```

## Acknowledgement

- https://github.com/rancher/k3s-ansible/
