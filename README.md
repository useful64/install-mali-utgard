# install-mali-utgard

```
git clone https://github.com/useful64/install-mali-utgard.git
cd install-mali-utgard
```

`vim inventory.ini` <-- change XXX.XXX.XXX.XXX

```
ansible-playbook -i inventory.ini -l rock64 -t install-mali-utgard rock64.yml
```
