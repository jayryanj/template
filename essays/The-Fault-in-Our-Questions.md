---
layout: essay
type: essay
title: The Fault in Our Questions
# All dates must be YYYY-MM-DD format!
date: 2019-09-12
labels:
  - Software Engineering
  - Stack Overflow
  - Community
  - Communication
---


Software engineering does not have to be a lonely endeavor. It's a difficult subject that involves solving a lot of problems that you often can't solve by yourself. Fortunately, there are large communities such as Stack Overflow that are there for assistance. There are wide audiences of experts with a range of skills that can help weary developers figure out a solution. Developers can succeed in software engineering by communicating their problem <strong>precisely</strong> to the <strong>correct community</strong> in order to receive an effective and meaningful answer to their problem.

<h2>There is a Right and Wrong Way</h2>
Encountering code problems may be frustrating, but developers shouldn't let that frustration leak into their questions. There is a right and wrong way to communicate a problem. The answers that are produced could be affected by the quality of the question. Smart questions are effective at communicating the problem properly for the convenience of those that are trying to answer them. Ineffective questions are an inconvenience to everyone involved. Fortunately, there are best-practices for software engineers to get the most out of the help that a community would be able to provide. The follow are examples of a smart question and an ineffective question that we will analyze further.

<img class="ui medium left floated image" src="../images/stackoverflow.png">

<strong>Here is an example from Stack Overflow of a smart question:</strong>
```
Tag: Security
Q: Secure hash and salt for PHP passwords
It is currently said that MD5 is partially unsafe. Taking this into consideration, I'd like to know which mechanism to use for password protection.

This question, (link to other question) Is “double hashing” a password less secure than just hashing it once? suggests that hashing multiple times may be a good idea, whereas (link to other question) How to implement password protection for individual files? suggests using salt.

I'm using PHP. I want a safe and fast password encryption system. Hashing a password a million times may be safer, but also slower. How to achieve a good balance between speed and safety? Also, I'd prefer the result to have a constant number of characters.

- The hashing mechanism must be available in PHP
- It must be safe
- It can use salt (in this case, are all salts equally good? Is there any way to generate good salts?)

Also, should I store two fields in the database (one using MD5 and another one using SHA, for example)? Would it make it safer or unsafer?

In case I wasn't clear enough, I want to know which hashing function(s) to use and how to pick a good salt in order to have a safe and fast password protection mechanism.
```
<strong>And this is an example of an ineffective question: </strong>
```
Tag: Python
Q: Keyboard messed up when using Pycharm as an IDE?

Don't get me wrong, Pycharm is an amazing IDE, and with its faults, I've still continued to use it and adapt to its way of working. But its getting pretty tedious not being able to do what I want.

Like in other IDE's, I can CTRL+A to select all the text, somehow it almost always messed up in Pycharm, copying all text will result in what ever the INSERT key does, and deletes my content.

Clicking backspace doesn't delete the highlighted content, instead I have to deliperatly click the delete key, and this isn't exactly wrong, but it doesn't fit in with other IDE's.

I noticed when switching from Pycharm to another IDE, I was doing what I did in Pycharm and it just felt unnatural, is there a way to make Pycharm work like other IDE's?
```
<h2>Relevant Audience for Relevant Answers</h2>
Software engineers need to be able to reach the correct community to receive meaningful and relevant help. There is a large selection of communities, tags, or categories to choose from. Although they all exist with the intent to help others, community members typically don't want to spend time on irrelevant topics that are outside the scope of their knowledge or skills. Choosing the appropriate community for a specific topic is important for reaching an audience that will understand the question immediately. The first question regarding secure password-handling mechanisms in PHP is a good example of reaching the right audience because it's within the "security" tag. It reaches those that have a specific intent on answering security-related questions. It would have been a bad practice if the question was placed in the PHP tag. The question would have reached an audience of PHP developers that may not necessarily know anything about password hashing. As a result from choosing the correct community, answers and solutions that are provided from that specialized community may be more meaningful. Furthermore, the second question regarding the Pycharm IDE is placed in an inappropriate tag. Although Pycharm is associated with Python, the question has nothing to do with Python programming. That user's issue is focuesd on the configuration of IDEs. Since the question is off-topic from Python programming, community members may think that the question is a waste of time. It's important to choose a community that's relevant and within the scope of your issue in order to receive relevant answers.


<img class="ui medium left floated image" src="../images/audience.jpg">

<h2>It's All About Precision</h2>
Furthermore, software engineers need to able to convey their problem with a precise and informative question. Problems need to be precise in order to receive a precise solution. They need to convey the problem in such a way that is easy to understand at a deep level. Community members don't enjoy reading questions that don't get to the point. Smart questions always convey the main problem immediately before diving into the details or steps. In the first question, the user instantly conveys their problem within the first two sentences by saying that they'd like to know "which mechanism to use for password protection" in PHP. This saves the community members time by providing the point of the question immediately. The second question does not precisely convey the issue because the user writes the main question at the very end of his post. This may annoy community members because they don't understand the point of the user's question until they've already read the entire post. In addition, it's important for developers to show that they've put time into finding a solution before asking for help. It shows that the developer cares enough to solve their issue on their own before lazily asking the community for assistance. For example, the first question shows evidence that the author tried to do their research on the topic before posting their own question. They created links to several other questions that they read beforehand. They also evidently know a sufficient amount of background to effectively convey their question. It shows to community members that the developer actually cares deeply for a solution to their problem because they are puttin in the effort to research. However, the second question seems very lazily produced. The author shows that they didn't even bother to look into the configuration manual for Pycharm. The community is not there do all the research for them. It's important for software engineers to convey their problem effectively and precisely to get the most out of the assistance that the community provides. They must be able to reciprocate the amount of effort that others will put into answering the question.

<h2>Conclusion</h2> 
Everyone has questions. It's not an uncommon occurrence in software engineering to require assistance with a problem. Effective software engineers know how to produce sufficient questions that will receive sufficient answers and solutions. There are large communities of generous individuals that assist those that need help. Be generous to them by providing effective and <strong>smart</strong> questions.






