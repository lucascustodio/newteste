## cli user create-users-with-list-input

Creates list of users with given input array

### Synopsis

Creates list of users with given input array

```
cli user create-users-with-list-input [flags]
```

### Examples

```
  cli user create-users-with-list-input --request '[{"id":10,"username":"theUser","firstName":"John","lastName":"James","email":"john@email.com","password":"12345","phone":"12345","userStatus":1}]'
```

### Options

```
  -h, --help             help for create-users-with-list-input
      --request string   Request body as JSON. Can also be provided via stdin.
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

* [cli user](cli_user.md)	 - Operations about user
