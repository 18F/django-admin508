# Admin508

Admin508 offers improved accessibility for Django's admin interface.

This package is a work in progress. The goal is to bring Django admin interfaces into full compliance with Web Content Accessibility Guidelines 2.0's AA standards.

Currently supporting Django 1.9

## Quick start


1. Add admin508 to your project as an app

2. Add admin508 to your INSTALLED_APPS in settings.py:

```
    INSTALLED_APPS = [
        'admin508.apps.Admin508Config',
        ...
    ]
```

3. Start the development server and visit http://127.0.0.1:8000/admin/
   to see the updated admin in action.
