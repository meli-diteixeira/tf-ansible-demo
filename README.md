# tf-ansible-demo

`Ansible` has a module for Terraform, which we can use in order to provision our resources. On the other hand, although Terraform does not have an explicit provisioner for Ansible (as it has for `Chef` or `Salt`), we can make use of the `remote-exec` & `local-exec` provisioners to invoke our `Ansible` scripts at the time of server creation.

![img architecture](./ansible/files/img/architecture.png)