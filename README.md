Para compilar:

```
wasm-pack build --target web --out-name wasm --out-dir ./static
```

Depois servir com seu servidor favorito:

```
cd static && python -mhttp.server
```
