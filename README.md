# minimal-asgi-app-demo 

The minimal asgi app dockerize with `starlette`, `hypercorn` and `uvloop`
* use docker multi-stage build
* python version: `3.12.5`

### Using packages
* starlette
* hypercorn
* uvloop

### Export `requirements.txt`
```bash
uv pip compile pyproject.toml -o requirements.txt
```

