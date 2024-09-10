
# WordPress Theme/Plugin Dev Setup

A development environment for WordPress Themes and Plugins. Use Docker to spin up a WordPress Environment with access to the wp-content folder. 

## Installation

Run the environment with docker compose.

```bash
  docker-compose up
```
    
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file. You can also copy the env.example file.

`CONTAINER_NAME`

`DATABASE_NAME`

`DATABASE_USER`

`DATABASE_PASSWORD`

`DATABASE_ROOT_PASSWORD`

`PMA_USER`

`PMA_PASSWORD`
