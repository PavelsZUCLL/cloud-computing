Om de applicatie vanaf nul te laten draaien, gebruikt u deze commando's:

```bash
git clone https://github.com/PavelsZUCLL/cloud-computing.git
cd cloud-computing
cp .env.example .env
docker compose up -d --build
docker compose ps
curl http://localhost:8000/health
docker compose down
```