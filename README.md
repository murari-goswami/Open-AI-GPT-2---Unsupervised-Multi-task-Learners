## Open-AI-GPT-2---Unsupervised-Multi-task-Learners




Read the blog post [here](https://soumyadip1995.blogspot.com/2019/02/language-models-unsupervised-multi-task.html)





A language model is a machine learning model that is trained to predict the next word given an input context. As such, a model can generate text by generating one word at a time. These predictions can even, to some extent, be constrained by human-provided input to control what the model writes about. Due to their modeling power, large language models have the potential to generate textual output that is indistinguishable from human-written text to a non-expert reader.

Language models achieve this with incredibly accurate distributional estimates of what words may follow in a given context. If a generation system uses a language model and predicts a very likely next words, the generation will look similar to what word a human would have picked in similar situation, despite not having much knowledge about the context itself. This opens up paths for malicious actors to use these tools to generate fake reviews, comments or news articles to influence the public opinion.

To prevent this from happening, we need to develop forensic techniques to detect automatically generated text. We make the assumption that computer generated text fools humans by sticking to the most likely words at each position, a trick that fools humans. In contrast, natural writing actually more frequently selects unpredictable words that make sense to the domain. That means that we can detect whether a text actually looks too likely to be from a human writer!

represents a visually forensic tool to detect text that was automatically generated from large language models.
