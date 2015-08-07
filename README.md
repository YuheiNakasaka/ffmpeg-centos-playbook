# ffmpeg centos playbook for vagrant

This is the ansible playbook to install FFmpeg.

I tested in CentOS 6.x using vagrant and virtualbox.

# USAGE

Installing vagrant and virtualbox is required.

1. vagrant up

2. Edit hosts and rewrite your-host and enter ↓

```
ansible-playbook -i hosts movie-converter.yml -u vagrant --private-key=/Users/username/vagrant/hoge/.vagrant/machines/default/virtualbox/private_key
```