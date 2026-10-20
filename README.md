# Defensive Plays Trainer

A 3D trainer for defensive decisions in **baseball**, **fastpitch softball**, and **slowpitch softball**. You pick a position, a play unfolds from behind your fielder, and at the key moment the play freezes: where do you throw, where do you go? Tap your answer before the clock runs out, then see the explanation and a replay of the best play.

Runs in the browser on desktop and phone. English and German.

## Features

- **Every position** on the field, alone or mixed (for example the whole outfield: situations alternate between the chosen positions), with sport-specific rules: field size, leadoffs, stealing, no bunting in slowpitch, and a 10-player defense in slowpitch.
- **Pre-pitch briefing**. It covers inning, score, outs, count, runners and the key facts (forces, double play, tag-ups, does the run matter?). You set your game plan before the pitch: where the throw goes for infielders and for outfielders.
- **Decisions under time pressure**: tap a base, a player or a spot on the field in the 3D scene.
- **Realistic outcomes**: ball flight uses real physics, and runners and fielders move at sport-specific speeds. Force plays and tag plays are judged by actual timing; on a close tag play the runner slides in.
- **Generated situations**:
  - ground balls to every infielder, including comebackers to the pitcher and the 3-1 play
  - base hits and fly balls with tag-ups to the outfield; on a deep fly the throw goes to the cutoff unless the throw through gets the runner
  - cutoff and coverage for SS, 2B and 1B on base hits and fly balls to the outfield (who cuts which throw, who covers which bag)
  - foul flies with a runner on third: catch it, catch and throw home, or let it drop when a catch would give up the deciding run
  - sacrifice bunts for P, C, 1B and 3B
  - line drives caught by an infielder or the pitcher while runners are off the bag: double the runner off at the closest base, or step on it yourself
  - rundowns between first and second (drive the runner back; with a runner on third, throw home)
  - fly-ball priority between infielder and outfielder, the pitcher covering first, and the third baseman's step-on-third double play
  - steals for the catcher (second, third, first-and-third) and coverage for SS and 2B, depending on the batter's side
  - chained plays: back up a throw, the ball gets away, and a second decision follows (RF and C back up first, LF backs up third, P backs up home); when every runner is already safe, the ball goes back to the pitcher

  Runners, outs, score and inning are randomized, so the right answer changes. Three difficulty levels.
- **Challenge mode**: 10 situations with points for right and fast decisions, streak bonuses, and local high scores per difficulty. **Free practice** is the endless mode without points.
- **Player view or overhead view**, slow motion, replay of the best play. After a decision the camera pulls back to follow the ball and comes back in before the next one.
- **Sound**: bat crack or bunt tap, bounces on dirt and grass, glove and mitt pops, and the umpire's "Out!" and "Safe!" (can be switched off in Options).
- **Options**: team colors for home and guest, park or stadium scenery, sound on or off.
