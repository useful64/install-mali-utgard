# install-mali-utgard

## Ansbile role for install libmali and compile mali kernel driver 

### Instructions

```
git clone https://github.com/useful64/install-mali-utgard.git
cd install-mali-utgard
```

`vim inventory.ini` <-- change XXX.XXX.XXX.XXX with board IP

```
ansible-playbook -i inventory.ini -l rock64 -t install-mali-utgard rock64.yml
```
### Notes

This is tested with armbian (focal) on rock64
