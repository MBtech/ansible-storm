# ansible-storm
An ansible way to deploy Apache Storm

Edit the hosts_sample to add the hostnames or IP of your nodes
Setup and run Storm + zookeeper using

`$ cd roles`

`$ ansible-playbook -i ../hosts_sample main.yaml`

This will download storm and zookeeper on the nodes in the directory `~/ansible-test/`

Note: I will fix some of the hardcoded paths to let user specify their own choices.
