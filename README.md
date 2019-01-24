# langerma-ansible-java

## Example Playbook

```yaml
- hosts: all
  vars:
    java_version: 11
    java_install_tar: "https://github.com/AdoptOpenJDK/openjdk11-binaries/releases/download/jdk-11.0.2%2B7/OpenJDK11U-jdk_x64_linux_hotspot_11.0.2_7.tar.gz"
    java_install_dir: "/opt/java"

  roles:
    - role: java
```
