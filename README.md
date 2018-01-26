# oracle-java

This role installs the Oracle Java distribution.
The license is automatically accepted.

## Requirements

Ubuntu

## Role Variables

| Name                  | Default/Required | Description                             |
|-----------------------|:----------------:|-----------------------------------------|
| `oracle_java_version` | `8`              | Major version number of Java to install |

## Example Playbook

```yml
- hosts: java-hosts
  roles:
  - oracle-java
    oracle_java_version: 7
```

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

## Author Information

- [Janne Heß](https://github.com/dasJ)
