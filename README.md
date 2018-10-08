# ansible-elasticsearch

<!-- TOC -->

- [ansible-elasticsearch](#ansible-elasticsearch)
  - [Requirements](#requirements)
  - [Role Variables](#role-variables)
  - [Dependencies](#dependencies)
  - [Example Playbook](#example-playbook)
  - [Molecule Testing](#molecule-testing)
  - [License](#license)
  - [Author Information](#author-information)

<!-- /TOC -->

An [Ansible](https://www.ansible.com) role to install/configure [Elasticsearch](https://www.elastic.co/products/elasticsearch)

> NOTE: This role has been completely rewritten and replaces my original
> `ansible-elasticsearch` role which has been renamed to [ansible-elasticsearch-old](https://github.com/mrlesmithjr/ansible-elasticsearch-old.git).
> I decided to rewrite this role as the original had a lot of residuals from years
> of different usages. The original will remain for historical purposes.

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)

If you would like to add additional Elasticsearch parameters you only need to add
them to the `elasticsearch_configuration:` section. These variables are added as
YAML using the template. So there is no need to reconfigure the template either.

## Dependencies

None

## Example Playbook

[playbook.yml](playbook.yml)

## Molecule Testing

If you have [Molecule](https://github.com/metacloud/molecule) installed, you
can easily spin up a 3-node cluster for testing.

Simply run the following to spin up:

```bash
molecule converge
```

## License

MIT

## Author Information

Larry Smith Jr.

- [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
