### cs-305-projects

## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
In this assignment, Artemis Financial is a consulting company that develops financial plans for customers, which include savings, retirement, investments, and insurance. Artemis wants to modernize their operations, and they want to use current and effective software security. Artemis Financial has a public web interface, and want to add file verification to their application to protect client data. They need a data verification step in the form of a checksum. 

## What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I would say I did a thorough job of reading through the various dependency deprecations and identify how they and their criticality affect the application. Coding securely provides not only peace of mind but protection of data for users, who depend on the various companies' services they employ, such as Artemis Financial.

## What part of the vulnerability assessment was challenging or helpful to you?
My only issues would tend to come due to my machine not being as up to date and deprecated dependencies that I wouldn't notice immediately or until after the first check. It was good to be able to see a full picture of the dependencies and be able to gather information about them as well, to further understand their roles within the application and its operations.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
An SHA-256 hash encryption was introduced in order to encrypt crucial data being exchanged within the application.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
A lot of refactoring and re-tooling went into trying to produce a functional and secure code. I would tend to find very small issues that did not require a lot of editing, and handled them quickly, and luckily any new vulnerabilities were discovered and handled quickly thanks to the Maven dependency check.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I think getting more comfortable with things not easily seen, and working confidentally within command line inputs. I'm also going to make much more use of extensions that are applicable to the various languages I may work with, as they can assist in ways I don't see at first glance.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
Truthfully, I would hope to show that I will occasionally reach points where I have to take a step back and re-work what I am trying to accomplish, and that when I do reach a point of impasse, I will reach out and accept any and all help.
