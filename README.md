# mini-local-aws-stack

## Project structure

```
mini-local-aws-stack/
│
├─ compose.yml
├─ .env
├─ .gitignore
└─ docker/
   └─ volumes/
```

## 🔑 Access points after `docker compose up -d`

* **MinIO Web Console** → `http://localhost:9001` (Login: `minioadmin / minioadmin`)
* **MinIO S3 API** → `http://localhost:9000`
* **DynamoDB Local** → `http://localhost:8000`
* **LocalStack Edge API** → `http://localhost:4566`
* **HashiCorp Vault** → `http://localhost:8200`

---

* **NoSQL Workbench (AWS)**: Official, robust GUI, works with DynamoDB Local.





