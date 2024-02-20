# The-Gillett-commercial-toxic-masculinity
Sentiment analysis of YouTube comments about the slogan “The best men can get”.

## Introduction
In 2019, Gillette ventured into the heart of social discourse with a commercial that reimagined its iconic slogan, “The Best a Man Can Get,” through a contemporary lens critically examining toxic masculinity. This initiative was not merely an advertising campaign but a cultural statement, aiming to spark conversation on the role of men in society amidst the burgeoning #MeToo movement.

The commercial, which highlighted various forms of male behavior, including bullying, harassment, and the casual dismissal of sexist actions, was met with a maelstrom of reactions across the globe. Public response was vividly captured in the digital arena, particularly in YouTube comments, offering a rich dataset for sentiment analysis.

This work delves into a comprehensive sentiment analysis of YouTube comments related to the Gillette slogan “The Best Men Can Get,” aiming to uncover the public’s reception, emotions, and viewpoints stirred by the commercial.

Also, it seeks to understand the broader societal implications of Gillette’s attempt to address toxic masculinity and the diverse perspectives on what constitutes the best men can be in today’s world.

## Methodology

About 25,674 Comments were scraped from YouTube at https://youtu.be/UYaY2Kb_PKI?si=XaqSRWqxLQ79dt8J using Python through the YouTube Data API.

Python NLTK was used for preprocessing the text data, including tokenization, stemming or lemmatization, and the removal of stop words.

10,000 comments of the cleaned data were sampled with a simple random sampling method and used for the text analytics to avoid overcrowding, especially for the word cloud.

## Analysis of the Results

### World Cloud

![image](https://github.com/Fkuukyee/The-Gillett-commercial-toxic-masculinity/assets/147086232/50451c43-ee5f-42ee-a29f-8bf6cda05bf8)


From the word cloud visualization above, the prominent words were women, men, product, toxic, and more, which gives an indication that the comments were mostly about gender.

### Polarity sentiment analysis

![image](https://github.com/Fkuukyee/The-Gillett-commercial-toxic-masculinity/assets/147086232/8b87488f-742b-4660-a353-0554da925904)

Polarity sentiment analysis is a powerful tool for understanding public opinion and can be applied across various domains, from analyzing customer reviews to monitoring brand reputation and beyond.

The above pie chart reveals that about 41.8% of the comments had positive polarity, whereas about 23.4% were negative and the rest were neutral. This shows that the advertisement by Gillett was able to win the hearts and support of the majority of the people sampled, with only a few expressing negative sentiments about the slogan “The best men can get.”

### Subjectivity sentiment analysis

![image](https://github.com/Fkuukyee/The-Gillett-commercial-toxic-masculinity/assets/147086232/5b16dba7-6ab6-41a9-a127-344b10689119)


Subjectivity sentiment analysis is a branch of natural language processing (NLP) focused on identifying whether a given text is objective (factual) or subjective (personal opinion or emotion-based).

The results of the subjective sentiment analysis show that about 70% of the comments were personal opinion or emotion-based, and the others were fact-based comments. This confirms the fact that social issues such as gender always stir up people’s emotions.

## Conclusion

In conclusion, the sentiment analysis of YouTube comments regarding Gillette’s “The Best Men Can Get” commercial offers insightful reflections on societal attitudes toward toxic masculinity and gender roles. The analysis reveals a predominantly positive reception among viewers, with a significant portion expressing support for the message against toxic masculinity. This suggests that the commercial succeeded in resonating with a broad audience, sparking constructive dialogue on what it means to be a man in the contemporary context.

The predominance of subjective comments underscores the deeply personal and emotional nature of discussions surrounding gender issues. It highlights the commercial’s effectiveness in engaging viewers on a personal level, prompting them to reflect on and express their own experiences, beliefs, and emotions related to toxic masculinity and societal expectations of men.

However, the presence of negative sentiments and the diversity of opinions evident in the comments also point to the complexities and sensitivities surrounding discussions of gender roles and behaviors. This underscores the challenge of addressing such deeply entrenched societal issues through commercial campaigns.

Gillette’s venture into this contentious terrain demonstrates the potential of advertising to contribute to social discourse, beyond selling products. By leveraging its platform to address toxic masculinity, Gillette has not only sparked debate but also contributed to the ongoing societal shift towards more inclusive and reflective understandings of masculinity.

The analysis of public sentiment, as reflected in the YouTube comments, serves as a valuable barometer for gauging societal progress and resistance to confronting and redefining traditional gender norms.





