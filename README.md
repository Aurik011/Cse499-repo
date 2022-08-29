## DEMO README
## BACKUPS


<html>
<head>
    Health Chatbot Application for Women and Adolescents
</head>


<body>
    Health Chatbot Application for Women and Adolescents

    Abstract
We’ve carried out a proposal to design a chatbot specifically for the
people of Bangladesh that answers questions related to different health
aspects ranging from children, adolescence, women’s health issues as well
as questions that are considered taboo in our social system. We want to
demonstrate how our chatbot can help solve small health issues that are
solvable via a few information, social hysteria and taboo related superstitions and provide necessary emergency facility if needed in desperate
situations like suicide

List of Acronyms

Below are all the acronyms used in this paper:
AI – Artificial Intelligence
ML - Machine Learning
NLP - Natural Language Processing
BERT - Bidirectional Encoder Representations from Transformers
DistilBERT – Distil Bidirectional Encoder Representations from Transformers

12 FREQUENTLY ASKED QUESTIONS
• Does the chatbot have multiple languages? Answer: As of now, we’re
not supporting multiple language features, we’re implementing English as
main language and afterwards we’re targeting to add Bengali.
• Does the chatbot provide feedback options? Answer: Yes, on settings
there’s an option called “provide feedback”
• What benefits do you think will have with this Bengali chatbot app?
Answer: We’ve created this chatbot app specifically for the people of
Bangladesh in mind. We hope to resolve some of the misconceptions as
well as superstitions that have been created for many decades among the
youths of this country.
• Do you have an app on the play store or the app store as of now? Answer:
No we don’t. But we’re planning to monetize this app through either the
play store or the app store or both if time and resources allow us to do so.

A Appendix
Contents
1 Introduction 1

9

2 Background and Significance 1
3 DISCUSSED SECTIONS FOR PURPOSES AND UPDATED
PROPOSALS 2
4 Doctor information related queries 3
5 Notification System 3
6 Method and Design 3
7 Features of NLP we’re using 4
7.1 Decreased latency . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
7.2 Reduced cost . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
7.3 Improving chatbot capabilities . . . . . . . . . . . . . . . . . . . 5
7.4 Tokenization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
7.5 Normalization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
7.6 Recognizing Entities . . . . . . . . . . . . . . . . . . . . . . . . . 5
7.7 Dependency Parsing . . . . . . . . . . . . . . . . . . . . . . . . . 5
7.8 Generation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
8 Implementation 5
9 User Interface Design 6
10 LIMITATIONS 6
11 KNOWN BUGS AND SOLVING MECHANISMS: 7
11.1 Bugs Identified: . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
11.2 Bugs solved . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8
11.3 Bugs NOT YET solved: . . . . . . . . . . . . . . . . . . . . . . . 8
12 FREQUENTLY ASKED QUESTIONS 8
13 Conclusion 8
14 Reference 9
15 A Appendix 9


</body>
</html>

## BACKGROUND AND SIGNIFICANCE(updated)
In our country Bangladesh, we don’t have many chatbots to look forward to re-
garding health related issues, be it for women, children or adolescents. We have

many simple chatbots for e-commerce websites as well as telecom companies
but not for our health issues. The ones that are available are either with limited
functionality or have problems like lack of updates and app crashes.There is
also no support for Bengali language as the datasets are non-existent as of 18

November, 2021. We have set up a team of enthusiasts and our project will fo-
cus on common and uncommon mental health/depression, women’s health, and

taboo related. Sometimes teenagers face reproductive problems and can not
express their concerns and go to search engines like Google, Bing, Duckduckgo
etc. We have understood that if we could find a platform that suits Bangladesh,
we could Provide these children and teenagers with their health problems. The
alternative is that these teenagers could find wrong information on the internet
and these could put them into serious health risks, as we’ve seen in the past in
many underdeveloped and developing countries.
As many of us suffer from these kinds of problems, there is actually no one
to talk about it. Many people don’t like to hear other people’s problems as their
own life is full of problems already. So our aim is to create something so people
can open themselves instead of keeping it in mind.
To implement this project, we would like to apply NLP (Natural Language
Processing). We can use term frequency and document frequency to understand
how often a word is used or how important a word is to a document. Like if any

1

user just repeating words related to suicide/depression, then chatbot will detect
that and turn the conversation in a way that the user can express his mind in
a more specific way and get immediate help. We used Normalization processes
to check spelling of different user inputs. Recognizing Entities can help us to
find out which topic. It can be a year such as 2021, a person’s name such as
Tahmid, Noshin, Anjum, Ahnaf, Aurik etc.
Our aim is to make this chatbot as interactive as possible. That’s why we
gave both options of either voice input question answering system or type input
system.
