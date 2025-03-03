# NOTE

When initializing the DB, any folders that are to be created to run as a volume pointer need to be assigned to a specific user using the following line:
```
sudo chown 10001 data &&
sudo chown 10001 log &&
sudo chown 10001 secrets
```

> ```10001``` is a custom owner created in the SQL Server instance and is a fix for permission issues when initializing the container instance.
