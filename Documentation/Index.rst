.. include:: Includes.txt


.. _start:

======================
File Abstraction Layer
======================

.. warning::

    This document has been merged into :ref:`TYPO3 Core API <t3coreapi:fal>` since core version 9.

    If looking for older versions, please refer to core v7 and core v8 of this document by using the
    version selector in the lower left corner of the online document.


**Sitemap:**

.. toctree::

    Targets


.. _introduction:
.. _about:
.. _what-s-new:
.. _credits:
.. _feedback:

.. _Admin-Basic-Concepts:
.. _concepts:
.. _Admin-Storages:
.. _concepts-storages-drivers:
.. _concepts-files-metadata:
.. _Admin-References:
.. _concepts-file-references:

.. _architecture:
.. _architecture-overview:
.. _architecture-folders:
.. _architecture-folders-processed-files:
.. _architecture-folders-migrated-files:
.. _Database-Structure:
.. _architecture-database:
.. _DB-table-sys_file:
.. _architecture-database-sys-file:
.. _DB-table-sys_metadata:
.. _architecture-database-sys-file-metadata:
.. _DB-table-sys_file_reference:
.. _architecture-database-sys-file-reference:
.. _DB-table-sys_file_processedfile:
.. _architecture-database-sys-file-processedfile:
.. _DB-table-sys_file_collection:
.. _architecture-database-sys-file-collection:
.. _DB-table-sys_file_storage:
.. _architecture-database-sys-file-storage:
.. _DB-table-sys_filemounts:
.. _architecture-database-sys-filemounts:
.. _architecture-components:
.. _architecture-components-files-folders:
.. _architecture-components-file-references:
.. _architecture-components-storage:
.. _architecture-components-drivers:
.. _architecture-components-file-index:
.. _architecture-components-collections:
.. _architecture-components-services:
.. _architecture-signals:
.. _architecture-signals-resource-storage:
.. _architecture-signals-resource-factory:
.. _architecture-signals-file-index-repository:
.. _architecture-signals-metadata-repository:
.. _architecture-signals-file-processing-service:

.. _Administrators:
.. _administration:
.. _Admin-Permissions:
.. _administration-permissions:
.. _administration-permissions-system:
.. _administration-permissions-mounts:
.. _admin-user-permissions:
.. _administration-permissions-user:
.. _Admin-User-Permissions-Per-Storage:
.. _administration-permissions-user-storage:
.. _Permissions-Details:
.. _administration-permissions-user-details:
.. _administration-permissions-upload-folder:
.. _administration-permissions-frontend:
.. _administration-storages:
.. _administration-maintenance:
.. _administration-maintenance-scheduler:
.. _administration-maintenance-processed-files:

.. _using-fal:
.. _using-fal-frontend:
.. _using-fal-frontend-typoScript:
.. _using-fal-frontend-fluid:
.. _using-fal-frontend-fluid-image:
.. _using-fal-frontend-fluid-fluidtemplate:
.. _using-fal-tca:
.. _using-fal-examples-resource-factory:
.. _using-fal-examples-resource-factory-default-storage:
.. _using-fal-examples-resource-factory-getting-storage:
.. _using-fal-examples-file-folder:
.. _using-fal-examples-file-folder-get-file:
.. _using-fal-examples-file-folder-copy-file:
.. _using-fal-examples-file-folder-add-file:
.. _using-fal-examples-file-folder-create-reference:
.. _using-fal-examples-file-folder-create-reference-backend:
.. _using-fal-examples-file-folder-create-reference-frontend:
.. _using-fal-examples-file-folder-get-references:
.. _using-fal-examples-file-folder-list-files:
.. _using-fal-examples-collections:
