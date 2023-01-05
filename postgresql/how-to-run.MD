# Create Container and run container
docker compose up -d


# Check if container is running
docker compose ps

# Check logs (If needed)
docker compose logs -f

# Enter postgre console
docker compose exec -it postgres-example psql -U postgres