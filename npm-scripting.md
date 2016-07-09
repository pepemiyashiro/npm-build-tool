Install NODE
Install lastest version of NPM
```
$ sudo npm install npm -g
```

WHY NPM is:
- Cross compatible.
- Run node_modules with out need to install -g
- The most important plugins used on FED exist on CLI


Scripts Hooks:
```
{
  "prestart"  : "Run First",
  "start"     : "Triggers the script but runs afte pre",
  "poststart" : "Run after the main Scripts",
}
```

Name-spaced sub-tasks
```
{
  "scripts": {
    "pet" : "npm-run-all pet:*",
      "pet:dog": "npm run bark",
      "pet:cat": "npm run meow",
      "pet:inu": "npm run wanwan",
  }
}
```

Shell Scripts
&&
|
>
<
