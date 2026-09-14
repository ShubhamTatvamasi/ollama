# ollama

Add helm repo:
```bash
helm repo add ollama https://otwld.github.io/ollama-helm/
```

Install ollama:
```bash
helm install ollama ollama/ollama \
  --namespace ollama \
  --create-namespace
```

---

Setup ollama locally

https://ollama.com/download


Models: https://ollama.com/search

https://ollama.com/library/deepseek-r1

Download deepseek model and run it locally:
```bash
ollama run deepseek-r1
```

Exit deepseek model:
```bash
/bye
```

---

List models:
```bash
ollama list
```

Pull the latest `deepseek-r1` model:
```bash
ollama pull deepseek-r1
```

Delete the image:
```bash
ollama rm qwen3-coder:latest
```

List running models:
```bash
ollama ps
```


