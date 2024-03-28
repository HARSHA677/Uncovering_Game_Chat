# Uncovering_Game_Chat

# Problem Statement:
To identify the topics discussed in the Discord chat from the Apex Legends game server using
LDA.
To analyze the sentiment of the chat messages using textblob and evaluate its accuracy
through Naive Bayes classifier.

# Objective:
We can use topic modeling to identify the main themes and topics being discussed in the
channel. This can help us understand the interests and preferences of the players and tailor our
content accordingly.
We can use clustering analysis to group similar messages together based on their content or
sentiment. This can help us identify sub-communities within the channel and understand the
different perspectives and opinions of players.
Overall, analyzing data from a gaming discussion channel in an Apex Legends server can
provide valuable insights into the behavior and preferences of human players.
By understanding these patterns, we can improve the gaming experience for players and create
more engaging content that resonates with our target audience.

# About the data:
Source: Discord Server
Game: Apex legend
Channel:Game_discussion

# Steps to extract data from discord channels:

1) Join the discord server
2) Collect your user token
3) Insert the token in the discord extracter (https://github.com/Tyrrrz/DiscordChatExporter
(https://github.com/Tyrrrz/DiscordChatExporter))
4) Select the channel we wish to extract the data from. In this case, we have selectedthe
gaming discxussion channel from the Apex legends server.
5) Specify the type of file we want to extract the data into. Csv in this case

# Dataset Description
Message ID: This field is a unique identifier for each message sent in the channel. It is
important for identifying and tracking specific messages in the channel, and can be used to
group messages by topic or conversation. Message IDs can also be used to analyze message
length, frequency, and patterns over time.

Author: This field represents the username or display name of the user who sent the message.
It is important for identifying individual users and their messaging patterns within the channel,
and can be used to analyze the engagement level of specific users, their posting frequency, and
the sentiment of their messages.

Content: This field includes the text content of the message, including any links, emojis, or
other media. It is important for understanding the topics and themes of the channel, and can be
used to identify common keywords or topics, as well as the sentiment of the conversation.
Analyzing the length, tone, and content of messages can provide insights into user behavior
and engagement.

Timestamp: This field represents the date and time when the message was sent. It is important
for analyzing message frequency, patterns, and trends over time. By grouping messages by
time intervals (e.g. daily, weekly, monthly), analysts can identify peak activity times and patterns
in the conversation, as well as track the evolution of topics and themes over time.

# Conclusion

Based on the topic modeling and clustering analysis, it seems that the conversations in the
Apex Legends game chat server are diverse and cover a range of topics. The topics identified
include frustration and negative experiences with the game, discussing gameplay mechanics
and strategies, having fun while playing the game, discussing the game in general, and
expressing emotions and reactions while playing the game.
Additionally, the clustering analysis revealed three distinct clusters, with one related to casual
conversation or socializing, one related to negative sentiment or feedback related to the game,
and one related to positive sentiment or feedback related to the game.
Overall, the analysis suggests that players in the Apex Legends game chat server engage in a
variety of conversations and discussions related to the game, with both positive and negative
sentiment expressed. These insights could be useful for game developers to understand player
experiences and improve the game accordingly.
