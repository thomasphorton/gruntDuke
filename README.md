# gruntDuke

make duke work with grunt

## global dependencies
* npm
* bower
* grunt

## getting started

1. clone repository (to your desktop is fine)
2. install local dependencies
  * `npm install`
  * `bower install`
3. edit /config.json
4. create a server.json file in each repository directory
5. run server with sudo permissions `sudo node app`
6. navigate to http://localhost:3000
7. click 'Check Active Repository' to see the current server status

*** warning: be patient! there aren't many failsafes. double check the server before doing anything crazy.

## troubleshooting

### grunt hangs when moving repositories
check to make sure the target repository does not have an /aspnet_client/ directory.

### can't parse server.json
run server.json through JSONlint- there is most likely an issue caused by extra whitespace in the JSON.
