# SeleniumCucumberGradleTest

This project is for REFERENCE ONLY. Not suitable as boilerplate code ....yet

**Notes**
- If build.gradle is modified, you need to sync.
- Make sure you add the chromedriver which is compatible with your version of Chrome ... otherwise it wont run
- Also make sure your path is correct when declaring chromedriver in
  System.setProperty("webdriver.chrome.driver", "src/test/resources/driver/chromedriver");
  

**How to sync gradle ?**
1. Click on the small refresh icon (element with refresh)
Or.
2. Go to Gradle Tab > Click on "Reload all Gradle Projects"

_Once successful you will see "BUILD SUCCESSFUL in Xs"_



**How to run ?**
1. Go to build.gradle > Click on PlayButton on "task cubumber"
This will run as "Gradle" Project in the Run Configuration

Or.

2. Go to google.feature file >  Run as "Feature: google"
This will run as "Cucumber Java" Project

