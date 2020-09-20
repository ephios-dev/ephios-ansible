
# ephios-ansible


## Uberspace

[Uberspace](https://uberspace.de/) is a shared hosting service. In `uberspace` there is an ansible playbook to provision ephios on an uberspace that you have registered before. The playbook expects an unmodified uberspace 7 without other applications running on it.

To use the playbook:

1. Copy `hosts.example` to `hosts` and change hostname, username, additional url that ephios will be served from and the ssh key to authenticate.
2. Have a look at `deploy.yml` and other files and change configuration as needed.
3. Run the playbook, e.g.: `ansible-playbook deploy.yml -i hosts -v`

