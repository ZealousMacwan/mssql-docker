# MSSQL Server(Dev) as Docker container

## How to use?
1. Make sure your Docker is up and running. <br/>
2. Clone this repository <br/>
3. Update docker-compose.yml file <br/>
  - Update SA_PASSWORD to your preferred strong password (Recommended)
  - Update 1435 port in "1435:1433" to be exposed on your system (Optional)
  - Update CPU and Memort limit (Optional)
### Run below command in repository path
```
sh deploy.sh
```
