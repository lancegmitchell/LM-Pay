# LM-Pay
Solutions Consultant assignment - pay and refund app for android.

Task: Build an Android application that has the following functionality:

A Textfield to enter an amount
A Button “Pay" to make payment
A Button “Refund” to refund the last transaction



COMMENTS

Having followed the instrutions, to the letter, for the integration of the Payworks SDK and Pay Button, I encountered many compile errors. Some of these were to do with the bugs in the latest version of Android Studio (3.4.1), which I resolved after much research in online newsgroups and bulletin boards. Others were to do with missing expected classes in the Payworks downloads. I started to manually create the missing classes in my MainActivity file, but I could have spent days trying to resolve these exceptions and would probably have missed some of the intended funtionality. I would have liked to work with a Payworks developer to get these sorted out. 

Eventually, I decided to build a front end application which simulated the required payments and refunds against an initial, hard-coded balance balance of £500.00. The application accepts an amount to be either refunded to the account or paid in to the account. The action can be repeated against the new balance.

I have tested (just UAT) the app on my own phone: a Motorola Z2 Play.
