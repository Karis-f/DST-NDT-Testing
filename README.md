# DST-NDT
This article, to learn details about destructive testing and non-destructive software testing. also see the differences between these two testing types.


Difference Between Destructive Testing and Non-Destructive Testing with Its Types and Methods:

What Is Destructive Testing And What Are Its Benefits?
Destructive Software Testing (DST) is a kind of software testing that tries to cause a part of software application to fail in an uncontrolled way, to test its robustness and detect the point of failure.

Destructive

Contrasting with other conventional type software testing methods that check the functionality of the software, this method inspects the unpredictable user behavior within the software. So, it enables us to uncover software defects that are generally not encountered by average users.

Please note that destructive software testing (DST) is an alternative approach to conventional type software testing (CST), but not its replacement. It is effective to carry out DST in addition to CST.

Destructive testing is carried out under the most rigorous operating conditions and it keeps on going until the application breaks. The key idea of this testing is not only to uncover the design weaknesses if any which possibly will not be revealed under normal working conditions but also to discover the service life of the software product.

This type of testing shares similarities with Monkey Testing, Ad hoc Testing, and Exploratory Testing.

Benefits of Destructive Software Testing

It helps to gauge robustness, recoverability, and lifespan of the application.
Reveals the points of failure in case of inappropriate or misuse of the software.
It sets the right context for the tester as it ignores the biases of user stories in testing.
It enables us to uncover software defects that are generally not encountered by average users.
This type of testing is unique in discovering flaws in the application that when addressed will promote the rank of the software to novice proof status.
Steps to Perform This Testing
At the beginning of the destructive software testing cycle, the client sends an application copy or access credentials, and user requirements.
The client then presents the requirements and demonstrates the application to a QA analyst.
Next, the QA analyst establishes the function of boundaries within the application and creates the usability limits of the application within the boundaries.
Now, the QA tester will randomly test the application within those boundaries, using the stochastic techniques. The QA test workflows and defects are recorded.
Finally, the defect directory is shared with the client.
If there is a need, the destructive testing cycle can be repeated based on the client’s requirements.
For this testing, it is good to have some knowledge of the original requirements of the software. This aids in coming up with a good testing strategy.

What do you verify in Destructive Test?
Improper and proper behavior of the software application.
Valid and invalid input data.
Improper usage of the software application.
Destructive Software Testing Methods and Strategies
There are several ways through which destructive testing can be carried out:

1) Failure Point Analysis Method:

In this method, the application is reviewed and examined to access every path and corner of it. It is determined what can fail at various points. For this method, you can take help from business analysts to have a walkthrough of the application.

2) Peer Review:

Get the application reviewed by a fellow tester who is not familiar with the software. This will help in finding some hidden points of failure which were not visible to you as a tester.

3) Get test cases reviewed by the business:

The end-users and other stakeholders can sometimes think of valid test scenarios that a tester may have missed. So, getting the test cases reviewed by the business can increase your test coverage.
4) Exploratory testing:

Carry out exploratory testing with the help of run sheets. It will help you to know what is tested, repeat the tests and control the test coverage.

5) Feed the system with improper data:

You can supply invalid input to the application. This may include corrupt data, the wrong sequence of steps on the user interface, etc.

6) Use other sources:

You can also use any other sources or ways to break the system and analyze for different scenarios. The good thing is that the user story of destructive software testing does not necessarily ask for ‘requirements’ and ‘specifications’, so you can try out any suitable way to conduct this testing.

Destructive Testing Techniques
Destructive software testing can be conducted through various techniques like:

Acceptance testing
Loop testing
Regression testing
Equivalence partitioning
Boundary value testing
Interface testing
Alpha/Beta testing
System testing
Top-down testing
Black box testing
Few Useful Tips for Destructive Software Testing
Gain as much knowledge of the product as you can. Put yourself into the shoes of the customer and then think about the product from his perspective.
Erase all the biased information from the user story. Forget about the user story description and acceptance criteria and try to break the application like a crazy customer.
Look for the exception paths, not the happy paths. Keep in mind that by ignoring the acceptance criteria, you will not know the expected or normal workflow.
Don’t expect a positive response from your application. What if something fails? Try to simulate and corrupt everything you can.
Curb your network conditions to a more realistic setup, because all the real users won’t be having top-class machines and network conditions.
What Is Non-Destructive Testing And What Are Its Benefits?
Non-Destructive Testing (NDT) is described as a software assessment technique that entails interacting with software correctly. Unlike destructive software testing where we look for exception paths, in non-destructive testing, we look for happy paths or golden paths. NDT is also known as positive testing.

For example, if there is an input box that accepts a number within 1-999, then a positive test case would be to enter a number within this range and verify the functionality of the input box.

Non-Destructive Test Example

In NDT, we have a well-defined test case using a known requirement, which executes without any error or exceptions and produces the desired output. It gives the expected results and verifies that the software is working as expected.

Benefits of  Non-Destructive Software Testing

Improved software quality and issues get fixed in the main flow of the application.
Useful in demonstrating that the software application is working as per the required specifications.
Verifies that the customer expectations are met.
Ensures that the performance requirements are met.
Saves both time and money in product evaluation and troubleshooting.
When to Perform This Testing
It should be the first form of testing and needs to be done at the initial stage of SDLC because the happy path is the main flow of the application and if it does not work well then the rest of the testing gets blocked.
It can be quickly and easily done when we don’t have enough time and budget for testing. This at least ensures that software requirements and acceptance criteria are met.
Strategy for Non-Destructive Software Testing
The positive testing approach should be adopted to conduct the non-destructive test.
While doing the testing, the tester should keep in mind that the objective of the non-destructive test is to verify that the application will work fine on giving valid input data. So, the aim is to verify the application behavior for the positive set of data.
The best practice is to check whether the system is doing what it is intended to do.


Conclusion
In destructive testing, the application is intentionally made to crash to examine the robustness of the application. It detects the points of failure in the software that may occur due to improper handling of the application by the customer.

It detects those weak spots that cannot be tracked using conventional software testing. For better test coverage, it is preferred to conduct destructive software testing along with conventional software testing.

Non-destructive testing is done with the positive testing or happy path testing approach to verify that the software functionality is meeting the customer requirements. It involves interacting with the software correctly.
