# symmetrical-umbrella: Place finder for new things

As 2025 comes to a close, I decided to ask my girlfriend if she had anything she wanted to accomplish or change in 2026. After a good conversation, the summary was simply:

> I want life to be a little less mundane.

This is my little piece of contributing to that. Searching for places isn't always the easiest thing, since I might not know certain little nooks and crannies of our city to search, so I instead want to search, organize, and equitably select 50 places in our city to go this year that we haven't before - one per week.

## Planning & Feasibility

It's easy to search "[X] near me", where X is restaurants, hobby shops, or so on, but there are a few things that aren't so easy:

1. Avoiding bias. If you don't know about some potential X to search for, you're never going to find it.
1. Getting out of popular areas. Top searches might be localized in specific shopping centers, stopping you from getting out and seeing somewhere new.
1. Effectively picking several things. It's easier to pick new things in separate areas if you do them all at once - if you pick one thing a week, it'll still be more than zero things per week which is awesome, but it also becomes easier to do the same things every week, and to go to familiar places. 
    * Furthermore, it's more actionable to pick your several things up front, and encourages you to follow through. Well-scheduled routines make good habits.

I want to make something to solve these problems. Given an address (or coordinates), I'd like to find several currently-open/accessible places that I can go with my girlfriend next year - be it restaurants, parks, hobby shops, or something else that we haven't thought about, within a radius of her home. Maybe a new iteration next year that has a cool UI, but this time, just something calm and easy to run that spits out a CSV file in time for the first or month week of the year. I think this lightweight deliverable, and the use of something like the Google Places API, make this achievable in the timeframe and allow me to build on the data in the future.
