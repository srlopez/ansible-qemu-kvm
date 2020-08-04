# ansible-qemu-kvm

para ejecutar todo desplegando las vm
$ sudo ansible-playbook local.yml 

para borrar las maquinas
$ sudo ansible-playbook local.yml --tags "never"


inspirado de Blog https://nbailey.ca/post/kvm-ansible-automation/