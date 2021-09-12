# Cliboa development environment

this repository is [cliboa](https://github.com/BrainPad/cliboa) development environment.

Procedure

1. Clone cliboa in this directory
2. `docker-compose up -d`
3. `docker-compos exec cliboa bash` Enter the development container
4. Execute cliboa/tools/script/init_dev.py
5. Install package by generated Pipfile
6. Follow the cliboa documentation to start and develop your project.
7. If your PYTHONPATH is not working, you can directly install ./cliboa in pipenv shell.
