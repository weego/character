# character
Digital Music Instruments (DMIs) with Character. 
A Series with code examples in SuperCollider. 

-- work in progress -- 

## intro
Everyone wants to play musical instruments that have *character*. There's tons of toys out there that ain't got any, and everyone is after those that do. 
But what is it that gives them *character*, and how can we achieve it in our own designs? 

The repo is structured in conceptual parts with reading material, and SC code. 

## methods 

### cybernetics / nontrivial systems / the Barrons

Read:

- Heiz von Förster: Understanding Understanding.
 short read:<br> http://www.cybsoc.org/heinz.htm 
- Louis and Bebe Barron: Soundtrack to "Forbidden Planet" <br>https://en.wikipedia.org/wiki/Bebe_and_Louis_Barron#Forbidden_Planet <br>
  https://www.youtube.com/watch? 
- Peter Blasser: Philosophical Paperz <br>
https://ciat-lonbarde.net/fyrall/index.html

Realizations: 

- simple examples in  https://github.com/marcokuhn/DMI/blob/main/code/scd/8-trivial-nontrivial.scd 
- feedback .ar
  - https://github.com/marcokuhn/DMI/blob/main/code/scd/3-xFM.scd 
  - https://fredrikolofsson.com/f0blog/feedback-synths/
  - most nUFO sounds / Ndefs
- feedback .kr
- logic from signals 
  - LFSR 
  - Rob Hordijk's Rungler 
  - Peter Blasser's Fyrall
- feedback via counters / frequency dividers etc.
- [scsynth thread](https://scsynth.org/t/cybernetic-music-with-supercollider/3184) and [lines forum thread](https://llllllll.co/t/cybernetic-music-roland-kayn-feedback-systems-ai/40635) on cybernetic music: do cybernetic music systems need to be goal-oriented? 

  
### Bad behaviour - against engineering norms
- irregular sample rate 
- thermic drift
- aliasing 
- distorsion
- [low battery audio effects](https://nathan.ho.name/posts/low-battery-audio-effects/)
  
### inspired by organic life
- linear drift aka aging - reboot to get back
- mutation
  - start conditions mutate: Rand()
  - mapping hops - meta mapping 
  - stochastics
