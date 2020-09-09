## Written submission
Please explain the steps you think are necessary to perform to get a feature done, from an idea to an implemented solution that is running in production. Be as detailed as possible. 

Makee a PR with your submission to this repository.

-------------------------------------------------------------------

To complete a feature, following agile values and principles, a number of steps are required:

# Design sprint 
The development team gets together for planning. The sprint time was reduced due to the constraints of the boot camp and the coaches acted as the client. The development team works closely with the client and both parties ask one another questions to establish the specific requirements.

# Epics/user stories
An epic captures a relatively high level, large area of work which should be broken down into smaller user stories. It is always recommended that the development team deliver smaller concise features/user stories. User stories are created for each feature specifying the stakeholder, the requirement of the story and desired result.  The user stories result in the features being described in a formulated way with acceptance criteria.

# Tasks/voting
Tasks for each feature/user story are outlined and lo-fis drawn up by the development team which set flow of actions and how the page will be displayed. They then review and discuss the complexity of all of stories in the sprint and then vote on how complex each story is using a three point scale.  

These features would then be added to the icebox. 

# Implementation:
1. The latest code from the central code base should be pull down to the pair programmers’ local drives who will be working on a desired feature and they branch out.
2. A test is written and just enough implementation code written to pass the test. This is then repeated until the feature is fully implemented and tests written to cover the ‘sad’ path.
3. A pull request in then made into the central code base, ensuring continuous integration checks pass. The pull request is then reviewed by the other team members/supervisor and any comments addressed. Once approved the code is merged into the central code base.
4. As continuous deployment is in place once the code is merged into the central code base it will be deployed immediately. 

The top priority is to write simplistic code that satisfies the client through early and continuous delivery of valuable software.