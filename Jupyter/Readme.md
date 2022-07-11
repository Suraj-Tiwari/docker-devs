# Jupyter Minimal Notebook

> image is configured for arm by default, if your change tag in `Dockerfile` for other arch

- This image also contains nodejs kernel
- Use `password` for notebook authentication, you can update that in `docker-compose.yml`
- To change user update `NB` in docker-compose file, make sure to update path in volumes `/home/{user}/work`
  and `/home/{user}/.jupyter` and working_dir `/home/{user}/work`
- access on http://localhost:8888
