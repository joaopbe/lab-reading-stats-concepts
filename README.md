<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Lab | Reading About Statistic Concepts

## Introduction

In the future, you will need to understand deep statistical concepts by reading technical articles. As a training for that, it is interesting to start from here. Also, as we have limited time, this is a way to have some self guided learning to understand everything better and have a wider knowledge.

This week you will find some questions here that you will need to answer by documentating yourself. So you will do a different PR for each question (you are meant to answer the questions in different days). Don't hesitate to write as many text as you need and push images if you need them.

Remember for this lab: there is a right answer. But there is no perfect way to explain it (except for in a mathematical way, but this is another story).

## Challenges

### Challenge 1: What is the difference between expected value and mean?

In the context of discrete random variables expected value is the probability-weighted average of all its possible values, i.e . the sum of each possible value multipied by it´s probability.

If it´s a continuous random variable it´s the integral of the variable times the  pdf over the whole range.

The mean is, by definition exactly that when we are discussing random variables, so the concepts are equivalent.


### Challenge 2: What is the "problem" in science with p-values?

They are used erroneously many times, with the result the of the test being considered as a binary assumption of
success or insuccess. These analysis fail to take into account the true nature of the P value testing Any analysis should always take into account the assumptions of the statistical study undertaken, the p value & confidence intervals and the level of significance defined. The rejecting/acceptance of the Null Hip has always
to be perceived as being done to the significance level defined and not as a deterministic written in stone
conclusion.

In essence, the problem is one of "stretching" sometimes for the benefit of a conclusion, sometimes for ignorance, the mathematical concepts underlying the analysis.


### Challenge 3: Applying testing to a specific case: A/B testing.
A/B testing is a widely used tool to understand differences between two samples. It is a way to measure the impact of something we did:
* A marketing campaign.
* A new feature in our application.
* A new design in our application.
* A different flow in the User Experience flow.

To do this, is very important first to design our experiment.
* We need to know how we are measuring the impact. If people has the behaviour we want with this new implementation.
* We choose a control group (people who doesn't have/see the new change) and the group which will see the new change.
* We think about how much data do we need.
* We measure the difference between them.

One example:
Our application has a lot of mini-games. We want people to reach the games that we think are the best but the behaviour is not the expected, they don't reach them.

So we call a designer and after a lot of work he shows us a new design for our application: we will add a botton specific for that kinf of games inviting the users to click on it:

*Click here to discover cool games!*

We think it will work but can we be sure? So instead of implementing this new botton for all users, we implement it for 10% and we compare the results with the users that didn't have it. Is there a significant difference? Is our botton working?

Read more about A/B testing with a couple of examples:

[Another example about Netflix here](http://select.video/artwork4)

[What happened to Basecamp](http://millions.social/tested7)

[An example with Python](http://math.social/tested3)

[A cool general explanation](http://arts.show/tested7)

So, take one single example in the articles you just read, which specific test/s would you apply? (We want you just to do a draft and think a little bit how to apply the tests you already know in this case)

## Deliverables
You need to submit a markdown file with the answers to the questions above. You can create a new `.md` file or directly edit the `README.md`.

## Submission
Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.
