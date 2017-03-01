# get-instances-ips-of-asg

Get IPs of the instances of an auto scaling group and return them in a list inside the fact asg_instances

## Role Variables

* `region`   : Region to launch the ec2 instance to create the new AMI
* `asg.name` : Auto Scaling Group name

## Example playbook

```yaml
- hosts        : localhost
  connection   : local
  gather_facts : no
  roles:
    - get-instances-ips-of-asg
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigma)
