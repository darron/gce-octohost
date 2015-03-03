gce-octohost
=============

Some ansible playbooks I have been using to setup a cluster of octohosts on Google Cloud.

```
ansible-playbook {consul|mysql|registry|service|ufw}.yml
```

Most configuration values are done from the environment:

`cp envrc .envrc`

Update the values in the .envrc and you should be good to go.

```
ansible-playbook ufw.yml
ansible-playbook consul.yml
ansible-playbook mysql.yml
```

I haven't gotten it all to work yet - so much of this may be broken.
