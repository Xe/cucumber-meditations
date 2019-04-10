# Feature: Tapering Meditation Length Upwards Gracefully

As someone is beginning in a meditative path, it can feel difficult at first
to meditate for long periods of time at once. This feature offers a method of
tapering meditation lengths upwards so that you may build up to whatever your 
target is gradually.

The overall guiding principle here is to gracefully taper up. Initially it is
going to feel like you failed. If you get distracted every 30 seconds during a
30 minute meditation and refocused your attention back to the meditation every
time, you were mindful of your meditation session 60 times in half an hour. 
The overall goal of this entire practice is not to perfectly meditate every 
single time, that is impossible. The goal is to improve your skills over time. 
Being mindful of your meditation session is one of the easiest ways to 
consistently improve your skills.

## Background

> Given no assumption about meditative background  
> And somewhere to record progress notes

This "somewhere to record progress notes" should be simpler than you are probably
thinking. Think paper. Think Notepad. Think simple. You don't want this to be a
chore, or you will simply just not do it. Use whatever you're more comfortable
with.

Again, cut this out if it doesn't work out for you.

## Scenario Outline: Tapering up From 5 Minutes to 30 Minutes over Two Weeks

> As a meditator  
> In order to get better at meditation in 14 days  
> When it is day $day  
> Then my meditative goal for the day will be $goal minutes of meditation  
> Then I make sure to record things I learn in my progress notes

### Examples:

| day | goal |
| :-- | :--- |
|   1 |    5 |
|   2 |    7 |
|   3 |    9 |
|   4 |   11 |
|   5 |   13 |
|   6 |   15 |
|   7 |   17 |
|   8 |   20 |
|   9 |   22 |
|  10 |   24 |
|  11 |   26 |
|  12 |   28 |
|  13 |   29 |
|  14 |   30 |

