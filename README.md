# Five Game Theory Games

Full summary here: https://www.reddit.com/r/SampleSize/comments/747ofd/results_i_have_compiled_the_results_of_the_game/

## Summary of Results

If a user selects the same scenario as another Redditor, they will be randomly paired with them. The outcome depends on the decision the redditors make together, and in the Results thread they were both called out.

Redditors were instructed to read the instructions carefully. Only one response is allowed per user per scenario. If a user submitted conflicting responses for a scenario, I messaged them directly and asked which one they wanted to pick.

### Game A - Chicken

You and a Redditor are in cars on a narrow bridge. Your cars are facing one other. You rev the engine, your opponent revs their engine.
On cue, you both slam the gas and start towards each other. You can end your conflict right now, if you can get your opponent to swerve. But you absolutely don't want to crash or else you both get serious injuries. You've now gotten as close as you can to your opponent, and it's time to make a call.

So what will it be? To summarize your choices:
* Both of you lay on the pedal, and you both get severe injuries
* Both of you swerve, and neither of you get anything of value.
* If one of you swerves, the other one doesn't, the one who doesn't swerve wins the right to forever humiliate the other with the title "chicken".

**Full results:** https://github.com/zonination/gametheory/blob/master/game_a.csv

![Game A - Chicken](https://raw.githubusercontent.com/zonination/gametheory/master/game_a.png)

### Game B - Snitch

You and another Redditor have been arrested, and are facing charges for a crime you both committed together. You're pretty much screwed, but there's a possible way out...

The cops come at BOTH of you with a plea deal: If you sell out your friend and they stay quiet, then they get 3 years and you go free. The cops are tricky, though. If you both sell each other out, they have enough evidence to put you both in jail for 2 years. And if you both stay quiet, you both get 1 year for Obstruction of Justice.

So what will it be? To summarize your choices:
* Both of you snitch, you both get 2 years.
* One snitches and the other stays quiet, snitch gets 0 years and the other gets 3
* Neither of you snitch, you both get 1 year

**Full results:** https://github.com/zonination/gametheory/blob/master/game_B.csv

![Game B - Snitch](https://raw.githubusercontent.com/zonination/gametheory/master/game_b.png)

### Game C - Game Show

You and another Redditor just won $1000 on a game show together. Now the challenge is splitting the cash. The game show has a novel idea: see whether the two contestants really trust one another.

The show has two buttons that you can select: SHARE and STEAL. If you both SHARE, you split the cash evenly and go home happy contestants each with $500. But if one of you STEALs, the theif walks away with the entire $1000 prize and the gullible companion gets nothing. And, of course, if you both steal, both of you get $0.

So what will it be? To summarize your choices:
* Both of you SHARE, you both get $500
* Both of you STEAL, you both get nothing.
* One SHAREs and the other STEALs, the STEAL gets $1000 and the SHARE gets nothing.

**Full results:** https://github.com/zonination/gametheory/blob/master/game_c.csv

![Game C - Game Show](https://raw.githubusercontent.com/zonination/gametheory/master/game_c.png)

### Game D - First Strike

CAREFUL! This scenario is similar to "M.A.D.", but it has different consequences!

You and another Redditor are in a military standoff for almost a decade now. Both of your countries have nukes, and the other might be too weak to fight back.

At some point, the other Redditor may attack you, or you could go the peaceful option. If you strike, it all depends on who strikes first. You could also sue for peace, but you might get taken advantage of.

What will it be? To summarize your choices:
* If you both Nuke, the user with the earliest timestamp wins the war while the other gets destroyed.
* If you both choose Peace, the conflict ends and nobody perishes.
* If one of you Nukes, and the other chooses Peace, the one who selects Nuke wins while the other gets destroyed.

**Full results:** https://github.com/zonination/gametheory/blob/master/game_d.csv

![Game D - First Strike](https://raw.githubusercontent.com/zonination/gametheory/master/game_d.png)

### Game E - MAD

CAREFUL! This scenario is similar to "Nukes", but it has different consequences!

You and another Redditor are in a military standoff for almost a decade now. Both of your countries have nukes, and you both have publicly vowed to destroy each other in full if the other initiates an attack, through Second Strike protocols. Your and your opponent are currently fighting on your east.

What will it be? To summarize your choices:
* If you both Nuke, you both get annihilated.
* If you both choose Peace, the conflict simply gets worse.
* If one of you Nukes, and the other chooses Peace, you both get annihilated because of Second Strike protocols.

**Full results:** https://github.com/zonination/gametheory/blob/master/game_e.csv

![Game E - MAD](https://raw.githubusercontent.com/zonination/gametheory/master/game_e.png)

## Information

* Source: /r/samplesize data
* Tool: R and ggplot2
