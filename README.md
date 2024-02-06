# Nginx docker container with modules
Following modules are enabled
- lua
- cachepurger (https://github.com/FRiCKLE/ngx_cache_purge)

Source: https://github.com/nginxinc/docker-nginx/tree/master/modules

Note: There is no Dockerfile here if you wonder. Dockerfile will be downloaded via curl from CI. Check .github/workflows/CI.yml file. You will get the idea 
