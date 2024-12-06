+++
date = '2024-11-27T15:47:02+01:00'
draft = false
title = 'Introduction to Brain-Computer Interfaces'
author= 'Dr Soukkou Youcef'
+++

{{<audio src="transcripts/luvvoicecom-20241206-88xm7b_Ah2bwO5C.mp3" caption="Listen to audio version">}}


## Introduction

Brain-Computer Interfaces (BCIs), or sometimes called "Brain-Machine Interfaces (BMIs)" are a relatively new concieved piece of technology that integrate the huge advances made in the last 2 decades or so in computer hardware (GPUs), computer software (Deep Neural Networks) as well as advances in material science and automated neurosurgery. BCIs aim to revolutionize human interactions with each other as well as interfacing with In-Silico hardware to enhance human cognitive abilities or to restore lost functions (eyesight, hearing in pathologies such as amyotrophic lateral sclerosis, cerebral palsy, stroke, or spinal cord injury... etc).
BCIs capture brain signals from neurones in a particular region or regions (e.g Motor cortex) of the brain where they're implanted and learn through neural networks the specific electrical neural firing patterns of each brain activity whether it's a thought or an action. The broader goal of these devices is to amplify the human brain's output bandwidth.

## The Basics
It's very hard to explain the idea of adding another digital layer of congnition to the biological structure that is the brain, the idea of 'interfacing' with the cortex seems vague and almost 'science-fiction' grade. But in truth, it has been done for so many years, the biggest issues aren't conceptual, they are practical, how do we make micro-electrodes that can capture unitary neurone activity without causing damage to nearby blood vessels, glia cells, and especially without provoking an immune reaction. Then how do we take all those signals and process them and give an output that is compatible with already existing brain circuits. These are the big challenges on a high level kind of thinking. If you look closely, you might just find the damn thing too complexe. I mean, we are dealing with engineering issues that intersect a wide range of different fields, immunology, material sciences, pathology, neurosurgery, signal processing, software engineering, and the list goes on and on.
Below is a simplified diagram showing the elemental steps in a simple design and implementation of a BCI.
![alt](https://www.researchgate.net/profile/Xiaorong-Gao/publication/227176331/figure/fig3/AS:667775211151379@1536221425653/Diagram-of-a-BCI-based-on-the-modulation-of-brain-rhythms.png)

In the olden days, people used to record brain activity in an awkward way, using an EEG, which typically has 25 electrodes. As one might guess, this is largely insufficient when we comparatively look at the hundereds of billions of neurones operating in a vastly more complex network in 3D space. But luckily, in recent years, the use of neural laces became common. I still have this article from 'Nature' in 2015 kept in my drawer somewhere talking about how a team of nano and neuroscientists created a flexible conductive mesh made of a polymer that they injected in the brain of a rat and were sucessfully able to record the activity of millions of neurones with much more than 25 electrodes. At the time reading this kind of stuff was like reading science fiction (Original Source: [Injectable meshes for neural recordings
. Nature 30 July 2015](https://www.nature.com/articles/nmeth.3511)
)
The mesh had transistors at the intersection of its lines which also had the same elasticity and flexibility as brain tissue. Therfore, eliminating the risk of losing neuron data when cells move with different blood flow conditions and other hemodynamic variabilities as well as mechanical changes. The team reported no pathological immune response even after 5 weeks of implanting the mesh.
This was a huge milestone back then. Fast forward almost 10 years later, and we now have 'Neuralink' a biotechnology company in silicon valley that successfully implemented BCIs in monkeys, allowing him to play the famous game 'pong' without the need for a joystick. See the video below :
{{< youtube rsCul1sp4hQ >}}

The team at neuralink are now in the phase of clinical trials, with their first ever patient 'Noland Arbaugh' who is tetraplegic. Upon recieving a neuralink chip he was able to play "Counter Strike" on his computer just by using his own thoughts. The possibilities of integrating the brain signals of his neuralink are limitless, smart prostethic limbs, computers, smart devices, etc the sky is the limit after the chip increases how much bandwidth your brain can output at each second.
And the examples of practical use are also endless, this was just one, being able to recover motor function after a spinal cord injury. The technology is so powerful, it can be used to cure peripheral blindness, where the neural lace acts as an artifical eye with its own optic nerve equivalent and sends electrical signals to the visual cortex in the same way a normal optic nerve does. Of course, it's not as simple or easy as it seems since the vision problem is a highly complex example of human physiology and anatomy and would require years of deciphering exactly how the eye and the visual cortex interface with each other in normal physiological conditions.  


## The Symbiosis
There are a bunch of fallacies that people always resort to when they know of this kind of technology. Mainly it either has to do with the ethical side of whether it is a dangerous thing to implement or the other side which is the technical impossibility of interfacing organic vs non-organic computers. I don't personally dable with the ethical bullshit, so i'm goona try to address the technicals instead.
The BMI does not have to adjust to the brain, its job in theory is relatively simple, capture elemental neurones firing and a region of the brain that we already know its function, try to learn from that data useful patterns using machine learning, and then do calculations to determine an output that then gets to be sent back to organic neural network since we have access to individial neurones. Thus, the problem of interfacing is not an issue, but rather, an illusion.
It's much like neural networks. We haven't got a clue on how they work inside and out but know how the learning algorithm works, it's a blackbox that we can't predict yet we can understand in theory.
I personally see no problem with adding the hard silicon layer to the brain, I can see a bright and incredible future for humans when BCIs become common. It's the only way I see our race competing with artificial super intelligence.
