## to dev 
- http://docs.learninglocker.net/guides-custom-installation/
- basically:
    - install all software with homebrew 
    - checkout this project to webapp folder...
    - xapi project to xapi folder
    - setup the upstream remote:
        - git remote add upstream https://github.com/LearningLocker/learninglocker.git
    - merge in upstream/master when they make updates and you want that update
    - build everything in dev mode
    - `cd webapp` 

## then in three diff terminals
- `yarn dev-api-server --watch`
- `yarn start-dev`
- `yarn dev-ui-client`

now as you change in the api, it'll rebuild it and if you change in the ui client it will also rebuild it. 
