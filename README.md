# Invasion of Meridell

Save Meridell from invading Darigan troops! This is a turn-based strategy game that used to exist on Neopets until 2011, when it was removed due to it being exploited. Despite incessant pleas, it's never come back - so after a decade of waiting, here it is rebooted by fans.

This repo attempts to clone the game exactly as it exactly right before being shut down.

[Play here!](https://emeth-.github.io/invasion-of-meridell/)


## Game Timeline
* <2005: Neopets released Invasion of Meridell v1 (first wave / first five missions only)
* ~2005: Neopets released Invasion of Meridell v2 (second wave added, no concept of enchantments)
* ~2006-2011: Neopets released Invasion of Meridell v3 (enchantments added, Buzz/Grarrl stats changed with Buzz defense-heavy and Grarrl attack-heavy)
* 2011: Invasion of Meridell is [taken down](http://www.neopets.com/games/play.phtml?game_id=182), game page is replaced with message "Invasion of Meridell is down for maintenance. We apologize for the inconvenience. Why not try one of our many other games?"
* Sept 2011: TheNeopetsTeam breaks radio silence and in [NT Editorial #511](http://www.jellyneo.net/index.php?go=editorialdb&type=id&query=14495) explains why the game was taken down: "We talked to a programmer and there was some kind of glitch with it. It's been taken down indefinitely. We'll talk amongst ourselves to figure out if we want to put the time in to fix the game. If not, we may release the associated avatar in a different way, or retire it. We'll update you once we reach a decision."
* Jan 2012: An XSS attack/exploit was found on IOM and [published publicly](http://xssed.com/mirror/64791/). Had been found in 2009, and remained unpublished until Neopets removed the game. Unclear if Neopets became aware of it and it contributed to their decision to take the game down.
* Dec 2013: Forum member "Infamous Joe" [gives details](https://clraik.com/forum/showthread.php?30654-Invasion-of-Meridell/page2) of the IOM exploit. In short, IOM was web-based, as opposed to the rest of Neopets games which were flash-based. It appears that some of the api calls IOM used could be executed without actually playing the game, and earn a person up to 250k Neopets a day automatically. The exploit was released in the form of a downloadable tool that one group of forum members shared, then one of those members reverse engineered it, built it into a new tool allowing it to be used on multiple accounts, and released it on another forum where it then said widespread usage (and presumably came to Neopets attention).
* 2015: Darkflagrance builds a clone of IOM in Java and releases it. [Announcement 1](http://www.bay12forums.com/smf/index.php?topic=154262.0), [Announcement 2](https://tdnforums.com/topic/45831-im-rebuilding-invasion-of-meridell-as-its-own-program/), [Announcement 3](https://www.reddit.com/r/neopets/comments/3uh2dy/update_invasion_of_meridell_remake_in_progress/), [Announcement 4](https://www.reddit.com/r/neopets/comments/3va341/invasion_of_meridell_remake_beta_release/) | [Source](https://drive.google.com/open?id=0B2Y0VMXUm08mRkNremE5ZVV0bnc) | [Compiled Game](https://drive.google.com/file/d/0B2Y0VMXUm08maEFyTE5meG9hOFk/view?usp=sharing)
* 2020: We release this clone of IOM written in Javascript. We base our clone off the gameplay found in the Java version, but then correct it off the guides/screenshots/videos we find online. See our notes on this process [here](https://github.com/emeth-/iom-reverse-engineering).


