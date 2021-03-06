[<img src="https://cdn.anychart.com/images/logo-transparent-segoe.png?2" width="234px" alt="AnyChart - Robust JavaScript/HTML5 Chart library for any project">](https://anychart.com)
# Python Flask basic template
This example shows how to use Anychart library with the Python programming language, Flask microframework and MySQL database.

## Running

To use this sample you must have Python 2.* installed (if not please visit [python download page](https://www.python.org/downloads/release/python-2712/)), PIP - Python package manager (if not please check [isntallation guide](https://pip.pypa.io/en/stable/installing/)) and
MySQL installed and running (if not please check out [MySQL download page](https://dev.mysql.com/downloads/installer/) and follow [instructions](http://dev.mysql.com/doc/refman/5.7/en/installing.html))

To check your installations, run the following command in the command line:
```
$ python --version
Python 2.7.6 # sample output
$ pip -V
pip 1.5.4 from /usr/lib/python2.7/dist-packages (python 2.7) # sample output
$ mysql --version
mysql  Ver 14.14 Distrib 5.5.52, for debian-linux-gnu (x86_64) using readline 6. # sample output
```

To start this example run commands listed below.

Clone the repository from github.com:
```
$ git clone git@github.com:anychart-integrations/python-flask-mysql-template.git
```

Navigate to the repository folder:
```
$ cd python-flask-mysql-template
```

Install dependencies:
```
$ pip install --user Flask
$ pip install --user MySQL-python
```

Set up MySQL database, use -u -p flags to provide username and password:
```
$  mysql < database_backup.sql
```

Run example:
```
$ python app.py
```

Open browser at http://127.0.0.1:5000/

## Workspace
Your workspace should look like:
```
python-flask-mysql-template/
    static/
        css/
            style.css       # css style
    templates/
        index.html          # html template
    app.py                  # main Python app code
    database_backup.sql     # MySQL database dump
    README.md
    LICENSE

```

## Technologies
Language - [Python](https://www.python.org/)<br />
Web framework - [Flask](http://flask.pocoo.org/)<br />
Html tepmlate - [Jinja 2](http://jinja.pocoo.org/docs/dev/)<br />
Database - [MySQL](https://www.mysql.com/)<br />


## Further Learning
* [Documentation](https://docs.anychart.com)
* [JavaScript API Reference](https://api.anychart.com)
* [Code Playground](https://playground.anychart.com)
* [Technical Support](https://anychart.com/support)

## License
[© AnyChart.com - JavaScript charts](http://www.anychart.com). Released under the [Apache 2.0 License](https://github.com/anychart-integrations/python-flask-mysql-template/blob/master/LICENSE).
