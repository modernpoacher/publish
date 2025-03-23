# Publish to NPM

For CircleCI or the shell

If you need an _authentication token_ to publish then you should resolve that before executing this script

```bash
echo ".publish/publish.sh" >> .npmignore
git clone https://github.com/modernpoacher/publish.git .publish
.publish/publish.sh
```

A Gist with the same content as `publish.sh` may need an additional step

```bash
echo ".publish/publish.sh" >> .npmignore
git clone https://gist.github.com/efd85e2b8da1ee830dd637f134994a9d.git .publish
chmod +x .publish/publish.sh
.publish/publish.sh
```
