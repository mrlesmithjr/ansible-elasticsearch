# ansible-elasticsearch

Ansible role to install/configure Elasticsearch

> NOTE: This role has been completely rewritten and replaces my original
> `ansible-elasticsearch` role which has been renamed to [ansible-elasticsearch-old](https://github.com/mrlesmithjr/ansible-elasticsearch-old.git).
> I decided to rewrite this role as the original had a lot of residuals from years
> of different usages. The original will remain for historical purposes.

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/mrlesmithjr/ansible-elasticsearch/workflows/Molecule%20Test/badge.svg)

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## Role Variables

[defaults/main.yml](defaults/main.yml)
If you would like to add additional Elasticsearch parameters you only need to add
them to the `elasticsearch_configuration:` section. These variables are added as
YAML using the template. So there is no need to reconfigure the template either.

## Dependencies

## Example Playbook

[playbook.yml](playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [http://everythingshouldbevirtual.com](http://everythingshouldbevirtual.com)

<a href="https://www.buymeacoffee.com/mrlesmithjr" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-role](https://github.com/mrlesmithjr/cookiecutter-ansible-role) as a template.
