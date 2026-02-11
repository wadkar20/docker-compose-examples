# Docker Compose Examples

Ready-to-use Docker Compose configurations.

## Stack Included
- Nginx web server
- MySQL database
- Redis cache

## Usage
```bash
# Start all services
docker-compose up -d

# View logs
docker-compose logs -f

# Stop services
docker-compose down

# Remove volumes
docker-compose down -v
```

## Configuration
Edit `docker-compose.yml` to customize:
- Ports
- Environment variables
- Volume mounts

## Author
Sakshi Wadkar

