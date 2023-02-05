# Provisions vanilla k8s with calico and istio

- Edit `hosts` to include your desired targets.
- Run it as such:

```
$ ansible-playbook -i hosts playbook.yaml
```

Tested on a vanilla debian11 VM. 

`Assumes user can sudo without a password.`
