# 039 · Firefly Catcher

**AppADay** — App 039 of 365  
**Category:** Games & Interactive  
**Built:** June 15, 2026  
**Live:** [augustineiacopelli.github.io/appaday-039-firefly-catcher](https://augustineiacopelli.github.io/appaday-039-firefly-catcher/)

-----

## What it does

A summer night game where you tap glowing fireflies drifting across a starlit sky to catch them in a glass jar. Each successful tap launches the firefly along an arcing path down to the jar at the bottom of the screen, where it joins the other captured fireflies — pulsing and drifting around inside the glass. A timer counts down and your score is how many you caught before time runs out.

## How to play

1. Choose a difficulty (Easy / Normal / Hard)
1. Tap **Catch Fireflies!** to start
1. Tap any glowing firefly to catch it — watch it arc into the jar
1. Miss taps show a red ripple
1. When time runs out, you get a score and a grade

## Difficulty

|Level |Fireflies|Time|Target size|
|------|---------|----|-----------|
|Easy  |7        |40s |Large      |
|Normal|10       |30s |Medium     |
|Hard  |14       |25s |Small      |

## Tech

Single-file vanilla HTML/CSS/JS. Canvas-based rendering with:

- Quadratic bezier catch arcs from tap point to jar
- Canvas clipping to keep jar dots visually inside the glass
- Organic firefly flight with randomized turn rates and pulse glow
- Twinkling star field with procedural grass silhouette
- ES5-safe, no frameworks, no dependencies

## Part of AppADay

One complete web app built and shipped every day.  
[← Back to portfolio](https://augustineiacopelli.github.io/appaday/)
