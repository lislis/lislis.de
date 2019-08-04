+++
title = "Generative music (Party:4:2)"
date = 2018-09-19
draft = false
[taxonomies]
tags = ["webAudio", "JS", "shaders", "creative coding"]
category = ["talk", "project"]
+++

The one where I talk about a procedural music generator.

The more you fall into the rabbit hole of music theory and programming the more your brain comes up with strange ideas like this one.

## About Party:4:2

I kind of like Shania Twain and the song *Party for two* remains a vivid memory and keeps reappearing in my consciousness for some reason. It's not clear to me when the idea of the two parties to participate in the party should not be two humans but a human and a computer.

We share quite a few intimate things with computers and why not also party together?
Since computers are good at numbers and generation according to rules, the computer should be in charge of music and visuals and the human, being good at feelings, should bring the fun.

Party:4:2 is the outcome of this, powered by JukeGen, a (simple) procedural music jukebox and a very poorly written fragment shader (writing this, I am much wiser as to what should go into a shader and what not) that the human can interact with via a physical game pad.

The human can influence both visuals and music to a certain degree and with the engagement created by of both  control and exploration creates a sense of fun.

## Music theory & shaders

I dream of one day actually fully understanding (western) music theory in a way that I can leverage it to the fullest while coding. But it's not that easy.

Fragment shaders are awesome and my brain hurts from coding them. But setting up a shader context in JavaScript from scratch taught me quite a few things. Mostly that I want this abstracted away from me so that I can focus explicitly on the shader code


## Web Audio Conf

Web Audio Conf (WAC) is a strange place and very, very academic. I felt quite out of place but in the end it was fine. It usually is. The title of the talk was **"Generative music, playful visualizations and where to find them"**, which I'm not super happy with, but it got the job done.


Given at [Web Audio Conf 2018](https://webaudioconf.com/) in Berlin.

[Live slides](https://lislis.de/talks/wac-2018) and [code for slides](https://github.com/lislis/wac-2018-talk). Code for [JukeGen](https://github.com/lislis/jukegen) and [Party:4:2](https://github.com/lislis/party-4-2) and [party live](https://lislis.de/projects/party42/) (only works with a controller).

{{ youtube(id="vQOtLFDDDS8") }}
