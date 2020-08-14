# terraform-vsphere-kubespray

1- Указываем необходимые параметры в terraform.tvars
```vsphere_user = ""
vsphere_password = ""
vsphere_server = ""
vsphere_datacenter = ""
vsphere_datastore = ""
vm_cluster = ""
vm_network = ""
vm_template_name = ""
```
2- Инициализируем terraform
```terraform init```
3- Запускаем скрипт
```terraform apply```
