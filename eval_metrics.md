# Chatbot Metrics:

## Papers on chatbot metrics:

- [Chatbot Evaluation and Comparison](https://www.researchgate.net/publication/348014085_Trends_Methods_in_Chatbot_Evaluation).

Radziwill and Benton, 2017
**ISO9214** concept of usability: “The effectiveness, efficiency and satisfaction with which specified users achieve specified goals in particular environments.” 

**Efficiency** is related to their performance towards their goal, be it robustness towards manipulation or unexpected input, effective function allocation, graceful degradation or avoiding inappropriate utterances.

**Effectiveness** can be separated into two sub-concepts.
- _functionality_ includes attributes such as accurate speech synthesis, accurately interpreting commands, linguistic accuracy, general ease of use and on-the-fly problem solving.
- _humanity_ has objectives pertaining to passing (or not) the Turing test, being transparent to inspection, including error for increased realism and being able to answer specific questions.

**Satisfaction** is divided into three different subgroups. 
- _affect_ covers providing greetings and conveying personality, giving conversational cues, providing emotional information (through tone, inflexion), showing warmth and authenticity, making tasks more enjoyable and interesting, or reading the mood.
- _ethics_ and _behaviour_ comprise the respect, inclusion and preservation of dignity, ethics and cultural knowledge of the users, protection and respect of privacy, non-deception, sensitivity to safety and social concerns, trustworthiness and awareness of trends and social context.
- _accessibility_ examines whether there is a response to social cues (or lack thereof), if the intent can be detected, or whether it can respond to more diverse needs.

Maroengsit’s et al., 2019
The first one, _Content Evaluation_, covers both automatic evaluation through means such as BLEU or ROUGE text summarisation methods, or expert evaluation when humans are required to do what scripts cannot do yet.
The second, _User Satisfaction_, focuses on methods that directly ask users what they think of their interaction with the chatbot. It is subdivided into _Turn Evaluation and Session Evaluation_ depending on whether the users are asked about their interaction after each question or only at the end.
The last category, _Functional Evaluation_, encompasses further other methods such as task-based evaluation that are popular with goal-oriented chatbots, usage statistics, and evaluation as a building block.

Jadeja and Varia, 2017 
The _User Perspective_, which measures user satisfaction, usability, etc.
The _Information Retrieval Perspective_, which measures, for example, the accuracy and speed of the answer to the user’s query.
The _Linguistic Perspective_, which measures whether the conversation scores well inquality, quantity, relation and manner.
The _AI Perspective_ on whether or not the AI can pass the Turing Test.


Jain et al., 2018
_Quantitative data_ (such as total interaction time, message count and number of interactive elements) during the discussions. 
Semi-structured interviews for users, from which they spotlit four elements as follows: _functionality, conversational intelligence, chatbot personality and chatbot interface_.


Venkatesh et al., 2018
reject the Turing Test as an appropriate way of evaluating chatbots
6 metrics: _conversational user experience, engagement, coherence, domain coverage, conversational depth and topical diversity/conversational breadth_

**Effectiveness** corresponds to a more technical point of view, where the technique behind the functioning of the chatbot is the main point of the evaluation, and progress is made when the performance of the underlying algorithms is improved.
**Efficiency** relates more to the explicit goal of the chatbot, i.e., to whether or not the task the chatbot is made for is achieved.
**Satisfaction** evaluation usually represents a desire to evaluate user interest in the chatbot, or whether the interaction was agreeable, which is often part of the goal as well.

- [Evaluating Natural Language Understanding Services for Conversational Question Answering Systems](https://aclanthology.org/W17-5522/)

- [A Review of Evaluation Methods and Metrics for Conversational Agents](https://arxiv.org/pdf/1709.04409.pdf).

Jiwei Li, Will Monroe, Alan Ritter, Michel Galley, Jianfeng Gao, and Dan Jurafsky. 2016. Deep Reinforcement Learning for Dialogue  Generation. In Proceedings of Empirical Methods in Natural Language Processing (EMNLP)
**Turn-level** rewards:
• Coherence: semantic similarity between consecutive turns,
• Information flow: semantic dissimilarity between utterances of the same speaker,
• Ease of answering: negative log-likelihood of responding to an utterance with a dull response (as defined by a blacklist).

Zhou Yu, Ziyu Xu, Alan W. Black, and Alexander I. Rudnicky. 2016. Strategy and Policy Learning for Non-Task-Oriented Conversational Systems. In Proceedings of the SIGDIAL.
**System-level** rewards: 
• Conversational depth: the number of consecutive turns belonging to the same topic,
• Lexical diversity/information gain: the number of unique words that are introduced into the conversation from both the system and the user,
• Overall dialogue length.

### Response time:
The time it takes for a chatbot to respond to a user's message. This is an important metric to ensure that the chatbot is responding quickly to users.

### Conversation duration:
The length of time a conversation lasts between a user and a chatbot. This metric can help evaluate user engagement.

### Task success rate:
The percentage of tasks that a chatbot can successfully complete. This is an important metric to evaluate the overall performance of the chatbot.

### User satisfaction:
The overall satisfaction of users with the chatbot. This metric can be measured using surveys or user feedback.


# Dialogue System Evaluation:

## Papers on dialogue system evaluation:

- [A Survey of Evaluation Techniques for Dialogue Systems](https://link.springer.com/article/10.1007/s10462-020-09866-x)
- [A Comprehensive Assessment of Dialog Evaluation Metric](https://arxiv.org/abs/2106.03706)

###  Task completion rate:
The percentage of tasks a dialogue system can successfully complete. This metric is important for evaluating the performance of the system in accomplishing specific tasks.

### Dialogue efficiency:
The speed and accuracy of the dialogue system in accomplishing a task. This metric can help evaluate the system's overall performance.

### User satisfaction:
The overall satisfaction of users with the dialogue system. This metric can be measured using surveys or user feedback.

### Diversity:
The ability of a dialogue system to generate diverse responses to user queries.

## Automatic Metrics:
-[FineD-Eval: Fine-grained Automatic Dialogue-Level Evaluation](https://arxiv.org/abs/2210.13832)


# Assistant Evaluation:

### Accuracy:
This metric measures the ability of the AI assistant to understand and correctly respond to user queries. It is usually measured as the percentage of correctly answered queries out of all the queries asked.

### Response Time:
This metric measures how quickly the AI assistant can respond to user queries. The response time should be fast enough to ensure that users do not have to wait too long for a response.

### User Satisfaction:
This metric measures how satisfied users are with the AI assistant's responses. User satisfaction can be measured through surveys or by analyzing user feedback.

### Error Rate:
This metric measures the number of errors made by the AI assistant. Errors can include misunderstandings of user queries, incorrect responses, or failure to respond at all.

### Task Completion Rate:
This metric measures the percentage of tasks that the AI assistant is able to complete successfully. For example, if a user asks the AI assistant to set a reminder, the task completion rate measures the percentage of times the AI assistant is able to successfully set the reminder.

### Robustness:
This metric measures how well the AI assistant performs under different conditions, such as variations in user accents, noisy environments, or changes in context.

### Engagement: 
This metric measures how often users engage with the AI assistant and how long they stay engaged. This can be measured through metrics such as session duration and frequency of usage.






