# washify

## deploy

```
git checkout build
git reset --hard origin/master
git push origin build:build
```

Then log into the server:

```
sudo su washify
~/deploy.sh
```
