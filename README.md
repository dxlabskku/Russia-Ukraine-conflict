# Russia-Ukraine-conflict

## Introduction
On Feb 24, 2022, the Russia-Ukraine conflict broke out, and the U.S. government decided to aid Ukraine. However, there were different stances toward aid for Ukraine in U.S. discourse depending on political orientation. 
Traditionally, media engage in continuous discourse and reflect their positions. Subsequently, in this regard, we set up a following research question.
> RQ.1 : an we verify the political stance in media outlets’ articles?

Additionally, analyzing the positions of the media as well as the U.S. government, particularly relevant government departments, provides a broad perspective on that issue. Therefore, we have the next research question as follows.

> RQ.2 : Which stance does the U.S. government have?
---------------------------------------

## Data
We collected 2types of data. those are Media data, which are articles produced by media outlets, and Government data released by 4 different government departments.

![image](https://github.com/dxlabskku/Russia-Ukraine-conflict/assets/122080807/b8b96356-f638-4803-913f-29cda8f16ada)


---------------------------------------

## Experiment
>To find out RQ.1, we classified articles by media according to political orientation and analyzed them through LIWC. LIWC selected 5 features related to this issue and conducted a series of t-tests for each feature to verify whether there was a difference between progressive and conservative media. After that, the average values ​​were compared to find out what meaning was implied.
The result of the t-test revealed that there were differences between articles from conservative and progressive media at a significance level of p < 0.01. Moreover, through the Affect feature, we confirmed that progressive media articles employ a more emotional tone in addressing the issue compared to conservative media articles. Specifically, we found that progressive media articles incorporate more
Negative Emotion, Anger, and Anxiety features compared to conservative media articles. Lastly, it was observed that conservative media articles tend to focus more on the security threat (Risk ) posed by the Russia-Ukraine conflict.

![image](https://github.com/dxlabskku/Russia-Ukraine-conflict/assets/122080807/d269a563-a631-4c7e-991b-619897470a7e)

>Through RQ.1, it was confirmed that there is a sentimental difference between articles produced by conservative and progressive media on the Russia-Ukraine issue. Therefore, the task of constructing a model through verified media data and inputting and classifying Government data was performed.
We used XGB and BERT models. To address the task using each model, XGB achieved an accuracy of 90.92%, while BERT outperformed with an accuracy of 98.37%. Based on the accuracy, we finally conducted a classifying Government data task with BERT model.

![image](https://github.com/dxlabskku/Russia-Ukraine-conflict/assets/122080807/b89b317b-7643-4b55-838b-25ee259ee5d8)

By classifying 64 instances as conservative and 227 instances as progressive, we confirmed that the policies and directions of the
Biden administration encompasses a notable progressive element

