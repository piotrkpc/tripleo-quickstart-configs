# tripleo-quickstart-configs

Example  cmd:

```
OOOQ_CONFIG=./tripleo-quickstart-configs/config/general_config/minimal-ceph.yml
OOOQ_NODES=./tripleo-quickstart-configs/config/nodes/1ctlr_2comp_1ceph.yml
./quickstart.sh -p quickstart-extras.yml \
    --release master-tripleo-ci \
    --config $OOOQ_CONFIG \
    --nodes $OOOQ_NODES \
    --clean \
    --bootstrap \
    --teardown all \
    --no-clone \
    --tags all \
    -e undercloud_undercloud_ntp_servers=clock.redhat.com \
    127.0.0.2
```
