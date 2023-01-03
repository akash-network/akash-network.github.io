## provider-services query gov tally

Get the tally of a proposal vote

### Synopsis

Query tally of votes on a proposal. You can find
the proposal-id by running "<appd> query gov proposals".

Example:
$ <appd> query gov tally 1

```
provider-services query gov tally [proposal-id] [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for tally
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query gov](provider-services_query_gov.md)	 - Querying commands for the governance module

###### Auto generated by spf13/cobra on 5-Dec-2022