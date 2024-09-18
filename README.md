# azure-vpn

Create VM in Azure and configure OpenVPN for personal use

custom_data can't accept file namitvely now:

```
custom_data_config: cloud-init.txt
```

leads to

```
sudo cat /var/lib/cloud/instances/d1d8ffc0-c2d3-614f-935f-a1128e5aef15/user-data.txt
cloud-init.txt
```
