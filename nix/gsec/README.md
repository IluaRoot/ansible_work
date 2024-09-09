# Autoinstall and configure GSecTLS proxy 

This playbook is made for autoinstall nces GSecTLS proxy server.
All info was taken from oficial nces manual.

Just create package directory in gsec and put .deb package into it.
Or you can delete 17 string in *gsec_server_install.yaml* file and uncomment 18 string

```yaml
#        deb: "{{ deb_url }}"
```

put your address in *vars* section of playbook. Don't forger to change inventory file.