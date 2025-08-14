Add the following installations steps:
# Installation Steps

To install the `addnumbers` MCP server, run the following command:

```json
{
  "mcpServers": {
    "addnumbers": {
      "command": "/opt/anaconda3/bin/uvx",
      "args": [
        "--from",
        "git+https://github.com/KavehMoss/mcp-server-deepdive-deployment.git",
        "mcp-server"
      ]
    }
  }
}
```

This will fetch and set up the `mcp-server` from the specified GitHub repository.