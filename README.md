# warehouse-fastapi

python3 -m venv .warehouse-fastapi-env
pip install -r requirements.txt

docker run -d --name redis-stack-server -p 6379:6379 redis/redis-stack-server:latest
