## v3.1 (November 27, 2018)
* improve debugging functions with VSCode plugin
* examples update to relect the latest scripting programming
* task template changes
    
## v3.0 (November 10, 2018)
* supported vscode editor debugging for rest/mocker server/task with all languages supporing: golang, Python, JavaScript
* there are upgrade issues that need to be manually handed to upgrade from 2.x to 3.0 includes
> * for golang based task & rest project, when we use callapi function, we changed to use "import restbird/rest/xxxx/" instead of "import restbird/xxxx" to import the api
> * for golang based mock server, when we use state, we must add the importing to the script's head "import State"

## v2.7 (October 27, 2018)
* big improvement of rest running related UI, like progress bar and status
* support request history for Python and nodejs based mockserver
* bug fix for url routing of Python based mockserver.

## v2.6 (October 17, 2018)
* bug fix for req.body undefined under certain conditon in nodejs based mock server.
* bug fix for failed to create case when directory level more than three in some cases

## v2.5 (September 27, 2018)
* bugs fix for rest python, rest golang template and several gui improvements.

## v2.2 (August 27, 2018)
* bug fix for python based mock server, which cause listen port INUSE error.

## v2.1 (August 17, 2018)
* bug fix for golang based mock server when you define mock APIs with same url path but different methods.

## v2.0 (July 30, 2018)
* Added Python and Javascript(nodejs) programming supported all through the projects.
* program examples added for all three programm languages (Python, JavaScript, Golang).

## v1.0 (March 30, 2018)
* Initial release of Restbird Docker image
* supports Rest Api Testing/Validation, Mock Server, Http Recorder and Replay.
* Golang as the programing language is supported all through the projects.
