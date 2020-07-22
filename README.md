# Useful MySQL commands

**Login to a database**

```
mysql -u [username] -h [host] -p [password]
```

**Import to an existing database**

```
mysql -u [username] -h [host] -p [password] [database_name] < SQL file to import
```

**Export and zip an existing database**

```
mysqldump -u [user] -h [host] -p [db_name] | gzip > [filename_to_compress.sql.gz] 
```