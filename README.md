# mumuki-escualo-sample-scripts
Sample scripts for deploying Mumuki Platform with escualo

## Getting Started

This repository contains sample scripts for deploying Mumuki Platform services, that can be used as inputs for the `escualo script` command. E.g.:

```
# download some script
wget https://github.com/mumuki/mumuki-escualo-sample-scripts/blob/master/server.simple.atheneum.yml 

# edit the script as needed. Replace any <VARIABLE> with your configurations before proceeding. 
vim server.simple.atheneum.yml 

# install escualo
gem install escualo

# run the script!
escualo script server.simple.atheneum.yml --hostname <HOSTNAME> --verbose --traceYOUR_HOSTNAMEb
```

:warning: **The scripts are not meant to be used as-is**. They contain `<VARIABLES>` that must be replaced by the script user before running `escualo script`. 
