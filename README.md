# Lessons Learned from _"LoonyAnimals"_
A collection of lessons learned from developing my first game (mobile) **"Loony Animals"**

https://play.google.com/store/apps/details?id=com.illyriangamestudios.LoonyAnimals

## Pre-Production

1. Specifically define the game _core loop_ & functionalities before going into production:
Must-have features for the game to launch with.
Skip features which do not strongly benefit the core loop (i.e: ‘Nice-to-have’)
The loop must be given a good amount of initial research and prototyping time. You can tweak it in production but changing it at that point can cause a chain of never-ending changes.

2. Define the overall **Art Style** early -- color palette, style (i.e: cartoony; soft or hard edge graphics; hand-painted; retro...) etc. This helps to:
   - Focus how you will approach implementation of effects, mechanic feel, music etc.
   - Mitigate time lost and frustration to switch from programming to art design and vice-versa.
   - Wondering why elements of the game are not feeling ‘right’: music, sfx, vfx, textures, colors etc. Usually they will not match together and feel or look like a Frankenstein game.

3. Your game is a **project**, so manage it as such: 
   - Create a basic documentation with the points above.
   - Set weekly, monthly milestones. It can be painful when all you want is to create the game but achieving your milestones is a pleasure on its own.
   - Get in the habit of making estimations and doing your best to keep up with them.

## Production
1. Your main focus should be on:
   - Unique **mechanics/features** (quick iterations)
   - Strong **core loop** (potential for replayability without getting boring) -- making big changes at this phase might cause re-design of features, mechanics or backend systems so be careful not to make them (at least not everywhere).

2. Unless your game’s core loop is all about UI (eg: Card Game, Puzzle), then you should not bother with UI design and use basic buttons, frames. But bear in mind the Art Style you have chosen so it at least the colors match.

3. However strongly you might want to do everything yourself, soon the amount of work put into a game will start pushing you down. Don’t stray away from content made available by others - use other assets and at best you can modify them to your liking but at least you will have a start. You will in turn learn something new and get closer to finishing your game in time.

4. TECHNICAL (mobile): Keep performance in mind while you are adding new assets and/or effects. Mobile devices are so different, from specs to architecture and users don’t care. They will expect the game to run smoothly although they are still rocking a smartphone from 2012 :/

5. TECHNICAL (sort of personal preference): Spend more time and properly document for System Design. Eg: in-game shop & in-game currency; data->objects->actors; spawning systems; cleanup systems etc.

## Post-Production
### ANDROID:
1. Do not overly concern yourself with polishing and making your game Bug-Free as long as the core loop is playable because of this awesome option of Google to release in Open Testing (seen below).

2. Make use of the extensive toolset of **Play Developer** console:
   - Go through Internal/Closed Testing phases to get a hang of the publishing scenario to prepare you for the official release.
   - Collect reports from Google’s **“Pre-Launch Reports”**: automated testing of the game by Google’s devices and it compiles a report for various issues encountered (including crashes)
   - Release in Open Testing first: this will not save the rating towards the official release and you can test a “not-so-polished” game for that initial feedback.

GENERAL:
1. For me there was this fear of showing the game to other people; fearing that it would struggle on its own, without my guiding hand; but that blinded me to the issues - so:
   - Show your rough weekly prototypes to people (at least people who might be occasional gamers) - you are not looking for sugar-coated words here, so ask them to be blunt and ruthless…. A painful but eye-opening process.
   - Don’t lead people with questions like: _“Would you like it better if there was...”_ etc… Let them describe what they feel and say what they mean.
