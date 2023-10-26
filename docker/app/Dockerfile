FROM jupyter/scipy-notebook

# Change uid for process user to avoid permission issues to 1000 (same as host user, normally)
RUN usermod -u 1000 www-data && groupmod -g 1000 www-data
