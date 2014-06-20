
# SphinxPHP Command-line

## Usage

```
bin/console sphinxphp:XXX
```

## Commands Available

### sphinxphp:start
Starts the Sphinx daemon.

### sphinxphp:stop
Stops the Sphinx daemon.

### sphinxphp:indexer-all
Runs the Sphinx indexer and reindexes all. (indexer --all)

### sphinxphp:indexer-rotate <index_name>
Runs the Sphinx indexer rotating the provided index. (indexer --rotate)

### sphinxphp:sphinxql:warmup <sphinxql_index_name>
Warms up the SphinxQL search table for the provided index. (SphinxPHP::parse)


