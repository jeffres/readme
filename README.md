# Open source projects presentation

Hi, I am **Geoffrey Lienhart**, a **DevOps engineer** from Strasbourg, France.

Here you will find a summary of my open source projects available at
https://gitlab.com/glienhart/.

You can contact me on
[LinkedIn](https://www.linkedin.com/in/geoffrey-lienhart-41462870)
if you wish. 🙂

## Kubernetes

### Monitoring stack (Prometheus/Grafana)

The [`k8s-monitoring`](https://gitlab.com/glienhart/k8s/k8s-monitoring) repository
illustrates the deployment of a Prometheus/Grafana monitoring stack
in a Kubernetes cluster, along with automatic provisioning of dashboards and alerts.

## Ansible

### Roles

The [`ansible/roles` group](https://gitlab.com/glienhart/ansible/roles)
contains Ansible roles (as the name suggests 😉).

All roles are **fully tested** for various Linux distributions with
[Ansible Molecule](https://ansible.readthedocs.io/projects/molecule).

Those are:

| Role name             | Repository                                        | Description
| ---                   | ---                                               | ---
| `glienhart.app`       | glienhart/ansible/roles/ansible-role-app>         | Manage applications |
| `glienhart.packer`    | glienhart/ansible/roles/ansible-role-packer>      | Install and run [Hashicorp Packer](https://www.packer.io) |
| `glienhart.terraform` | glienhart/ansible/roles/ansible-role-terraform>   | Install and run [Hashicorp Terraform](https://www.terraform.io) |

### Roles usage example

The
[`ansible-roles-usage-example`](https://gitlab.com/glienhart/ansible/ansible-roles-usage-example)
repository demonstrates **how to** use the roles above and manage dependencies with
[Ansible Galaxy](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html).

It installs various applications such as
[Docker](https://docker.com),
[Terraform](https://www.terraform.io/),
[kubectl](https://kubernetes.io/docs/reference/kubectl)
...

### Bootstrap

The
[`ansible-bootstrap`](https://gitlab.com/glienhart/ansible/ansible-bootstrap)
repository provides scripts to easily install Ansible tools.

## dotfiles

The [`dotfiles` group](https://gitlab.com/glienhart/dotfiles)
contains my personal configuration files for the tools I use.

Currently only a configuration for Neovim is provided in
the [`nvim`](https://gitlab.com/glienhart/dotfiles/nvim)
repository.
