## cli store

Access to Petstore orders

### Synopsis

Access to Petstore orders

```
cli store [flags]
```

### Options

```
  -h, --help   help for store
```

### Options inherited from parent commands

```
      --agent-mode             Enable structured errors and default TOON output for AI coding agents. Automatically enabled when a known agent environment is detected (CLAUDE_CODE, CURSOR_AGENT, etc.). Use --agent-mode=false to disable.
      --api-key string         API Key
      --color string           Control colored output: auto (color when output is a TTY), always, or never. Respects NO_COLOR and FORCE_COLOR env vars. (default "auto")
  -d, --debug                  Log request and response diagnostics to stderr
      --dry-run                Preview the request that would be sent without executing it (output to stderr)
      --environment string     Server template variable: environment
  -H, --header stringArray     Set a custom HTTP request header (format: "Key: Value"). Can be specified multiple times.
      --include-headers        Include HTTP response headers in the output
  -q, --jq string              Filter and transform output using a jq expression (e.g., '.name', '.items[] | .id')
      --no-interactive         Disable all interactive features (auto-prompting, explorer auto-launch, TUI forms)
  -o, --output-format string   Specify the output format. Options: pretty, json, yaml, table, toon. (default "pretty")
      --server string          Select a server by index (for indexed servers) or name (for named servers)
      --server-url string      Override the default server URL
      --timeout string         HTTP request timeout (e.g., 30s, 5m, 100ms)
      --usage                  Print the CLI Usage schema in KDL format
```

### SEE ALSO

* [cli](cli.md)	 - Petstore - OpenAPI 3
* [cli store delete-order](cli_store_delete-order.md)	 - Delete purchase order by ID
* [cli store get-inventory](cli_store_get-inventory.md)	 - Returns pet inventories by status
* [cli store get-order-by-id](cli_store_get-order-by-id.md)	 - Find purchase order by ID
* [cli store place-order](cli_store_place-order.md)	 - Place an order for a pet
