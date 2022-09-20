# Wordpress - Docker template

This is a Wordpress system template built on top of Docker.

## Installation

  - Install Docker on the computer. Refer to the installation instructions on the Docker homepage
  - Run command to get started

```bash
docker-compose up
```

## Developing

- For creating a new project
  + Checkout each project by branch
  ```bash
  git checkout -b [institution]/[project_name]
  ```

  + Create git submodule in a directory under `wp-content/themes/...`
  ```bash
  git submodule add [repository] wp-content/themes/[project_folder]
  ```

- For cloning project
  + Clone submodule
  ```bash
  git submodule update --init
  ```
