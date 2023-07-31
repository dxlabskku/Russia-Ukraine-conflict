# Russia-Ukraine-conflict

## Introduction
On Feb 24, 2022, the Russia-Ukraine conflict broke out, and the United States government decided to aid Ukraine. However, there were different stances toward aid for Ukraine in the United States discourse depending on political orientation. 
Thus, we tried to explore that state of affairs through news media and addressed the research question below
>RQ.1: Do the articles written by the news media on the issue of the
The Russia-Ukraine conflict contains a political orientation of its own.
>
>RQ.2: Is it feasible to explore it in a computational approach?

Additionally, we conducted an extra experiment, building a classification model and classifying the United States government's official documents regarding the Russia-Ukraine issue.

---------------------------------------

## Data
We collected 2 types of data, 8,104 Media data, which are articles produced by news media, and 291 Government data released by 4 different government departments.

---------------------------------------

## Experiment and Result
Exp-1) Comparative process between conservative and progressive articles 
 - we conducted sentiment analysis using LIWC
 - we selected 7 categories with considering the political orientation
> result : conservative(family, positive emotion), progressive(past focus, anxiety, affect, negative emotion, future focus)
![bar_graph](https://github.com/dxlabskku/Russia-Ukraine-conflict/assets/122080807/f9a43448-0bce-48fa-9085-b0a0864eab05)

Exp-2) Classifying Government data
 - we compare 2 models: XGB, BERT
 - BERT achieved better performance in the validation step
 - finally, we classified with the BERT model
> result : conservative: 64 / progressive: 227
