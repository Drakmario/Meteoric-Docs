> Change Log
>
>> Change Log displays every new in the recent update of Meteoric.

⚠ The logs can change at anytime, so check this page every so offend.

# Change log

## Version 3.0.0

### Added

#### New Categories 

* Image Mainpulation
* Configuration
* Music

#### Fun Category 

* Pokemon - See info about a pokemon

#### Image Mainpulation

* Triggered - Make yourself or someone triggered
* Wanted - Make yourself or someone wanted
* Slap - Slap a user
* Bed - Makes a meme about a monster under the bed
* Kiss -  Kiss another user
* Trash - Look at this piece of trash
* Invert - Inverts the image | Reverses the colors

#### Moderation

* Nickname - Add a name/change the name of a user
* Reset - Reset the name of a user
* Createchannel - Creates a channel
* Deletechannel - Deletes a channel
* Nukechannel - Nukes the channel and creates a copy of it

#### Configuration

* Setprefix - Set/change Meteoric prefix for the server
* Setchatbot - Set/change the channel for Meteoric chatbot api to be set to (More information below)
* Setmodlogs - Set/change the channel for moderation command usages to be logged to (More information below)

#### Music

* Play - Play a song
* Queue - View the songs in the queue
* Loop - Loop the current song/queue or turn off the loop
* Skip - Skip the current song
* Stop - Stop the song

### Changed

* Meteoric's ChatBot - Meteoric's Chatbot system has been remade from a command into a event. Once you set a channel for Meteoric's chatbot api to be set to any message sent within that channel Meteoric will respond back.
* Slowmode - If this command is used in a channel with slowmode enable the the command has no args Meteoric will set the channel's slowmode to 0.
* Warn, mute, unmute, kick - Confirmation messages have not been changes. Also, these 3 commands are now logged unless a modlog channel has been set.
* Userinfo - Instead of Username for Account Info saying "Random Name#0000 | Bot: false/true" It's now say "Random Name#0000" and right after the discriminator it'll have either a bot tag or not depending on if the user is a bot or not. The command also displays the user's/bot's nickname for the server as well their Highest role, if they don't have a high role then it'll display "No roles".
* Report - Report Bug command now gives you a invite link to the support server so you can see the bug you submitted.

### Removed

* Document command - The reason I removed this command is because there's no need to have Meteoric's Docs exist in the form of a command.

### Fixed

* Under the hood fixes
* Fixed up the help menu a bit (Grammar and changed how stuff is worded)
