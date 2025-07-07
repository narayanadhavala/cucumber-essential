# Cucumber Essential Training
This is the repository for the LinkedIn Learning course `Cucumber Essential Training`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

Cucumber is a tool for behavior-driven development (BDD), which allows you to write assertions in plain language that are then testable by code. By making written requirements actually testable, Cucumber provides a common language for business and engineering professionals. In this course, learn how to use Cucumber to implement agile practices like BDD, test-driven development (TDD), and acceptance test-driven development (ATDD). Instructor Shashi Shekhar goes over the basics of BDD, TDD, and ATDD, and then dives into the essentials of the Cucumber workflow. Along the way, gather tips on how to map user stories to features, add hooks, generate reports, and apply techniques to make BDD maintainable.

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

Navigate to the linkedinlearning.cucumbercourse folder and run "mvn test" to execute the test cases.

The restaurant_calculator folder contains a simple Python Django calculator web application. If you want to run this application, open a new shell session and navigater to the restaurant_calculator folder. Then run "python manage.py runserver" to start the web application. The application will be available at port 8000.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Branches (To be Confirmed)
1. Branches are named after chapters. 
2. The branch CH02After contains all code built during chapter 2. 
3. This course helps build code incrementally, often starting with the code written in the previous chapter(s). The branch named CH02After is effectively the same as "CH03Before" even though there is no branch named CH03Before. So CH03After is the same as "CH04Before" and so on.
4. You can start with main, which contains code at the beginning of the course and build code incrementally. Or start with a specific branch to get all code built in that chapter.
5. Chapter 1 has no coding lessons.


## Instructor

Shashi Shekhar

Enterprise Architect

                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/cucumber-essential-training-26244361
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4E0DAQHsGYSNUrrAQA/learning-public-crop_675_1200/B4EZd_ckKDHcAc-/0/1750189884322?e=2147483647&v=beta&t=GCnxd5sCmNZA6ItrpqgIzGkj3QmARDGBl04zguLTT90

