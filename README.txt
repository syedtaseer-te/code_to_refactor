questions
Q1. Your thoughts about the code. What makes it amazing code. Or what makes it ok code. Or what makes it terrible code. How would you have done it. Thoughts on formatting. Logic..
1. Booking module is associated with many other repositories so some code can be shifted to their associated other repositories.
2. There can be more use of events to make methods more specific and generic.
3. BookingRepository have extra stuff which is against its conceptual usage, e.g. emails shouldn't sent from repository. It should be concerned only to access data sources
4. Response messages are not dynamic and linguistic approach is ignored. This approach is not good for manipulation of language and messages.
5. Laravel validation is not used for validations which results in many conditional statements making code junk.
6. There seems very specific methods that results in repetition. Methods should be generic so that they can be reusable.
7. The methods are too dense so it is difficult to understand, manipulate and expand.
8. There should be one coding standard through out the files, e.g. some variables are declared as camelcase and some are with underscore.

Q2. Refactor it if you feel it needs formatting. The more love you put into it. The easier for us to asses.
I have done much refactoring in given time and tried to rebase structure on proper logical flow.