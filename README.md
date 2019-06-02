# conferenceapp
super project - monorepo

# content
this repo only contains automation scripts and submodules

# usage
* to update the references use "git submodule update --recursive"
* to add another submodule add it via "git submodule add repo-path"
** don't forget to add the new module in the automation scripts
** commit and push the changes
* to build the app create an `.env` file with credentials from `env_template`
* run `docker-compose build && docker-compose up`
* access the server at localhost:4000. User for testing purposes on the frontend is
** username: testuser
** password: testtest
