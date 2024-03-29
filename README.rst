|Riptide|
=========

.. |Riptide| image:: https://riptide-docs.readthedocs.io/en/latest/_images/logo.png
    :alt: Riptide

.. class:: center

    ======================  ===================  ===================  ===================
    *Main packages:*        lib_                 proxy_               cli_
    *Container-Backends:*   engine_docker_
    *Database Drivers:*     db_mysql_            **db_mongo**
    *Plugins:*              php_xdebug_
    *Related Projects:*     configcrunch_
    *More:*                 docs_                repo_                docker_images_
    ======================  ===================  ===================  ===================

.. _lib:            https://github.com/theCapypara/riptide-lib
.. _cli:            https://github.com/theCapypara/riptide-cli
.. _proxy:          https://github.com/theCapypara/riptide-proxy
.. _configcrunch:   https://github.com/theCapypara/configcrunch
.. _engine_docker:  https://github.com/theCapypara/riptide-engine-docker
.. _db_mysql:       https://github.com/theCapypara/riptide-db-mysql
.. _db_mongo:       https://github.com/theCapypara/riptide-db-mongo
.. _docs:           https://github.com/theCapypara/riptide-docs
.. _repo:           https://github.com/theCapypara/riptide-repo
.. _docker_images:  https://github.com/theCapypara/riptide-docker-images
.. _php_xdebug:     https://github.com/theCapypara/riptide-plugin-php-xdebug
.. _k8s_client:     https://github.com/theCapypara/riptide-k8s-client
.. _k8s_controller: https://github.com/theCapypara/riptide-k8s-controller

|build| |docs| |pypi-version| |pypi-downloads| |pypi-license| |pypi-pyversions|

.. |build| image:: https://img.shields.io/github/actions/workflow/status/theCapypara/riptide-db-mongo/build.yml
    :target: https://github.com/theCapypara/riptide-db-mongo/actions
    :alt: Build Status

.. |docs| image:: https://readthedocs.org/projects/riptide-docs/badge/?version=latest
    :target: https://riptide-docs.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. |pypi-version| image:: https://img.shields.io/pypi/v/riptide-db-mongo
    :target: https://pypi.org/project/riptide-db-mongo/
    :alt: Version

.. |pypi-downloads| image:: https://img.shields.io/pypi/dm/riptide-db-mongo
    :target: https://pypi.org/project/riptide-db-mongo/
    :alt: Downloads

.. |pypi-license| image:: https://img.shields.io/pypi/l/riptide-db-mongo
    :alt: License (MIT)

.. |pypi-pyversions| image:: https://img.shields.io/pypi/pyversions/riptide-db-mongo
    :alt: Supported Python versions

Riptide is a set of tools to manage development environments for web applications.
It's using container virtualization tools, such as `Docker <https://www.docker.com/>`_
to run all services needed for a project.

It's goal is to be easy to use by developers.
Riptide abstracts the virtualization in such a way that the environment behaves exactly
as if you were running it natively, without the need to install any other requirements
the project may have.

Database-Driver: MongoDB
------------------------

This repository implements the database driver interface of the Riptide library for use
with MongoDB-compatible databases. This allows users to manage MongoDB databases within
Riptide projects via the Riptide CLI.

Documentation
-------------

The complete documentation for Riptide can be found at `Read the Docs <https://riptide-docs.readthedocs.io/en/latest/>`_.
