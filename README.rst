.. -*- mode: rst -*-

|Travis|_ |GHActions|_ |Codecov|_ |CircleCI|_ |ReadTheDocs|_


[![Build Status](https://github.com/PythonOT/POT/workflows/build/badge.svg)](https://github.com/PythonOT/POT/actions)

.. |Travis| image:: https://travis-ci.org/mne-tools/mne-project-template.svg?branch=master
.. _Travis: https://travis-ci.org/mne-tools/mne-project-template

.. |GHActions| image:: https://github.com/mne-tools/mne-project-template/workflows/build/badge.svg
.. _GHActions: https://github.com/mne-tools/mne-project-template/actions

.. |Codecov| image:: https://codecov.io/gh/mne-tools/mne-project-template/branch/master/graph/badge.svg
.. _Codecov: https://codecov.io/gh/mne-tools/mne-project-template

.. |CircleCI| image:: https://circleci.com/gh/mne-tools/mne-project-template.svg?style=svg
.. _CircleCI: https://circleci.com/gh/mne-tools/mne-project-template/tree/master

.. |ReadTheDocs| image:: https://readthedocs.org/projects/mne-project-template/badge/?version=latest
.. _ReadTheDocs: https://mne-project-template.readthedocs.io/en/latest/?badge=latest

mne-project-template - A template for mne-python compatible extensions
======================================================================

.. _mne-python: https://martinos.org/mne/stable/index.html

**mne-project-template** is a template project for mne-python_ compatible
extensions.

*Thank you for cleanly contributing to the mne-python ecosystem!*

.. _documentation: https://mne-project-template.readthedocs.io/en/latest/quick_start.html

Refer to the documentation_ to modify the template for your own mne-python
extension or follow this quick reference::

    $ git clone https://github.com/mne-tools/mne-project-template.git mne-foo
    $ cd mne-foo
    $ # update mne_project_template_bootstrap.sh
    $ bash mne_project_template_bootstrap.sh
    $ rm mne_project_template_bootstrap.sh
    $ rm -rf .git
    $ git init && git add . && git commit -m 'Initial commit'
    $ git remote add origin https://github.com/your_remote/mne-foo.git
    $ git push origin master
    $ # Activate all CIs

Notice that appveyor badge image needs to be updated manually. Go where ``_AppVeyor:`` pints
in the resulting `README.rst` after bootstraping and substitute `4qrnsuohh5g53i5u` with
the relevant information from `settings` -> `badges` in appveyor's website of your project.
