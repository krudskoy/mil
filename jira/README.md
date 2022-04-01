Jira compose file

Requirements:
 * docker-compose

Run:
1. Download docker-compose file
2. Update POSTGRES_PASSWORD and ATL_JDBC_PASSWORD values in docker-compose file.(POSTGRES_PASSWORD=ATL_JDBC_PASSWORD) 
2. Run "docker-compose up -d" inside the directory where docker-compose file is located.

Backup:
1. Volumes backup and restore: https://docs.docker.com/storage/volumes/#backup-restore-or-migrate-data-volumes