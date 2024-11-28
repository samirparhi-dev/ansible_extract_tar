# Ansible Role to extract tar

usage:
- create a `requirements.txt` in you role 
- Add it to requirements:
```
---
roles:
  - name: check_folders
    src: https://github.com/samirparhi-dev/ansible_extract_tar.git
    scm: git
    version: main
```

add below content in `meta/main.yml`
```
---
dependencies:
  - name: <<Name of the Role>>
```

It should be available now for consuption