# Página local en ngrok (Puerto 2828)

Archivos:
- `index.html`: Página web simple.
- `server.js`: Servidor HTTP Node.js que sirve `index.html` en el puerto `2828`.

## Ejecución

1. Abre una terminal en esta carpeta.
2. Ejecuta el servidor:

```bash
node server.js
```

3. En otra terminal, inicia ngrok:

```bash
ngrok http 2828
```

4. ngrok mostrará una URL pública. Usa esa URL para abrir la página desde Internet.

## Notas

- Necesitas tener instalado Node.js.
- También necesitas tener `ngrok` instalado y configurado.
