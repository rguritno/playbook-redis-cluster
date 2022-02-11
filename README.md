# Readme First

This Playbook only for purpose create redis cluster for active passive and failover using sentinel. This playbook also can create multiple redis cluster in server existing

# Run Playbook

ansible-Playbook -i [inventory file] Playbook/playbook-configure-redis-sentinel.yml -e "nodes=sentinel0" -t slave -vv

Notes:

There are 3 Tags for Master, Slave, and Sentinel Redis. 

Run playbook using environtment in inventory
