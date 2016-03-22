.. _changelog:

===============
Release history
===============

0.6.2
-----
* Fixed regression from 0.6.0: Multiple sortable inlines are now possible again.

0.6.1
-----
* Removed global variables from Javascript namespace.

0.6.0
-----
* Compatible with Django 1.9.
* In the list view, it now is possible to move items to any arbitrary page.

0.5.0
-----
* Changed the namespace from adminsortable to adminsortable2 to allow both this
project and django-admin-sortable to co-exist in the same project. This is
helpful for projects to transition from one to the other library. It also allows
existing projects's migrations which previously relied on django-admin-sortable
to continue to work.

0.3.2
-----
* Fixed #42: Sorting does not work when ordering is descending.

0.3.2
-----
* Using property method ``media()`` instead of hard coded ``Media`` class.
* Using the ``verbose_name`` from the column used to keep the order of fields instead of a hard
  coded "Sort".
* When updating order in change_list_view, use the CSRF protection token.

0.3.1
-----
* Fixed issue #25: admin.TabularInline problem in django 1.5.x
* Fixed problem when adding new Inline Form Fields.
* PEP8 cleanup.

0.3.0
-----
* Support for Python-3.3.
* Fixed: Add list-sortable.js on changelist only. Issue #31.

0.2.9
-----
* Fixed: StackedInlines do not add an empty field after saving the model.
* Added management command to preset initial ordering.

0.2.8
-----
* Refactored documentation for Read-The-Docs

0.2.7
-----
* Fixed: MethodType takes only two attributes

0.2.6
-----
* Fixed: Unsortable inline models become draggable when there is a sortable inline model

0.2.5
-----
* Bulk actions are added only when they make sense.
* Fixed bug when clicking on table header for ordering field.

0.2.4
-----
* Fix CustomInlineFormSet to allow customization. Thanks **yakky**.

0.2.2
-----
* Distinction between different versions of jQuery in case django-cms is installed side by side.

0.2.0
-----
* Added sortable stacked and tabular inlines.

0.1.2
-----
* Fixed: All field names other than "order" are now allowed.

0.1.1
-----
* Fixed compatibility issue when used together with django-cms.

0.1.0
-----
* First version published on PyPI.

0.0.1
-----
First working release.
