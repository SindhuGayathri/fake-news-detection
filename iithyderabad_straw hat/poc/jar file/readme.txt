



click on the train "button" and give the training data(updated_data_set.txt) set as input
Now the training is completed,we will see two centroids(true,fake)
Now click on the testing button to give test dataset(test_data_set.txt) as input.

the output will be shown 
<Origin_of_news,by_whom,context,about_whom,context,sender,reciever,topic,timestamp>:TruthValue(Fake or True) 

Now click on the bot Detection and select the input file as BotTest.txt
The out will be shown 
A particular topic is shared between people as shown(sender and reciever)
Analysis of timestamps detects the originator(may be bot)
Test for all the topics(i.e change the input record in bot test.txt) and the one having the largest count of sender-->reciever pairs is detected as bot. 