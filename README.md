# RULES
* only commit packaged/minified applications in /Public/*yourappname/
* do not update npm config 
* If a service is needed contact tom@knabelabs.com 


## COMMITING 
* `git checkout master -b [your project name here]`
* commit your files
* `git push origin [your project branch name]`
* create a PR into development branch first
* when dev branch updates -- changes should reflect in environment within 2 minutes
* view changes at mmdev.theescapegame.com
* if passes QA create a PR of development into master
* Master instantly deploys when branch updates

## Run on Local
* `npm install`
* `npm start`
* done 