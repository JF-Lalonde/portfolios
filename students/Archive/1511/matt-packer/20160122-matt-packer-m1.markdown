# Matt Packer - M1 Portfolio

## Individual

### Your Mission

To improve my technical problem solving skills to a point where I feel confident teaching others, while using feedback and self-reflection in order to develop as a student.

### Mid Module Assessment

##### Evaluation Comments

Assessed by Jeff Casimir
* Work on a couple keyboard shortcuts like swapping focus between panes
* Work on keeping your head up while typing -- especially with an external monitor
* Comfortable workflow early on -- good understanding of tests and workflow
* Seem comfortable writing a test from scratch
* Implementation is somewhat hesitant but ok
* Developer is able to write Ruby with some debugging of fundamental concepts
* Developer refactors for clarity but has some areas for improvement
* Developer writes tests that are effective validation of functionality, but don't drive the design
* Developer smoothly moves between tools, but is dependent on mouse-driven interaction
* Developer lays out their thinking before attacking a problem and integrates feedback through the process

##### Evaluation Scores
* Ruby Syntax & API: 3
* Ruby Style: 3
* Testing: 3
* Workflow: 2
* Collaboration: 3

### End of Module Assessment

**Instructor** Horace

**Result:** Retake

**Notes:**

* Crippling nerves prevented us from making much progress
* Ended up struggling to react appropriately to the data structures
we were encountering
* Need to figure out a way to slow down and think through more specific
and tailored solutions rather than trying to rush to the answer

1. Ruby Syntax & API - __2__: Developer is generally able to write Ruby, but gets stuck on or needs help with fundamental concepts
2. Ruby Style - __3__: Developer writes code that is easy to follow
3. Blocks & Enumerations - __2__: Developer can use enumerator methods, but struggles to choose the right one for the job or demonstrates weak understanding of blocks
4. Testing - __3__: Developer uses tests to guide development in small chunks
5. Workflow - __3__: Developer demonstrates comfort with their tools and makes some use of keyboard shortcuts
6. Collaboration - __3__: Developer lays out their thinking before attacking a problem and integrates feedback through the process

### End of Module Assessment (Retake)

Assessed by Josh Cheek

Assessed by Josh Cheek on 20 Jan 2015

Challenge: Multipliers

###### 1. Ruby Syntax & API - Score: 3

* Gets lost in details, but when told to think about it, is able to figure out how things work
 More precision and more practice would dramatically improve your ability here

###### 2. Ruby Style

Score: 3

###### 3. Blocks & Enumerations - Score: 3

* Figured out zip
* Would have benefitted from `inject`

###### 4. Testing - Score: 3

* Starts with test
* Chooses good test names!
* Be more cognizant of edge cases, eg empty word and multiplier of 0 would both be interesitng,
 and the `[2,2]` allowed a bug to exist for a while.

###### 5. Workflow - Score: 3

* Generally good
* A bit more practice, make yourself use the things you know are effective

###### 6. Collaboration Score: 3

* Good recitation back to me
* Don't worry so much!

### Attendance

I have been present and on time for every Turing class.

### Work

The following section consists of two individual projects, 'Jungle Beat' and 'Enigma', along with instructor feedback and scores for each project. All were completed during the first three weeks on Module 1.

#### Jungle Beat

