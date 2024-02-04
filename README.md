# How to Create Predictions on Your Stream Using StreamerBot
Created by [WaffleSmacker](https://www.twitch.tv/wafflesmacker) Make sure to leave a follow for more future tips!
<br>
![Waffle_Logo](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/47f02801-7a5d-4c9f-a9b7-04bb6d9bd968)
<br>


## Introduction

:tired_face: **Tired of having to manually come up with predictions on the spot?**
Wish that you could just press a button or simply speak a command into your mic to create a prediction on stream?
By the end of this page you should be able to do so!
<br><br>

## Prerequisites

- [OBS](https://obsproject.com/)
- [Streamer.Bot](https://streamer.bot/)
- [Stream Deck (Optional)](https://www.elgato.com/us/en/p/stream-deck-mk2-black)
<br><br>

## Step-by-Step Guide

<br>

### Step 1: Import the code to Streamerbot

Open up streamer.bot and click the import button.
<br>
![Import Button](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/e7fb44a5-a6b9-4fff-a402-89cdd215bdcd)
<br><br>
:point_down::point_down::point_down:**Copy the text below and paste it into the import string section.** :point_down::point_down::point_down:

```
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
```
<br><br>
Click OK to import the new actions, triggers and commands!
<br>
![Import Actions](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/411c00c1-e4a6-4600-bc98-45a70daf286a)


<br><br>


### Step 2: Enable the test commands

Whenever new commands are imported to streamerbot you will need to manually enable them.

Go to commands<br>
![Commands](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/c5c15d2d-2dc0-4f4b-974c-259756596358)

Go to the new commands, right click each one and enable them.

Before:<br>
![Enable Commands](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/2996e169-1798-4c93-ba58-226f06e9bffc)

After:<br>
![Enabled commands](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/02b189c8-3e50-49ae-8bcb-4eb415ac3e8e)


<br><br>


### Step 3: Try creating a prediction & resolving it

Use the "**!TestPredictionStart**" to simply set up a new prediction.

If everything was set up correctly you should notice in OBS that a prediction was created.<br>
![Prediction Created](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/6c538184-38ee-4939-87a3-7dd2333aa2bf)


Next, try to do "**!PredictionOutcome1**" to resolve the prediction!<br>
![Prediction Resolved](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/3b24ba6e-66fb-48bf-890e-dcd094ed4fe1)



If that all works, next I'll explain how to change the title, duration and outputs of the prediction.

<br><br>


### Step 4: Adjusting the prediction variables.

The code is set up to easily allow you to duplicate the action in order to create multiple different predictions.
If you want to change the title, duration and outputs, select the action and then expand the grouped folder.

Click on the action "**Prediction - Sample [Duplicate this]**" <br> 
![Import Actions](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/400ede57-2cae-4775-bbee-34599ebcc24a)


You will see that there are 4 args being set up. (Make sure to read the green comments!)
<br><br>

![Edit Prediction Settings](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/fceca46d-4c77-40a8-a217-2cb76db8ea2c)


Feel free to:
- Change the title (note: due to twitch restrictions it can only be **45 characters long**)
- Change the duration (**in seconds**) to as long as you need it
- Change the outputs of the prediction
<br>

![After changes](https://github.com/WaffleSmacker/WaffleSmacker/assets/131427794/d1338974-7353-4580-99a3-d7b7eaefbf39)




<br><br>


## Tips and Tricks

Now that you have predictions set up, why not get fancy?

Instead of just using chat commands, you can set up different types of filters!

You can also change the commands to be easier/more relevant for your stream.

### Voice Activated Commands
- Go to the voice command tab on streamerbot and set up a new voice command.
- I suggest using something unique you won't say accidentally
- ex. "start the silly gamba!"
- Set up the voice command like so:
- Press ok to save the voice command and go back to your Prediction Action.
- Set up the voice command you just created as a Trigger
- Try saying the voice command to see if it works!
- The same can also be done to resolve gambas!  (I use "The believers have it" and "The doubters have it")



