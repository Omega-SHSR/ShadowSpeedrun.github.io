![](/img/S-SX-Logo.png)

## Download on GitHub

#### [Click here to visit the GitHub Release page](https://github.com/ShadowSpeedrun/ShadowSX/releases)
<br/>

<u>You will need to provide your own clean rip of the Shadow ENG NTSC ROM to run with the emulator.</u>

<u>The only files provided on GitHub are the configuration files needed to apply the settings and changes to run Shadow SX.</u>

<br/>

## What is Shadow SX
Shadow SX is a ROM hack of the ENG NTSC version of Shadow the Hedgehog that aims to provide quality of life changes for improving the speedrunning experience without any major changes to the core gameplay experience. 

As of BETA V2, Shadow SX is playable on GameCubes or Wiis with Homebrew or on computers using Dolpin Emulator.

Although this website started as a means of consolidating and proving data for the console releases. Everything you see on this site should apply to both the console versions and Shadow SX.

Due to changes to the game code, Shadow SX will be considered it's own thing seperate from the original console releases.  Seperate Leaderboards for any of the categories or levels will be provided at a future time.

This current release is considered a BETA and is meant to get a feel for how everyone is able to setup and play this version.  There will still be some changes to the emulator and ROM hack code as we move into a definitive version.

If you record and upload any footage of Shadow SX, please be sure to properly label the video as the SX version including that it's a BETA to help prevent confusion for future viewers / runners of the game.

<br/>

## Changes Compared to the Original
The following changes have been made to the game code:

### In Game Timer (IGT) Quality of Life changes

#### Checkpoints no longer pause the IGT
The game will no longer pause the timer while in the checkpoint menu.  This prevents the use of the checkpoint for saving IGT while waiting for another in game event to playout.  More important though, is that this change allows the use of IGT timing for runs that utilize the Chaos Control Glitch.

#### Deaths no longer reset the IGT to the last checkpoint time
One of the biggest headaches when timing IGT runs on console was having to manually calculate the time from deaths to checkpoints.  With this change, the time continues without interuptions after death.  The time you end the level with is the final time now.

#### Restarting a stage during a "Story Mode" playthrough no longer resets the IGT
This change, while applies to every level, is mainly targeted to the shorter Boss Fights where one might reset quickly early on if a setup doesnt go to plan. Like with the Death fix above, the timer will simply continue form that point on until the end of the level or boss fight.  

This does NOT apply to levels or bosses that are started with "Select Mode" as this would quickly become annoying for Individual Level (IL) runs and attempts. This applies only for Normal Story, Last Story, and Expert Mode playthroughs.

#### Preventing timer slow down during boss fight Chaos Control
A neat mechanic for boss fights was slowing down time when using Chaos Control instead of speeding through the level, which makes sense considering that boss arenas are small enclosed areas.  When time slows down, the IGT slows down considerably. Since SX changes the IGT to be more of a RTA without loads timer, the IGT will now longer slow down.  Everything else should remain unaffected.

<br/>

### IL Quality of Life changes
The following changes were made to not only improve the quality of life for IL attempts, but also to keep Story and IL runs more in sync.

#### Partners no longer have intro cutscenes
When you first encounter a partner character, there's a quick intro that plays to introduce them.  This gets annoying after many attempts so the intros have been turned off.  This also allows the player to focused more on movement for the sections they would normally be stopped in, just like if they were doing multiple IL attempts.

#### Infinite Lives for Select Mode
Kinda self explanitory, no longer needing to worry about lives makes IL a lot more bareable. This only applies to the Select Mode. The Story Style game modes work the same as the original. To account for the handicap that is available in the Egg Dealer fights, holding D-Pad Up while selecting one of the Egg Dealer levels will enable a mode where you will start with infinite 0 lives to allow the 

#### Secret Doors Open Faster.
If you have all 5 keys for a level, the Secret Door will now automatically open, just like it would if you had opened it normally, and reentered the area after a death. This was how one could speed up IL in the original game. Now it's available to everyone without needing to interact with it first. This also allows for Story Mode and ILs to use similar strategies.

<br/>

### Emulator Changes
The following changes were made to the default Dolphin configuration to improve game perforance.

#### Recommended Settings
Included in the download is a set of recommended settings that have been tested to provide a good gameplay experience.  If that is not the case for you, reach out to let us know.

#### Overclocking with Dolphin Settings
Since Shadow SX and the console Shadow releases will not be comparable, Shadow SX will utilize the Dolphin Emulator's ability to run at a higher clock frequency for better perforance and a smoother experience.  This should play similar to running on Nintendont on a Nintendo Wii.

#### Improved Loading Times
The Dolphin Emulator has a setting to allow faster reading of the ROM data.  So instead of having to match a similar rate to the GameCube disc drive, the emulator can read and load data much faster allowing vastly shorter load times.  Normally getting from the end of Westopolis to the beginning of Glyphic Canyon takes a little over a minute on Wii.  With this change, it now takes 48 seconds.

#### Reduced Bloom
When playing on Dolphin, the bloom effect is a bit stronger than what is visible on console. A change was made to reduce this back to expected levels.

<br/>

### Optional Changes
These changes are optional settings:

#### Race Timer
Along with remanaging the IGT time, I have been able to set aside some space to keep track of the current total time for a Story or Expert Mode runs.  Currently this is a option that will swap out the IGT timer spot when enabled.

#### Options for Skipping Cutscenes
New file runs will now be able to skip cutscenes without needing to view the cutscene first like in the original. There is an option to disable this change if you wanted to run a New Game run like you would on the original, notably for runs like All Endings and 100% No Library where cutscnes have an effect on the run.

#### Glossy Effect on Characters
The glossy effect on characters can be left alone, reduced, or removed.

#### Replace Button Images for UI
Different Textures are available that allow swaping out the default GameCube buttons with PlayStation or Xbox images.

#### Modern Controls for UI
When using GameCube controls, no changes are needed.  But if you are using a PlayStation or Xbox style controller, turning this option on will allow you to control the game just as you would on the Xbox or PS2 versions of the game.

<br/>

## Planned Roadmap for future changes

### BETA
The main plan for BETA is to improve the setup and managment process. As of BETA V2, getting set up and going is pretty quick and easy with the ROM patching methods provided. Getting the recommended Dolphin setup is still a bit of a hassle, but the provided instructions should help guide anyone through the process. There is currently a bug with Dolphin that causes a hitch after playing for a while. I would like to see this fixed before preparing a specialized build to simplify the setup process.

### Full Release
Once everything is ironed out and finished in BETA, a proper release will be made.  At this point a leaderboard should be available to track runs of the game.
