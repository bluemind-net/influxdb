git remote add upstream https://github.com/influxdata/influxdb.git
git fetch upstream 1.7
git rebase FETCH_HEAD

# create the branch on remote
git push origin bm-1.7
