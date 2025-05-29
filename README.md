### How to setup the environment

```curl -LsSf https://astral.sh/uv/install.sh | sh```

```
# Create virtual environment and activate it
uv venv
source .venv/bin/activate

# Install dependencies
uv add "mcp[cli]" httpx
```

### to run the mcp inspector
```
mcp dev weather.py
```

For more detail documentation please visit
https://modelcontextprotocol.io/
