# Neo4j on RAM Disk

Run a temporary Neo4j graph on a RAM disk by doing the following:

1. Check out this repository!
2. Ensure the symlink *ramdisk* is pointing to a mounted RAM disk.
3. `./neoram start` (Neo4j 2.1.2 will be downloaded)

When finished, run `./neoram stop` and the database will be flushed when the
server stops.

To load and save database snapshots, store a graph.db directory in the `var`
folder under any name. A snapshot called `snapshot1` can be loading using
`./neoram start snapshot1`. To save the current database as a snapshot use
`./neoram stop snapshot1`.

To select and download an alternative version, use `./neoram use x.y.z` where
`x.y.z` is a valid Neo4j server version.

