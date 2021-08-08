# Power Control
```
ansible -i inventory/pi-cluster -m include_role -a "name=power_control" -e 'shutdown=true' -b model4
```
