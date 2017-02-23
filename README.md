# REST API testing example on Groovy and Spock
Created for Selenium Camp 2017

To use this example you have to install json-server locally and run it:
```bash
$ npm install -g json-server
$ json-server http://jsonplaceholder.typicode.com/db
```

More info about the json-server here:
* https://github.com/typicode/json-server

Then you can run the tests from IDE or by the command

```
gradlew clean test
```

To generate the report
```
gradlew allureReport
```

Report will be generated by default to:
```
build/allure-report/index.html
```

Additional info can be found here

* [Video from QA-Fest 2016](https://youtu.be/5elqH5UNwkk)
* [Groovy documentation](http://groovy-lang.org/documentation.html)
* [Spock documentation](http://spockframework.org/spock/docs/1.1-rc-2/all_in_one.html)
* [RESTClient documentation](https://github.com/jgritman/httpbuilder/wiki/RESTClient)
* [Allure home](http://allure.qatools.ru/)
