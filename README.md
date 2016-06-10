# Ansible Role: Oracle Java

Installs the Oracle Java JDK using a package provided by http://www.webupd8.org on Debian/Ubuntu Linux servers.

## Installation

You can either use ansible-galaxy to install this role:

    ansible-galaxy install deveth0.oracle_java

Or checkout this git-repository to your roles directory:

    git clone https://github.com/deveth0/ansible-oracle-java.git deveth0.oracle_java


## Role Variables

Available variables are listed below, along with the default values:

You can configure which java-version to use:

    oracle_java_version: 8

By default the Java environment variables are set:

    oracle_java_set_default: True


## Dependencies
 
No dependencies required

## Example Playbook

    - hosts: foo
      roles:
        - role: deveth0.oracle_java
          oracle_java_version: 7
          

## License

Apache License 2.0

## Author Information

This Role was created by [Alex Muthmann](http://dev-eth0.de).
