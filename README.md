# LM-Pay
Solutions Consultant assignment - pay and refund app for android.

Instructions from Payworks

More specifically, we’d like you to build an Android application that has the following functionality:

A Textfield to enter an amount
A Button “Pay" to make payment
A Button “Refund” to refund the last transaction

Here are the steps you should take:
1) Make yourself familiar with coding for Android, https://developer.android.com/guide/index.html
2) Download and install the Android IDE, Android Studio https://developer.android.com/studio/index.html
3) Start a project within Android studio and add the UI items using the Interface Builder
4) Install the Payworks SDK within the project by following the instructions
here: http://www.payworks.mpymnt.com/node/143#android
5) Use the Payworks documentation to find the code needed for the “Pay” and “Refund” buttons
6) Create a Github Account (https://github.com/) and make your project available there

Don’t forget to test your app on your phone or with the Android simulator.
At the end, it should be possible for us to clone your Github repository, run your code and test it.
Please send us an email when you are done which includes the link to Github repository with your code.

COMMENTS

Having followed the instrutions, to the letter, for the integration of Payworks Pay Button, I encountered many compile errors. Some of these were to do with the bugs in the latest version of Android studio, which I resolved after much research in online newsgroups and bulletin boards. Others were to do with missing expeted classes in the Payworks downloads. I started to create the classes in my MainActivity file, but I could have spent days trying to resolve these exceptions. I would have liked to work with a Payworks developer to get these sorted out. 

Eventually, I decided to build a foront end application which simulated the required payments and refunds against an initial, hard-coded balance balance of £500.00. The application accepts an amount to be either refunded to the account or paid in to the account. The action can be repeated against the new balance.

I have tested (just UAT) the app on my own phone: a Motorola Z2 Play.
