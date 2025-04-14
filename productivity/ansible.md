[Example repo](https://github.com/ThePrimeagen/ansible/tree/0e9ec7e31d5bf5c721267a8dccaeea3c1667f3ca)

## Anatomy

```
hosts: localhost
become: true
pre_tasks: ...
vars: ...
tasks: ...
```

### Task
```
- name: string
  _SOME_ACTION_
  tags:
   - list
   - of
   - tags
```