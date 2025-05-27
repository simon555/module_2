# Filesystem MCP Agent

This folder demonstrates how to use an agent that can read and reason over files in the `sample_files` directory.

## Prerequisites
- Python 3.10+
- Node.js and npx installed (`npm install -g npx` if needed)
- Project Python dependencies installed

## Quick Start

**You do NOT need to start the MCP Filesystem server manually.**  
The server will be launched automatically by the Python script.

1. **Run the agent interactively**

In your terminal, execute:

```bash
python main.py
```

You can then chat with the agent via the command line. Type `/quit` to exit.

## Example files
- `favorite_books.txt`
- `favorite_songs.txt`
- `favorite_cities.txt`
- `poem.txt`

## Notes
- The MCP Filesystem server is started automatically as a subprocess by the script.
- For more information about the MCP Filesystem server, see:  
  https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem