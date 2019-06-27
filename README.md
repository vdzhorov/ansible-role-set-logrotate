# set-logrorate

Simple role for setting up logrotation for mashines using nginx, apache and virtualmin.

## Getting Started

Define you parameters in defaults/main.yml. The role is set for automatic detection of running software so it should detect whether you are using, NGinx, Apache, Virtualmin and combination between the three. After this running the role is simple as this:

```ansible-playbook -i '<IP>,' playbooks/set-logrotate.yml```

### Prerequisites

No prerequisites required

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/latest/roadmap/ROADMAP_2_8.html) - Ansible 2.8

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## License

This project is licensed under the MIT License.

## Company

* **Delta.BG**

## Acknowledgments

* Tired of getting setting logrotate by hand. Also not good when the a disk of client service gets filled because of logs.
