# Bot Features Overview

	1.	Play Media (/play):
	•	Users can play audio or video by providing a YouTube link or search query.
	•	The bot uses youtube_dl to fetch the best audio stream from the given URL or search results.
	•	If the media is already playing, it gets added to a queue for later playback.
	
	2.	Automatic Queue Management:
	•	The bot manages a queue of media to be played after the current media ends.
	•	When the current media finishes, the bot automatically plays the next item in the queue without user intervention.
	•	If there are no items in the queue, the bot can suggest related content based on the last played item.
	
	3.	Crossfade Feature:
	•	When switching from the current media to the next item in the queue, the bot gradually lowers the volume of the current media before starting the next one, creating a smooth transition (crossfade).
	•	This feature enhances the listening experience by preventing abrupt audio changes.
	
	4.	Skip to Next Item (/next):
	•	Users can skip the current media and jump to the next item in the queue.
	•	If there are no items left in the queue, the bot continues playing the current media and notifies the user.
	
	5.	Stop Streaming (/end):
	•	The bot can stop streaming and leave the group call on command.
	•	This function resets the current playing track and clears the queue.
	
	6.	Current Playing Status (/current):
	•	Users can check what is currently playing, including the elapsed time and volume level.
	•	If nothing is playing, the bot notifies the user accordingly.
	
	7.	Shuffle Queue (/shuffle):
	•	Users can shuffle the order of items in the queue for a randomized playback experience.
	•	This adds variety to the listening experience.
	
	8.	Loop Current Track (/loop):
	•	This feature allows users to loop the currently playing track.
	•	When enabled, the current track will replay automatically after it finishes.
	
	9.	Loop Entire Queue (/loopqueue):
	•	Users can choose to loop the entire queue, causing the bot to restart the queue after all items have been played.
	•	This is useful for continuous playback of a selected set of media.
	
	10.	Set Volume (/setvolume):
	•	Users can adjust the volume level of the audio being played (between 0 and 100).
	•	The bot notifies the user of the current volume level and adjusts it accordingly.
	
	11.	Help Command (/help):
	•	Provides users with a list of available commands and their functionalities.
	•	This helps users understand how to interact with the bot effectively.
	
	12.	Greeting Command (/start):
	•	A friendly introduction to the bot, outlining its capabilities and guiding users on how to use it.

## Summary

These features collectively make the bot a powerful tool for streaming audio and video in Telegram group calls. The automatic queue management and crossfade functions particularly enhance the user experience by ensuring smooth transitions and continuous playback.

You don’t like a complicated bot for streaming? This is the right choice.

Powered by NTgCalls

~ available soon ~