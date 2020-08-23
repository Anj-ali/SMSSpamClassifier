# SMSSpamClassifier
We all are bothered of unnecessary spam messages in our inbox. It would be great if me can classify our messages according to spam no spam according to our needs. Here is a simple attempt to do so.

Here i used Naive Classifier to classify to classify the messages as spam or not spam.Lets first have a look at what we have for dataset.
I have used famous dataset named SMS Spam Collection Data Set for sms spam classification. 
You can find the dataset here - https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

Lets have a look for the words that are present in spam messages.

![spam_cloud](https://user-images.githubusercontent.com/44197413/90971667-d3ed7680-e52f-11ea-8db8-245c83fa0de9.PNG)


Lets have a look for the words that are present in non spam messages.

![nonspam_cloud](https://user-images.githubusercontent.com/44197413/90971711-36df0d80-e530-11ea-9f36-c971f1e4f7ac.PNG)


Let have the look what we have as data:

![data](https://user-images.githubusercontent.com/44197413/90971745-99380e00-e530-11ea-81aa-b3d25224fc07.PNG)


As we can see that the data is completely baised toward non spam messages but reducing non spam data to keep it balanced will be the wastage of data. So we will keep the data in its original form.

Let's have a glance of top messages in the dataset.

![smssample](https://user-images.githubusercontent.com/44197413/90971776-d6040500-e530-11ea-9a89-d4ee6a0553f2.PNG)


For the Naive Bayes algorithm i implemented this naive algorithm from scartch and got a really good accuracy of 97%.
Below is the glimpse of various accuracy paramter obtained on the algorithm.

![result](https://user-images.githubusercontent.com/44197413/90971769-c7b5e900-e530-11ea-8b5f-f34df9dc955b.PNG)
