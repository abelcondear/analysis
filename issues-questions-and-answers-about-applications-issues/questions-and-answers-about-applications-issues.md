## Questions and answers about Applications Issues

### When an API starts returning errors in production, how do you usually figure out what is wrong and proceed to fix it? 

I look for more information about the error description that the App is throwing, and then I refactor the code to see if I can fix the error. 

In case, I could not, I would try to evaluate if that specific functionality is highly important to work at that moment. And if that functionality can be only discarded by now, then I commented it or removed it temporally. 

### If a screen is loading slowly, what simple steps would you take to understand the cause and improve it? 

I would try to review if the “loading slowly” is related to the hardware, where the app is installed. Or I would try to review if the "loading slowly" is related to the code or algorithm that the app is using to work when it is being used. 

Then, in case, it has to do with app coding, then I would try to use other similar libraries or just load the libraries dynamically at the moment that the app needs to use them.

Besides, I would try to short the algorithms or routines, the app is using to make the “screen loading” much faster.

### You need to add a new field to a table that is actively being used. How do you safely make this change without affecting and stopping the app running? 

I would create a copy of that table and add the adjustments I need to apply. Then, I would rename and backup the original table and copy the records from the original table to the new one (with the last adjustments) and rename it using the original table name. 

This should be done in a moment when the app is not being highly used. I would perform this database operation in the weekend or in the early morning. 

By the way, this operation should not last too much time. Unless, the table holds too many records.

### A bug is blocking users from performing an action on the app. What is your step-by-step approach to diagnosing it and delivering a stable fix? 

I follow these steps:

1. Understand bug 
2. Analyze bug 
3. Evaluate it in order to confirm if that bug is not a real bug 
4. Refactor code to fix bug 
5. Test app on local or stage environment 
6. Publish app 
7. Re-do steps again until fixing the bug
