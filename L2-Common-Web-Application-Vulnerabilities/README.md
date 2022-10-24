# Setup Fine Tune

1. Install python and pip
2. install postgres

The tables for the database should be manualy created from `startup.txt` into psql terminal.

Postgres and the project should be edited at `Site/db/__init__.py` user & password.

1. change postgres root user & password

```
sudo -u postgres psql postgres
# \password postgres
Enter new password:
```

1. change user & password from `Site/db/__init__.py`
