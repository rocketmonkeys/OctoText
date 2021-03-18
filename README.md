# Octotext
<img width="326" alt="OctoText" src="https://user-images.githubusercontent.com/44931130/111055804-8858d680-8447-11eb-9d43-c1e3daf8077f.PNG">

OctoText will notify you via text on common printer events. The current list of events are:
    * File uploaded
    * Print started
    * Print done
    * Timelapse done
    * Error (unrecoverable)

There is also a test message that is used to verify your settings

## Setup

Install via the bundled [Plugin Manager](https://docs.octoprint.org/en/master/bundledplugins/pluginmanager.html)
or manually using this URL:

    https://github.com/berrystephenw/Octotext/archive/master.zip

The plugin needs no special installation.

## Configuration

In order to configure OctoText you have to use an email account to send the messages from. 
I use the free email service from Microsoft - Outlook.com. I created the email address octotext@outlook.com for the development of the plugin
and it works well. You should NOT use an email account that you care about - the plugin is not secure and while that will change in the future 
right now it is exposed to anyone that knows what to look for. 

Once you have the email account you want to use, you will need the SMTP server of the account. For Outlook you can find that under 
Settings->sync settings:

<img width="735" alt="Outlook settings" src="https://user-images.githubusercontent.com/44931130/111056048-df5fab00-8449-11eb-8aa8-4807493750d9.png">

In addition you will also need to find out the email address of the text service of your provider. For US carriers the list below will
cover most users:

<img width="368" alt="SMS gateway" src="https://user-images.githubusercontent.com/44931130/111055919-a7a43380-8448-11eb-836d-40a9706d7d51.png">

This table was taken from: https://en.wikipedia.org/wiki/SMS_gateway please refer to Wikipedia for more up to date information

Once you have gathered all this information you will need to enter it into the settings page on OctoText. The Test Icon on the OctoPrint front page 
also doubles as a test message to check your settings. Just press it once and wait 30 seconds or so and you should see a text (if everything is set correctly)
on your phone:

<img width="326" alt="Screenshot 2021-03-13 215826" src="https://user-images.githubusercontent.com/44931130/111055811-9c043d00-8447-11eb-87b8-fdac8dd1dfff.png">

# Problems?
If you are having trouble with your setup, you can post on the discussion board and I'll get to your question as soon as I can. Please include a copy of the octoprint log from the logging menu of octoprint. https://github.com/berrystephenw/OctoText/discussions
# Credits
Gina Häußge https://github.com/foosel for creating Octoprint and the plugin Pushbullet from which some of this plugin is developed from. 
jneilliii https://github.com/jneilliii for helping me get past some sticky problems in development 
Charlie Powell https://github.com/cp2004 for answering even the dumbest questions on discord.
