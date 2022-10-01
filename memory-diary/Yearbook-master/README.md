# Yearbook

- Scrape data
- Create pass
- Csv to Database
- add polls
- Deploy 
- Get class photo and add
- Get yearbook through print
- get group pics and run collage maker
- merge all the three

# Collage Generation
cd to the `/collage` directory and run `compose.py`
```bash
python compose.py
```

# Yearbooks generation
Usage:
```python
python manage.py yearbooks [-h] [-d DEPARTMENT] [-o OUTPUT] [--all] [--version] [-v {0,1,2,3}] [--settings SETTINGS] [--pythonpath PYTHONPATH] [--traceback] [--no-color]
```
```
-h                          Display help message, for usage and arguments description
-d DEPARTMENT               To generate yearbook for a specific DEPARTMENT
-o OUTPUT                   To specify output directory
--all                       To generate Yearbooks for all departments
--v {0,1,2,3}               Verbosity level :
                                0 = minimal output
                                1 = normal output
                                2 = verbose output
                                3 = very verbose output
--settings SETTINGS         To specify python path to the settings module, e.g. "myproject.settings.main", If not provided, DJANGO_SETTINGS_MODULE variable will be used
--pythonpath PYTHONPATH     To specify python path
--traceback                 Raise on CommandError expecptions
--no-color                  To not colorize the command output
```
<br>


# Best way to share and collect your college stories spent with friends. Feel free to clone and use it. Don't forget to star the repo.