* [GitHub URL](https://github.com/matthewrpacker/linkedlist.git)
* [Original Assignment](https://github.com/turingschool/curriculum/blob/master/source/projects/jungle_beat.markdown)

##### Description

'Jungle Beat' focused on developing a fundamental understanding of linked lists. The goal was to implement a linked list in ruby using either iteration (looping) or recursion.

##### Evaluation Comments

Assessed by Lovisa Svallingson
* Developer didn't complete the project but the existing code for the linked list shows conceptual understanding.

##### Evaluation Scores
* Functional Expectations: 1
* TDD: 2
* Encapsulation: 3
* Ruby Style and Fundamentals: 3
* Looping / Recursion: 3

#### Enigma

* [GitHub URL](https://github.com/matthewrpacker/enigma)
* [Original Assignment](https://github.com/turingschool/curriculum/blob/master/source/projects/enigma.markdown)

##### Description

'Enigma' focused on encrypting and decrypting a given message through the use of a key, offset, and input/output files.

##### Evaluation Comments

Assessed by Josh Cheek
* Encrypts
* Decrypts
* No crack
* No extensions
* Can't pass a different date or a different key
* Some opportunity for arrays
* [Travis CI](https://travis-ci.org/matthewrpacker/enigma)
* Nice method names, go a little further with it
* Liked the tests
* Consolidate encryptor and decryptor by taking out the 1 line that is different (which map to use)
* Generally nice job :)

##### Evaluation Scores
* Overall Functionality: 2
* Fundamental Ruby & Style: 3
* Test-Driven Development: 3.6
* Breaking Logic into Components: 3

## Team

### Projects

The following section consists of two group projects, 'HTTP Yeah You Know Me' and 'Headcount', along with instructor feedback and scores for each project. All were completed during the second three weeks on Module 1.

#### HTTP Yeah You Know Me

(In collaboration with Chad Ellison)

* [GitHub URL](https://github.com/chadellison/server_project)
* [Original Assignment](https://github.com/turingschool/curriculum/blob/master/source/projects/http_yeah_you_know_me.markdown)

##### Description

'HTTP Yeah You Know Me' focused on building a functional web server in Ruby.

##### Evaluation Comments

Assessed by Tess Griffin
* Got through iteration 3 with the word search. Nice to see components broken out into separate classes. It was strange duplication between the iterations. They created separate files for each one. Told them to not do that in the future.
* Application implements three iteration
* Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.
* Application uses tests to exercise core functionality and some edge cases, but fails to break out component objects/tests.
* Application has multiple components with defined responsibilities but there is some leaking of responsibilities

##### Evaluation Scores
* Overall Functionality: 2
* Fundamental Ruby & Style: 3
* Test-Driven Development: 3
* Breaking Logic into Components: 3

##### Feedback

#### HeadCount

(In collaboration with Adrienne Domingus)

* [GitHub URL](https://github.com/adriennedomingus/headcount.git)
* [Original Assignment](https://github.com/turingschool/curriculum/blob/master/source/projects/headcount.markdown)

##### Description

'Headcount' focused on how to query, search, associate, and analyze data stored in CSV files. The dataset consisted of Colorado school statistics provided by the Annie E. Casey foundation.

**Instructor:** Horace (& Mary w/ the assist)

**Repo Url:** https://github.com/adriennedomingus/headcount

#### Evaluation Notes:

* implements expected iterations
* good job tackling vaguely defined result set / result entry stuff in I6
* tests are numerous and effective, relying on a trimmed data set to support easy
testing and anticipation of results
* would have liked to see some means of overriding the data set from tests without having
to edit the data files
* connections between the analyst and the various repositories are clear and easy to follow; however
it does place the Analyst in a privileged position at the top of the hierarchy
* discovered a somewhat rigid dependency on the file structure with harcoded paths in a few places
* analysis methods are well-written and easy to follow; using appropriate enumerables and data helpers to filter down the
data set as needed

#### Evaluation Scores:

##### 1. Functional Expectations - 3: Application fulfills expectations of Iterations 0 - 4 *as well as* one of Iterations 5 or 6
##### 2. Test-Driven Development - 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality
##### 3. Encapsulation / Breaking Logic into Components - 3: Application effectively breaks logical components apart but breaks the principle of SRP
##### 4. Fundamental Ruby & Styl - 3:  Application shows strong effort towards organization, content, and refactoring
##### 5. Enumerable & Collections - 3: Application demonstrates comfortable use of appropriate Enumerable methods

## Community

### Giving Feedback

##### To Hedy:

“While pairing with Hedy, I came to realize that she is one of the most driven and insightful people I have ever met. Her determination is contagious and she demonstrates significant leadership skills. Also, I really enjoyed how she would communicate not only how she planned to improve while at Turing, but also how I could do the same. I found her work ethic encouraging, and really appreciated her helping me work through concepts that I had difficulty understanding." - Matt Packer

##### To Chad Ellison:

“I worked with Chad on the HTTP project. Chad is extraordinarily talented at deconstructing a large problem into workable components. Oftentimes, Chad would develop a game plan that would help direct our team’s focus; I found this strategy helped our team break the project down into manageable steps. Also, Chad was very good at communicating his viewpoints while thinking through a problem. His open communication style encouraged collaboration and helped the both of us move forward. I think it would be helpful for the both of us to work on maintaining a strict pomodoro schedule in order to avoid spending too much time on any one problem. I know that Chad’s drive, resilience, and problem solving skills would bring success to any team." - Matt Packer

##### To Brian Rippeto:

“Brian would make an excellent contribution to any team. He clearly communicates his understanding of the problem at hand, while providing a possible solution; this helps the team gain consensus before implementing a solution. I found his approach helpful both in overcoming challenges and debugging testing errors. I am confident that Brain will continue to develop his workflow by utilizing additional keyboard shortcuts." - Matt Packer

### Being a Community Member

##### From Hedy Woo:

 “I can’t find enough quality words to describe how great Matt has been as a pairing partner.  He is quiet, but very insightful, and will comment just the right way, and at the right time, to give guidance and direction to a project.  I loved the questions you asked during the projects, and your reliance on well documented notes, grounded my otherwise, flighty, and possibly impossible ideas. So thank you! Working with you was both fun and encouraging for me! Thanks for being a friend at Turing and a great pairing partner!"

##### From Chad Ellison:

"Matt is very patient and he is a strategic developer with a great perspective on priorities. Throughout our time working together on "Http, Yeah, you know me", he was constantly directing our resources on the essential problems. He is very methodical in his approach and as a result, we had a stronger app than we otherwise would have had. Matt's ability to learn and retain information efficiently will make him a great developer. He was able to adapt and deconstruct problems while they were still very new and abstract to both of us."

##### From Brian Rippeto:

"I enjoyed the calm collected thoughts Matt delivered as we navigated through an assignment that was tough for both of us. When stuck on a problem he vocalizes ideas for a new approach instead of projecting discouragement. Like many of us at this stage in our learning process, Matt would benefit from having more confidence in his abilities and solutions."

### Playing a Part

I did my best to support the Turing community by working with my 'posse' on morning warmup exercises and offering help, guidance, and encouragement to fellow students. I look forward to finding additional ways that I can better support the Turing community.

## Review

### Notes

* assessment came together on the second take
* individual projects consistently showing good code but short
on fulfillment / completion

### Outcome - PROVISIONAL PASS

* __A End-of-Module Assessment:__ 3
* __B Individual Work & Projects:__ 3*
* __C Group Work & Projects:__ 3
* __D Community Participation:__ 3
* __E Peer & Instructor Feedback:__ 3
