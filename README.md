Ansible Harbor Server
=====================

- Activate .venv if present then install pip deps: `pip3 install ansible openstacksdk`
- Install requirements `ansible-galaxy collection install -r requirements.txt`
- Obtain a copy of clouds.yaml for your project, place it in `~/.configs/openstack/clouds.yaml` and rename `openstack` to `jupyter-development`
- Test using `openstack --os-cloud=jupyter-development coe cluster template list`, which will always return built-in templates