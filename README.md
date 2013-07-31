ext_vars
========

```
PLAY [localhost] **************************************************************

GATHERING FACTS ***************************************************************
ok: [localhost]

TASK: [debug msg={{one_var}}] *************************************************
ok: [localhost] => {"msg": "{{one_var}}"}

TASK: [debug msg={{other_var}}] ***********************************************
ok: [localhost] => {"msg": "{{other_var}}"}

PLAY [all] ********************************************************************
localhost: importing /Users/victorcoder/Code/ext_vars/external_ok.yml

PLAY RECAP ********************************************************************
localhost                  : ok=3    changed=0    unreachable=0    failed=0

ansible-playbook --version
ansible-playbook 1.3 (devel 8cc13590b4) last updated 2013/07/30 21:41:53 (GMT +200)
```

