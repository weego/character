# character
Digital Music Instruments (DMIs) with Character. 
A Series with code examples in SuperCollider. 

-- work in progress -- 

## intro
Everyone wants to interact with a musical instrument that has *character*. There's tons of toys out there that ain't got any, and everyone is after those that do. 

This in an investigation into the quest of characterful instruments: what gives an instrument character and how can we achieve it in our own designs? 

The repo is structured in conceptual parts with reading suggestions, and SC code. 

## a few inspiration sources

### cybernetics / nontrivial systems / the Barrons

Read:

- Heiz von Förster: Understanding Understanding
- Louis and Bebe Barron: Soundtrack to "Forbidden Planet" 
- Peter Blasser: Philosophical Paperz 

Realizations: 

- feedback .ar
  - https://github.com/marcokuhn/DMI/blob/main/code/scd/3-xFM.scd 
  - https://fredrikolofsson.com/f0blog/feedback-synths/
- feedback .kr
- logic from signals 
  - LFSR 
  - Rob Hordijk's Rungler 
  -  Peter Blasser's Fyrall
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
