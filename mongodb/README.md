这是mongoDB的备份文件

备份：
```
mongodump -h 127.0.0.1 -d hdy_club_dev -o Desktop/mongodb/
```

恢复：
```
mongorestore -h 127.0.0.1:27017 -d hdy_club_test Desktop/mongodb/hdy_club_dev/
```