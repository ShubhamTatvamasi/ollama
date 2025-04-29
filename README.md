# ollama

Setup ollama locally

https://ollama.com/download

https://ollama.com/library/deepseek-r1

Download deepseek model and run it locally:
```bash
ollama run deepseek-r1
```

Exit deepseek model:
```bash
/bye
```

Start Open Web UI localy for getting access to the dashboard:
```bash
docker run -d \
  -p 3000:8080 \
  --add-host=host.docker.internal:host-gateway \
  -v open-webui:/app/backend/data \
  --name open-webui \
  --restart always \
  ghcr.io/open-webui/open-webui:main
```

http://localhost:3000




