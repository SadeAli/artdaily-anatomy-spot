# Anatomy Spot — an Art Daily drill

Two mannequins built on the classic 7.5-head canon stand side by side;
one hides a single proportion error — head, upper arm, forearm, torso,
leg or shoulder width. Tap the flawed figure, then tap the part that is
off. Five items per round, and the flaw ramps subtler: ±30% → ±20% → ±13%.

Scoring is pure geometry: 50 for naming the right figure, up to 50 more
for how close the second tap lands to the flawed part's capsule (full
marks on the part + 12px, fading to zero 1.2 head-units away). The round
score is the mean of the five items. After every item the true canon is
ghost-overlaid with a head-unit ruler, so each miss still teaches.

Part of [artdaily.sadeali.com](https://artdaily.sadeali.com/) —
plain HTML/CSS/JS, no build step, no trackers.

## What changed in the input-fairness pass

A wrong first tap no longer forfeits the item. With two figures that was
a coin flip, so half of all first-timers met "other figure!" as their
first ever feedback and two unlucky guesses capped a round at 60. The
drill now says "not that one", lets you take the other figure for 10
instead of 35, and still runs the locate half for its full 65 — and
finding the part, not naming the figure, now carries most of the marks.
Both figures share ONE pose, so the only difference between them is the
proportion being asked about. The head-height ruler is on screen while
you play, the landmark canon is printed under the picture instead of
hidden behind a button, and the hardest items are ±20% rather than ±13%.

## Input fairness

Scores are only ever compared against your own history, so the drill
eases its tolerances for the hardware in your hand and says which one it
eased for (the "scoring for…" chip in the HUD). A pen keeps the strict
reference; a mouse or trackpad, which pivots at the wrist and cannot
creep, gets roughly double the room; a finger sits between. Start and
grab zones move the other way — a screenless tablet needs the *biggest*
targets, because the hand is out of sight. Relative tolerances carry an
absolute pixel floor so a phone is never held to a stricter standard
than a desktop for the same drill.

