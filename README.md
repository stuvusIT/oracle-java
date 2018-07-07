# oracle-java

This role installs the Oracle Java distribution including the unlimited strength policy.
The license is automatically accepted.
Additionally, you can add certificate files to the cacerts keystore

## Requirements

Debian or Ubuntu

## Role Variables

| Name                  | Default/Required | Description                                               |
|-----------------------|:----------------:|-----------------------------------------------------------|
| `oracle_java_version` | `8`              | Major version number of Java to install                   |
| `oracle_java_cacerts` | `[]`             | List of paths to certificates to import into the keystore |

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
