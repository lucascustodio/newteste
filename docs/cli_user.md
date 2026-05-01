## cli user

Operations about user

### Synopsis

Operations about user

```
cli user [flags]
```

### Options

```
  -h, --help   help for user
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
* [cli user create](cli_user_create.md)	 - Create user
* [cli user create-users-with-list-input](cli_user_create-users-with-list-input.md)	 - Creates list of users with given input array
* [cli user delete](cli_user_delete.md)	 - Delete user
* [cli user get-user-by-name](cli_user_get-user-by-name.md)	 - Get user by user name
* [cli user login](cli_user_login.md)	 - Logs user into the system
* [cli user logout](cli_user_logout.md)	 - Logs out current logged in user session
* [cli user update](cli_user_update.md)	 - Update user
