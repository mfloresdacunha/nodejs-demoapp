## Instruções

Para este projeto, não estamos fazendo o build da imagem diretamente, mas sim usando uma imagem pronta, cujo endereço encontra-se no README.md do projeto original.

Para rodar a imagem, executar:

```bash
podman run --rm -it -p 3000:3000 ghcr.io/benc-uk/nodejs-demoapp:latest
```

