# AutomationTestScript 
Prerequisites to run the test : 
Install Java 1.8
Install Eclipse 

Import the SampleTestProject as a Java Project in Eclipse 

Install selenium version 3.4.0 from the path below
https://www.selenium.dev/downloads/
Unzip the downloaded file and Add all the jars from lib folder in project build path 
Do not forget to add client-combined jar which is present outside the lib folder in selenium 


To resolve the build issues set up the environments by following the steps below:
Install Cucumber plugin in Eclipse
Steps:
1. Go to Help -> Install New Software 
2. Click on Add and paste the link https://cucumber.github.io/cucumber-eclipse-update-site-snapshot
3. Select Cucumber Eclipse Plugin
4. Click on next, agree the terms and conditions and click on finish 

Download and Add below cucumber jars to the created project build path 
Path to download cucumber jars: https://repo1.maven.org/maven2/info/cukes/
cucumber-html-0.2.7
mockito-all-2.0.2-beta
junit-4.12
cucumber-reporting-3.10.0
cobertura-2.1.1
gherkin-2.12.2
cucumber-jvm-deps-1.0.5
cucumber-junit-1.2.5
cucumber-java-1.2.5
cucumber-core-1.2.5


Once all the jars are added you can run the TestRunner.java class as junit test and can see the test report.
![Console_output](https://user-images.githubusercontent.com/94328887/141707408-0b332789-c8d2-4870-a314-3ee1e13254c2.PNG)
![JunitReport](https://user-images.githubusercontent.com/94328887/141707419-53c2fd90-d08f-42f9-bb1e-c732c75a98da.PNG)

