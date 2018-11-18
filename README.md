# ansible-demo
Demo of installing Elasticsearch/Kibana using Ansible

# Example of how to run the Ansible script
```sh
ansible-playbook -i ./hosts site.yml --tags "elasticsearch,kibana"
```

```sh
ansible-playbook -i ./hosts site.yml --tags "elasticsearch"
```