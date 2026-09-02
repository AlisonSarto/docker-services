3306 -> warehouse
8000 -> appsmith
5678 -> n8n
3000 -> metabase

for dir in */; do (cd "$dir" && docker compose up --build -d); done

ip docker: 172.17.0.1

