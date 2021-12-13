# Rundeck PagerDuty Assignment

### JOBS

1. Gets Rundeck PID and echo it.
```bash
[rundeck@rundeck jobs]$ rundeck_pid.yaml
```


2. Show IP addresses and hostname for remote machine (tag: name=centos)
```bash
[rundeck@rundeck jobs]$ rundeck_ip_hostname.yaml
```

### PLUGINS
1- Make a YAML Rundeck Plugin that just executes a "hello world" (or simple echo)

Code:
```bash
[rundeck@rundeck plugins]$ ls hello-world-plugin
contents  plugin.yaml
```
Plugin file:
```bash
[rundeck@rundeck plugins]$ ls *.zip
hello-world-plugin.zip
```

### NODES

Nodes YAML definition

```bash
[rundeck@rundeck nodes]$ nodes.yaml
```