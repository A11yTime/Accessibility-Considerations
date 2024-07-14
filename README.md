# Accessibility-Considerations of different disabilites
### Visual disability
##### Visual disabilities rages from low vision to blindness and some people have color blindness.
#### Blind
* All content must be available in text to serve the equivalent purpose.
* Focusable element must be available and function with keyboard.
* Page must be structue with good semantics either with native html tags or aria. It is highly recomended use of native element rather than aria.
* All custom widget must have name, role and value(when appropriate) to expose screen reader.
* All action on page should have immediate feedback either with native or aira
* Video content must have equivalent alternative (transcripton, caption and audio description) to accommodate different disabilities
* Cutom swipe action must have alternative(with single pointer).
  
#### Low vision
* Page content must be resized up to 200% without loss of contnet and functionality.
* All text and image of text must have proper contrast ratio, for reqular text 4.5:1 and large text 3:1
* Image of text should not be used If the same visual presentation can be made using text alone.
* Focusable element should be distinguishable in different states (Focus, hover, selected) with contrast ration of 3:1

#### Color blindness
* All content on the page must be understandable without relying on color alone (Combination of red and green)
  
#### Motor Control disability
* All controls must be avaiable with keyboard and mouse as well.
* Focusable elements should be distinguishable in different states (Focus, hover, selected) with contrast ration of 3:1
* Must have obvious visual focus indicator(contrat ratio 3:1 with 2px and larger indicator)
* Time dependent functonality must have mechanism to turn off, adjust and extent the time limit.
* Click/touch target should be large enough without risking activating adjacent controls.
* Page provide mechanism to bypass block of content that are repeated on multiple webpage.

#### Cognitive disability
##### Cognitive disability is most common type of disabilites by far. Web content accessibility guidelines don't completely address cognitive disability but with sophisticated design consideratons help to enhance the experience for cognitive disability:
* Simplify the design
* Simpler language
* Consistant navigation
* Consistant Identificaiton
* Clear label and instruction
* Provide suplemental format
* Reduce cognitive load.
* Eliminate distractions and enhance focus.
* Offer help

#### Hard of hearing
* All video content must have captions and all audio only content must have transcriptions

#### Deafblindness
* All considerations for blindness and deafness apply
* It is highly recomended to provide transcriptions for audio and video content.

#### Speech disabilities
* Voice dependent functionality must have alternative.
