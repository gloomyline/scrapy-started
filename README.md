# scrapy_started
Get started on Scrapy, a crawler framework powered by python.

## How to use virtualenv
1. install
  ```
  pip3 install virtualenv
  ```
2. create project directory
  ```
  mkdir myproject && cd myproject
  ```
3. create a isolated python runtime environment, named it `venv`
  ```
  # --no-site-packages means do not copy third-party packages from system python environment
  virtualenv --no-site-packages venv
  ```
4. activate the clean local env created before
  ```
  source venv/bin/activate
  ```
5. deactivate
  ```
  deactivate
  ```
