role_lighthouse 1.0.1


dependencies:
- git
- git repository ``` https://github.com/VKCOM/lighthouse.git```
- nginx

## example playbook:
```
- name: install lighthouse
  hosts:
    - example_host
  become: true
  roles:
    - role: lighthouse``` 