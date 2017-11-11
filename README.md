Ansible-ELK
=========

Ansible playbook to install ELK stack

Requirements
------------

CentOS/Redhat 7

How to start
------------

Simply type 
```ansible-playbook ELKInstall.yaml```

How to review that all is working
------------
For Elasticsearch (use 9200 port)

```curl http://localhost:9200```

For Kibana

```curl http://localhost:5601```

Author
------------
Andrii Striletskyi
