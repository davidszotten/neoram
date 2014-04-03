# Neo4j on RAM Disk

Run a temporary Neo4j graph on a RAM disk by doing the following:

1. Check out this repository!
2. Ensure the symlink *ramdisk* is pointing to a mounted RAM disk.
3. `./neoram start`

When finished, run `./neoram stop` and the database will be flushed when the
server stops.
