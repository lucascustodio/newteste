## cli pet update

Update an existing pet

### Synopsis

Update an existing pet by Id

```
cli pet update [flags]
```

### Examples

```
  cli pet update --name doggie --photo-urls '["<value 1>"]'
```

### Options

```
      --body string              Request body as JSON (alternative to individual flags). Can also be provided via stdin.
  -c, --category string          JSON object
  -h, --help                     help for update
  -i, --id int                   integer value
  -n, --name string              [required]
  -p, --photo-urls stringArray   [required]
  -s, --status string            pet status in the store (options: available, pending, sold)
  -t, --tags string              list of values
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

* [cli pet](cli_pet.md)	 - Everything about your Pets
