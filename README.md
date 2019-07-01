# custom-bash-scripts
A bunch of bash script I wrote to make life easier

If you want to use them, I would recommend putting them in a `custom/` folder in your `/usr/local/bin/`
  > `mkdir /usr/local/bin/custom/`
  > `git clone https://github.com/djpeach/custom-bash-scripts.git /usr/local/bin/custom/`
Make sure to add this new folder to your path
  > `echo PATH="$PATH:/usr/local/bin/custom/"; > ~/.bashrc`
Finally, give executable permissions to the scripts (wildcard, or just the one you want)
  > `chmod +x /usr/local/bin/custom/*`
  > `chmod +x /usr/local/bin/custom/<script_file_name>`

For all of them: copy and paste into terminal:
```
mkdir /usr/local/bin/custom/
git clone https://github.com/djpeach/custom-bash-scripts.git /usr/local/bin/custom/
echo PATH="$PATH:/usr/local/bin/custom/"; > ~/.bashrc
chmod +x /usr/local/bin/custom/*

```
