# WebSampler Template

## Abstract

The finished project should be a fully functioning, deployed web application with stable access speed and a decent UI. It will allow users to perform sampling of audio files, with specific lowlevel effects, potentially include slicing, convolution, function application. The samples can also be sequenced to an extent. 

## Goals
 - Sequencing/automation 
   - Shouldn't look like a step sequencer
   - Should feel like an instrument
   - Ideally it should transition from instrument to composition device
   - Replication
   - RoSa as a model: it exposes OSC commands that manipulate the buffer
   - Monolithic buffer that has views which slice into it
   - Scriptability of buffers slicing and play stopping
 - Exporting of audio in limited capacity
 - Freesound integration

### Production Goals
 - Version one: default audio buffer and slices, test all manipulations of slices
   - Play/Pause/Stop
   - Loop Start/Loop End
   - Wavetable Stuff

## Needs 
 - Clojure/ClojureScript
 - WebAudio Api familiarity
 - Cheap server and deployment service, eg Heroku.
 - Scheduled development 
 - Attractive UI for use in portfolios
 - Usability in creative work
   - Audio export?
   - Sequencing?
   - Fast/without audible lag
 
## Resources 
 - Building WebApps with Clojure
 - Clojure/Cljs docs 
 - https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Basic_concepts_behind_Web_Audio_API
 - UI
   - React docs: https://facebook.github.io/react/tutorial/tutorial.html
     - Om vs Reagent: http://theatticlight.net/posts/Om-and-Reagent/
     - Om: https://github.com/omcljs/om
     - Reagent: https://holmsand.github.io/reagent/
   - Any other options?

## Timeline
 - Read the dang book: 
   - Total length is 230 pages minus appendices; each chapter is roughly 30 pages.
   - Reasonable per-week reading: 90-100 pages, give or take depending on subject
   - Now until Easter Chapters 1-4
   - After that? 5-7
   - Chapters 8&9
 - Trampoline structure over course of weeks 1-3
 - Weeks 4-6: Develop application logic, structure & UI
