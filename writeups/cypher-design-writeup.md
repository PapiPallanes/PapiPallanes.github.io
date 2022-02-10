---
layout: single
title: "Cypher Ability and Vandal Rifle Redesign Writeup"
header: 
  image: /assets/images/YeezyCropped.jpg
author_profile: true
toc: true
toc_icon: "headphones"
toc_sticky: true
---

---

{% include video id="TJpcrGZiZIM" provider="youtube" %}

Here I do a quick walk and listen through my final project file for the redesign. I also talk about my thought process behind certain decisions for ablities and my ideas for how it should all sound.

Below you can find a written explanation of my design process. 

---

# Redesigning the Vandal Rifle

The first part of my redesign consisted of redoing the Vandals gunshots and reload. These sounds are entirely sample based as gunshots are, to simply put it, really hard to synthesize.

In the gunshot sound I have multiple layers consisting of a sampled AR10 recorded at Close, Medium, and Far range (in open air), to cover the wide gamut that a gunshot covers.

Additionally we have miscellaneous sounds like a Camera shutter, to mimic the mechanical bolt that clicks as each bullet fires, and a drum kick to add more bass to the front of the gunshot.

The second part of the Vandal sounds to remake was the reload, which was pulled from the same sample library the gunshots were sourced from. The most manipulation came in the form of moving around parts of the reload to better fit the look of the vandal and more accurately reflect the apparent materials of the rifle


![Vandal Redesign file screenshot](/assets/images/writeup-images/VandalWorkScreenshot.png){: .align-center}


# Redesiging Cyphers Abilities

Cypher is centered around stealthy info gathering and cunning tactics to gain the upper hand. His main abilities, barring his ultimate, all feature a “cloaking” aspect. I saw this cloak as a great opportunity to work on my synthesis ability using the free synth helm.

## Designing the Cloak

All of the cloaking sounds we're made from the same Helm patch. But manipulated to give each ability it's own distinct cloak. My main idea for the cloak sound was wholly inspired by the predator and uses fading clicks to convey the idea of the item going invisible.


![Cloak design Helm Patch](/assets/images/writeup-images/HelmCloakScreenshot.png){: .align-center}


## Designing the Abilities

After finishing the cloaking sounds for each ability I went down the line working on each ability on it's own, focusing on the ability cast, placement, and activation (if applicable)


### The Cage


![Cage Opening Screenshot](/assets/images/writeup-images/CageOpenScreenshot.png){: .align-center}


The first ability I worked on redesigning was the cage. I wanted a kind of "metal mesh" feel when activating the cage. I thought of this primarily because of its look when activated. This sound was achieved by having 2 different Helm patches in which one part was a percussive front end, and a "metal-like, twangy" tail end.


![Helm Cage Open Patch](/assets/images/writeup-images/HelmCageOpenScreenshot.png){: .align-center}


Something else that I wanted to mess with was using different pitches to change how the sound feels. While I ended up only using 1 of the takes in the final redesign, it's still an idea I find interesting enough to try in future projects.


![Helm Cage second open Patch](/assets/images/writeup-images/HelmCageScreenshot2.png){: .align-center}


#### Closing the Cage


For the close of the cage I went with a resonant hit preset from the Alchemy synthesizer modifying it to make it sound similar to a radio transmission tuning out.


![Alchemy Preset for Cage](/assets/images/writeup-images/AlchemyCageScreenshot.png){: .align-center}


The main idea of this sound being used for the cage closing was mainly from the way in which it closes, which reminded me of old CRT TVs turning on/off with the color of the broadcast very quickly turning to white and then immediately to the black slate of the screen. The sound mimics this in there being a burst of "transmission sound" to communicate the cage closing.

### Designing the tripwire

After the Cage sounds I went to redesign the Tripwire and all of its parts. Unlike the cage, most parts of the tripwires redesign are sampled layers.

![Tripwire Example Image](/assets/images/writeup-images/TripwireExampleImage.png){: .align-center}

For the pullout I took the sound of a poker chip tapping wood along with a metal coin tapping against metal for the clicks that occur when Cypher shuffles the tripwire in his hands and pitch shifted each subsequent shuffle to keep it from sounding repeated. Additionally, cloth movement is overlaid to better simulate the movement cyphers' arms are doing to mimic the movement during the ability pullout.

![Tripwire Pullout Work Image](/assets/images/writeup-images/TripwireWorkImage.png){: .align-center}

The idea of a poker chip came directly from Cyphers backstory and reputation as a "high roller" in the universe of Valorant making shady deals and such.

##### Designing the placement of the tripwire

Next is the placement of the Trip, which I made with various samples including A piece of metal being scratched on stone to indicate the attached surface, heavily manipulated Air hissing for the deployment, and a camera shutter for the final lock of the mechanism.

![Trip Placement Work Image 1](/assets/images/writeup-images/TripwireSample1.png){: .align-center}
![Trip Placement Work Image 2](/assets/images/writeup-images/TripwireSample2.png){: .align-center}
![Trip Placement Work Image 3](/assets/images/writeup-images/TripwireSample3.png){: .align-center}


#### Designing the tripwire recall. 

![Tripwire Recall Image](/assets/images/writeup-images/TripwireRecallExample.png){: .align-center}

For the recall of the trip I used a "fusion driver" preset on Alchemy to mimic the "magnetic" energy that cypher seemingly recalls the tripwire with.

I reversed the original synthesized sound to have it get faster as the tripwire gets close to cyphers glove, to mimic the feeling of a magnetic pull between cyphers glove and the tripwire

### Designing the Camera and it's placement. 

Finally for the camera, every part of the sound here is sampled as opposed to the cage, or tripwire. 

![Camera Placement Example Image](/assets/images/writeup-images/CameraPlacementExample.png){: .align-center}

The placement sound of the camera is a lock being closed. and the sound of the camera opening is simply a camera shutter moving.

The main choice for these samples was simply what sounds closest to a metal attachment and a camera priming.

![Camera Sample Images](/assets/images/writeup-images/CameraSample1.png){: .align-center}
![Camera Sample Images](/assets/images/writeup-images/CameraSample2.png){: .align-center}
