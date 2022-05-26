Install this into the same namespace as the etcd you're looking to peek into.

oc create -f etcdkeeper.yaml

You may need to look up the in-cluster ip of the etcd pod that you're looking to inspect and enter that in the etcdkeeper webui

