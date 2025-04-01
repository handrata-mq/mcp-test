# MCP-TEST

Simple test of MCP Server.

This sample uses mcp-server-sqlite

Full list of MCP servers can be found here: https://github.com/modelcontextprotocol/servers

## Pre-Requisites

You need to install python UV

https://docs.astral.sh/uv/getting-started/installation/

## Demo

There is empty demo.db (Sqlite3) in this repo.

With .cursor/mcp.json config, it enables cursor to have sqlite3 capabilities.

Now you can ask cursor to modify the sqlite3 db such as:
- List tables in my demo.db.
- Populate 100 sample records for actor and movie table.
- Create new table called studios and add default columns for movie studios.

By utilising other MCP servers, you can even manage your remote database, kubernetes, aws, etc.

