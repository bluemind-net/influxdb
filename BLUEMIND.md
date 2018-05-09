git remote add upstream https://github.com/influxdata/influxdb.git
git fetch upstream 1.5
git rebase FETCH_HEAD
