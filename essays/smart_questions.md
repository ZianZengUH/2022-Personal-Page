---
layout: essay
type: essay
title: "Can’t Get a Helpful Answer? Try Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
  - Reflection
---

<img width="500px" class="rounded float-start pe-4" src="../img/essays/stack_overflow.png">

## Introduction: Why is Asking a Smart Question Important?

We often ask questions in our life and this is a common thing in the world of software engineers as well.  Not all of our questions can get good answers or even get an answer at all, especially for technical questions. One of the influential factors that caused this issue is that we probably did not ask a smart question. How we ask and present the question is as important as how challenging it is to provide the answer. Therefore, the way to ask questions is crucial. In order to get a more helpful and satisfactory response to the question, we need to ask the question in a way that can increase the possibility of getting such answers. This is where a smart question demonstrates its importance. 


## The Way to Get a Helpful Answer

There are many things that you can do to increase your likelihood of getting a good answer. In other words, you can do a lot of things to generate a smart question. According to Raymond and Moen (2014), before asking a question, you should do your best to do your own research first rather than hoping others will feed you the entire solution for a big problem. You may do the following:
Try to find an answer by searching the archives of the forum or mailing list you plan to post to.
Try to find an answer by searching the Web.
Try to find an answer by reading the manual.
Try to find an answer by reading a FAQ.
Try to find an answer by inspection or experimentation.
Try to find an answer by asking a skilled friend.
If you're a programmer, try to find an answer by reading the source code. (Raymond & Moen, 2014)

The most important thing is that you need to show that you did your own research when asking the question.
Second, Raymond and Moen (2014) mentioned you can “use meaningful, specific subject headers” to get people’s attention and a better understanding of the subject that you are querying on. Third, you should write in clear, concise, and grammatically correct language. Fourth, you should present the questions in “accessible, standard formats”. Finally, you should try to be precise and informative about your problem, and try to describe the symptoms of your problem in a clear manner while avoiding only presenting your guess. There are still many methods that Raymond and Moen noted on their website, but this should provide some good insights on what is a smart question and how to form it.

Now, let’s look at an example of a smart question that was posted on StackOverflow. In this post, the developer asked a question about how to calculate r-squared using Python and Numpy. First of all, the developer has a clear and specific subject headline as “How do I calculate r-squared using Python and Numpy?”. In this headline, the developer presented the leading elements related to his requests such as the specific language (Python), library (Numpy), and topic for help (r-squared). Second, the developer described his situation and problem precisely and informatively without grammatical errors. At the beginning of the post, the developer shared his situation by mentioning what he had accomplished which is that he uses “Python and Numpy to calculate the best fit polynomial of arbitrary degree” and “pass a list of x values, y values, and the degree of the polynomial” that he “want to fit (linear, quadratic, etc.)”. Then, the developer got into the details of his problem which is that he wants to “calculate r (coefficient of correlation) and r-squared(coefficient of determination)”, but his function does not work for polynomials with degrees greater than 1. From what we see so far, the description of the problem is concise and specific but still touches on the background of the question. In between the question, the developer demonstrated his efforts before asking the question that he used Excel to test and compare the result of his program which fulfilled Raymond’s precept of “try to find an answer by inspection or experimentation”. Through demonstrating his effort before asking the question, he explained further the symptom of the question that after using Excel's best-fit trendline capability to test the result, he knows that he is “calculating r-squared correctly for linear best-fit (degree equals 1)”. Lastly, the developer provided his source code and presented his source code in an “accessible, standard format” in the post in which other developers can copy the source code to test the result and manipulate the code. Thus, this is a great example of asking a smart question.
In addition, a smart question will more likely get a more helpful and detailed answer which is the case here. The accepted answer to this question provided reference documentation and websites for the questioner such as the “numpy.polyfit documentation”). The respondent also provides an equation to the question like “E(y|x) = p_d * x**d + p_{d-1} * x **(d-1) + ... + p_1 * x + p_0" as well as two blocks of codes for questioner to examine. Furthermore, the question was answered on the same day (May 21), 5 hours after the question was posted. Hence, asking a question in such a smart way will most likely lead to both efficient and effective help.

For more details visit [good example](https://stackoverflow.com/questions/893657/how-do-i-calculate-r-squared-using-python-and-numpy?rq=1).


## The Way to get an Unhelpful Answer, or No Answer at All.

On the other hand, let’s take a look at a bad example of asking a question. First, the headline of the question is “How od I get a collision detection” which contains a typo. Then, the first sentence of the question is “so basically i want to make collision detection code using Turtle Python between a good_char and the player” which is not grammatically correct with the use of “so” and the letter i is not capitalized. Also, “collision detection code” and “a good_char and the player” are very vague and confusing words. In addition, the questioner did not give further details on what these terms mean, but the questioner just continued with a broad question: “How could I do this?”. The questioner finished his post with “I tried copying and pasting other code blocks i found form other answers but none of them worked. I am a beginner.” This is not the way to demonstrate the effort of the questioner’s research on the topic; rather it shows the questioner simply wants to take other people’s works for granted instead of being interested in the topic. Although the questioner provided his code, the code is very unorganized that has a “print("Hello.")” as the first line which is before the three imported packages, and the comments of the code are all noted “# STAGE 2: ” rather than in an ordered format. Thus, this question got 0 answers and people marked it as an unclear question.

For more details visit [bad example](https://stackoverflow.com/questions/73642603/how-od-i-get-a-collision-detection).


## Conclusion

In summary, it is essential to develop the ability to ask smart questions, especially for software engineers, because it is the best way to get a rapid, responsive, and helpful answer. On another hand, the path of asking questions in a bad manner such as being very vague about the question, writing with many grammatical errors, being impolite, and trying to let others do your homework for you, is not the method to get adequate help from other people. Although the process can be time-consuming, putting the effort into research before asking the question and generating smart questions is the best way to get the most benefits in our journey of software engineering.


References

Raymond, E. S., & Moen, R. (2014, May 21). How To Ask Questions The Smart Way. www.catb.org. [http://www.catb.org/esr/faqs/smart-questions.html](http://www.catb.org/esr/faqs/smart-questions.html) 
