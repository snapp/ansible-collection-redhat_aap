Ⓐ Ansible Collection: snapp.redhat_aap
======================================

|ansible-lint| |ansible-test| |antsibull-docs-lint|

This Ansible Collection can be used to install and manage Red Hat's Ansible Automation Platform (AAP).

Using this collection
---------------------

..
    TODO: Include some quick examples that cover the most common use cases for your collection content. It can include the following examples of installation and upgrade:

Installing the Collection from Ansible Galaxy
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Before using this collection, you need to install it with the Ansible Galaxy command-line tool:

.. code-block:: console

    ansible-galaxy collection install snapp.redhat_aap

You can also include it in a ``requirements.yml`` file and install it with ``ansible-galaxy collection install -r requirements.yml``, using the format:

.. code-block:: yaml

    ---
    collections:
    - name: snapp.redhat_aap

Note that if you install the collection from Ansible Galaxy, it will not be upgraded automatically when you upgrade the ``ansible`` package. To upgrade the collection to the latest available version, run the following command:

.. code-block:: console

    ansible-galaxy collection install snapp.redhat_aap --upgrade

You can also install a specific version of the collection, for example, if you need to downgrade when something is broken in the latest version (please report an issue in this repository). Use the following syntax to install version ``0.1.0``:

.. code-block:: console

    ansible-galaxy collection install snapp.redhat_aap:==0.1.0

See `Ansible Using collections`_ for more details.

Release Notes
-------------

See the `changelog`_.

License
-------

GNU General Public License v3.0 or later.

See `LICENSE`_ to see the full text.

Author Information
------------------

snapp@redhat.com

.. _Ansible Using collections: https://docs.ansible.com/ansible/devel/user_guide/collections_using.html
.. _changelog: https://github.com/snapp/ansible-collection-redhat_aap/tree/main/CHANGELOG.rst
.. _LICENSE: https://www.gnu.org/licenses/gpl-3.0.txt

.. |ansible-lint| image:: https://github.com/snapp/ansible-collection-redhat_aap/actions/workflows/ansible-lint.yml/badge.svg
   :target: https://github.com/snapp/ansible-collection-redhat_aap/actions/workflows/ansible-lint.yml
.. |ansible-test| image:: https://github.com/snapp/ansible-collection-redhat_aap/actions/workflows/ansible-test.yml/badge.svg
   :target: https://github.com/snapp/ansible-collection-redhat_aap/actions/workflows/ansible-test.yml
.. |antsibull-docs-lint| image:: https://github.com/snapp/ansible-collection-redhat_aap/actions/workflows/antsibull-docs-lint.yml/badge.svg
   :target: https://github.com/snapp/ansible-collection-redhat_aap/actions/workflows/antsibull-docs-lint.yml
