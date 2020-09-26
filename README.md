# npm_publish_versionbump
publish to npm after bumping the version number

# Install (tested on mac)
```bash
# via wget
wget https://raw.githubusercontent.com/kkristof200/npm_publish_versionbump/master/npm_publish_versionbump -O /usr/local/bin/npm_publish_versionbump && chmod u+x /usr/local/bin/npm_publish_versionbump

# or via curl
curl https://raw.githubusercontent.com/kkristof200/npm_publish_versionbump/master/npm_publish_versionbump > /usr/local/bin/npm_publish_versionbump && chmod u+x /usr/local/bin/npm_publish_versionbump

# optionally create symlink
ln -s "/usr/local/bin/npm_publish_versionbump" "/usr/local/bin/npub"
```

# Usage
```bash
cd to_desired_new_folder_path
npm_publish_versionbump # or npub if created symlink
```
