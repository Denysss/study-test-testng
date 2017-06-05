# study-test-testng

#### Introduction.
What are we going to do now?
- theoretical part;
- practical part.

Two teams. Trainer chooses who answers a question.


#### Theory test:
1. What TestNG annotations do you know? (Before, After, DataProvider, Factory, Listeners, Parameters, Test)
2. What is the main structure of testng.xml? suite -> test -> groups/package/class ('s) -> method.  Golden rule - XML file should be simple and understandable.
3. What the difference between BeforeSuite, BeforeTest, BeforeClass, BeforeMethod are? - testng.xml
4. Groups? Where can we define them? - the parameter of @Test. Where can we use them? - in XML file to include or exclude.
5. DataProvider. What is it? When should we use it?
6. Dependencies. What is it? When to use. How?
6a. dependsOnMethods or dependsOnGroups
6b. Hard dependencies (SKIP) VS Soft dependencies (alwaysRun=true)
6c. How to make a group depending on other one - <groups> <dependencies> <group name="c" depends-on="a  b" />
7. Parallelism. How to run in separate threads (<suite name="My suite" parallel="methods|tests|classes|instances" thread-count="5">)
8. TestNG Listeners. What is it? When should it be used?

#### Practice - trainer's part:

Explain an Application/Class that should be tested

####Practice - Discuss which the final result should be:
1. Discuss which tests should be implemented (smoke, positive, negative(exception)).
2. Discuss groups.
3. Discuss Before and After.
4. Discuss DataProvider.
5. Discuss Dependencies (dependsOnMethods, dependsOnGroups).
6. Discuss Listener to log
7. Parallelism.
8. Discuss which XML files should be.


####Practice - help students if there are any questions
1. Implement tests, XML files, DataProvider, Listener