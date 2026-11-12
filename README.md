# Fretboard Explorer

A single page guitar tool. Two things you can do with it: explore chords and scales on the fretboard, and train your ear.

## Why I built it

I've played guitar for years. I have an American Strat, I grew up on classic rock and metal, and John Frusciante is my favorite guitarist. But my ear has always been the weak spot.

I can play shapes I memorized. What I can't do reliably is hear a note and know what it is, or hear a chord and know if it's major or minor. That's the part I never trained. I wanted something I could open for five minutes and actually practice with, not another app I have to sign up for and never open again.

So I built the thing I needed.

## How I built it

I vibe coded it with an AI assistant. I didn't write the code. I described what I wanted in plain language, tried it, and told it what to change. That loop is the whole workflow: describe, test, correct, repeat.

It started with me asking for ideas for a small public project that would show how I use AI to code. Something simple, something people could click through in a few seconds. It came back with three ideas: a game picker, a fretboard explorer, and a comic tracker.

The fretboard one was the obvious pick. Ear training is something I actually need, not just a demo.

From there the prompts went like this. First I told it the ear training had to be the main thing, not an afterthought. Then I had it build the explorer: pick a chord or a scale, see it light up on the fretboard, hear the notes. Then the ear training modes: guess the note, guess the chord, with a score and a streak so you can watch yourself get better.

Each round I tested the preview and gave it notes. Keep it simple enough that someone gets it in ten seconds. Make the fretboard the thing you look at, not a wall of menus. If something felt off, I said so and it fixed it.

I also had it write this README in my voice, like I'm explaining how I did it and how I prompted it. Because that's the part I actually want to show: not just the finished page, but how I got there.

## What I learned

The biggest thing is that prompting is the skill. Being specific about what you want, and honest about what's wrong when you test it, gets you further than knowing syntax.

The AI writes the code. My job is knowing what good looks like and saying so clearly.

## How to use it

Open the page. In Explorer mode, pick a chord or a scale and click any note on the fretboard to hear it. Hit play to hear the whole chord or scale.

In Ear Training mode, pick guess the note or guess the chord. It plays something, you answer, it keeps your score and your streak — saved on your device, so they're still there when you come back.

## What's next

More ear training modes. Intervals first, then chord progressions. Your best streak now saves on your device. Open to ideas.

## The look

The style is its own thing, on purpose. It doesn't copy my Taproot site (navy and teal) or my personal site (light, clay and charcoal). It's a warm old guitar amp feel: deep pine green and brass on warm paper, serif headlines, a mahogany fretboard.

## Tech notes

No build step. Just HTML, CSS, and JavaScript. The audio is generated in the browser with the Web Audio API, so there are no sound files to load.

Built with an AI assistant.

Vibe Coded by Rick Aquilia.
