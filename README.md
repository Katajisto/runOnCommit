# runOnCommit
A go program that runs a set of commands when a GitHub commit happens.

It's a simple way to keep your server version of the program updated with the github version, if you are a student and not doing anything very serious. I don't think it's very safe, but I use it in hobby projects so it doesn't matter that much. Please make some safeguards if you use this with anything that matters. Someone could just spam the webhook link and make your server run the commands constantly. Not nice :(
