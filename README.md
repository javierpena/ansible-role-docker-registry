# ansible-role-docker-registry

Simple role to deploy Docker registry with authentication support.

## Notes

This role deploys the official Docker Registry image, together with cesanta's
docker_auth image, and configures them to work together and form a working
registry with integrated authentication.

You will need to adapt the role for your needs (or send a pull request), since
it hardcodes a few variables, like the service URL. You can set the
user and RBAC rules by editing the `defaults/main.yml` file in the role.

## License

Apache 2.0

## Author

* Javier Peña ([@fj_pena](https://github.com/javierpena))
