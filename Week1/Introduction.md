# Introduction

#### 기계학습이란? 


> 컴퓨터가 명시적(explicit) 프로그램이 없어도 스스로 학습할 수 있는 능력을 연구하는 학문 분야 - Arthur Samuel

위의 정의는 오래된 느낌, Tom Mitchell의 정의가 조금 더 가까움
> A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P,
>  if its performance at tasks in T, as measured by P, improves with experience E. - Tom Mitchell

Tom Mitchell은 Well-posed Learning Probelem 관점에서 정의. 컴퓨터가 일정수준(P)를 가지고 어떤 작업(T)을 수행한다고 가정했을때,
경험(E)가 증가함에 따라 수행 능력(P)가 향상될 수 있다. 

#### Example
Playing Checkers.
E = the experience of playing many games of checkers

T = the task of playing checkers.

P = the probability that the program will win the next game.


Suppose your email program watches which emails you do or do not mark as spam, and based on that learns how to better filter spam. What is the task T in this setting ?

1. Classifying emails as spam or not spam. - T
2. Watching yhou label emails as spam or not spam. - E
3. The number (or fraction) of emails correctly classified as spam/not spam. - P(분류된 메일의 비율)
4. None of the above - this is not a machine learning program.


#### 배울 알고리즘

지도학습(Supervised Learning) / 비지도학습(Unsupervised Learning) / 강화학습(Reinforcement Learning) /추천 시스템(Recommender Systems)
