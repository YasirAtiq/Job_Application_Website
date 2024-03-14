# Django Job Application Website

## Latest Commit: "Setting Up Project & Adding TODO"
### Setting Up Project
Built the project tree shown below at [here](#project-tree) using `django-admin startproject "Main_Project" .` and built app Homepage by `django-admin startapp "Homepage"`.

Note: Add `Homepage` to `INSTALLED_APPS` in `Main_Project\settings.py`

### Adding TODO
Check [TODO](../TODO) file for more information.

## Project's aim:
This aim's to build a new version of the repo which I made earlier (`YasirAtiq/Django_Job_Web_App` which is deleted now).

## Project Tree
```tree
+------------------------------------------------------------------------+
| -> .gitignore                                                          |
| -> LICENSE                                                             |
| -> manage.py                                                           |
|                                                                        |
+---+ .github                                                            |
|   | -> README.md                                                       |
|   +--------------------------------------------------------------------|
|                                                                        |
+---+ Homepage                                                           |
|   | -> admin.py                                                        |
|   | -> apps.py                                                         |
|   | -> models.py                                                       |
|   | -> tests.py                                                        | 
|   | -> urls.py                                                         |
|   | -> views.py                                                        |
|   | -> __init__.py                                                     |
|   +---+ migrations                                                     |
|   |   | -> __init__.py                                                 |
|   |   +----------------------------------------------------------------|
|   +--------------------------------------------------------------------|
|                                                                        |
+---+ Main_Project                                                       |
|   | -> asgi.py                                                         |
|   | -> settings.py                                                     |
|   | -> urls.py                                                         |
|   | -> wsgi.py                                                         |
|   | -> __init__.py                                                     |
|   +--------------------------------------------------------------------|
|                                                                        |
+------------------------------------------------------------------------+
```
