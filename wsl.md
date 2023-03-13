# wsl
- wsl install

# ubuntu
 user:user
 password:password
ref: https://softantenna.com/blog/how-to-setup-wsl2-wndows-11/

# nodenv
https://memoryclip.uchiida.com/2021/10/simple_way_of_install_nodenv_on_wsl2/
ubuntu :.bashrcに設定追加。

# nodenv installer
https://github.com/nodenv/nodenv-installer#nodenv-installer

# node 18.14.2
https://github.com/nodejs/node/blob/main/doc/changelogs/CHANGELOG_V18.md#18.14.2

# nodenv versionup
cd ~/.nodenv/plugins/node-build
git pull

# vite start
 npm create vite@latest

# how to install chrome on wsl
https://scottspence.com/posts/use-chrome-in-ubuntu-wsl
```
sudo apt update && sudo apt -y upgrade && sudo apt -y autoremove
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt -y install ./google-chrome-stable_current_amd64.deb
google-chrome --version
```

# how to setting webstorm debug to js.
- `double shift` and type `Edit configuration`
- click to `Add new configuration`
- Select `JavaScript Debug`
- Name: Any
- URL: http://localhost:{your-port}
- File & Directory: project root

# how to debug vite-react on wsl with WebStorm.
- setting webstorm. -> how to setting webstorm debug to js.
- install chrome on wsl
- execute vite-react on terminal. or run on WebStorm.
- Debug configuration execute to debug on WebStorm's setted debug configuration.
-  Don't forget set to break point your debug line.
