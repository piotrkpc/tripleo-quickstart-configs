# tripleo-quickstart-configs

Example  cmd:

```
OOOQ_CONFIG=./config/general_config/minimal-ceph.yml
OOOQ_NODES=./config/nodes/1ctlr_2comp_1ceph.yml
./quickstart.sh -p quickstart-extras.yml \
    --release master-tripleo-ci \
    --config $OOOQ_CONFIG \
    --nodes $OOOQ_NODES \
    --clean \
    --bootstrap \
    --teardown all \
    127.0.0.2
```
