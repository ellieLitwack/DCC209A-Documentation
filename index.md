# Body Swap VR: A Body Scan Meditation in Another Person’s Body
An exploration of gender, bodies, and virtual reality by Ellie Litwack

## Abstract 
Other people’s bodies can feel so foreign: it’s difficult to even imagine how having a different shape or appearance would feel. This virtual reality experience takes “walking in someone else’s shoes” to another level: you see a real person’s body, from their perspective, captured using panoramic video. By matching your movements to those in the video, you feel a deeper sense of immersion. The experience is meant as a jumping off point for inquiry: how do other people see the person in the video? How do they see themselves?  How do the differences between your body and theirs shape your experience?

## Final Project Images
Below are examples of what the user would see when using the final version of the experience.
![alpha shorts][shorts]
![alpha jeans][jeans]
![lower view 1][lowerfinal1]
![ lower view 2][lowerfinal2]

## Documentation of Capstone Fair
I presented the final version of my project at the DCC capstone fair. Several people got the opportunity to try the experience for themselves.
![woman trying][capstone1]

Meanwhile other attendees could see a projection of the participant’s view on a nearby monitor.
![outside view][capstone2]

I had the opportunity to talk with participants and learn about their reactions. Most were surprised at how immersed they became in the experience. “That was incredible,” one said. “I truly felt like I was in a different body.” Another participant said he eventually started to perceive the body in the video as under his control. “Towards the end, I moved my foot, and I was so surprised when the foot in the video didn’t move with me.”

In addition to these more superficial observations, multiple participants highlighted that the similarities between their bodies and the body in the video were more noticeable than the differences. “I looked down and immediately thought, this seems like my body,” one person said.

“I wish she [the person in the video] had been more full-figured. Like, I wish she had a large bosom,” one woman said. “But as it is, I looked down and thought, ‘well that’s about what I’ve got.’”

When people did find differences between themselves and the body in the video, they quickly forgot about them. A black person who tried the experience said, “at first, I noticed it [the difference in skin color between herself and the body in the video], but after a minute I wasn’t thinking about it at all.”

The noisy, public environment proved to be the greatest issue for the experience. Many people weren’t comfortable putting on a VR headset with others around. If I were to show it again, I would want to do so in an environment where I could sit one on one with participants.

## Blog
These posts document the iterative development of the project
### Paper Prototype: 180-degree "Spatial Storyboard"
A normal storyboard is a comic-book like, shot-by-shot sketch of the temporal progression of a piece of media. This spatial storyboard instead explores the spatial path that a viewer’s gaze might follow as they are immersed in this virtual reality experience.
![Layout of story board views][paperPrototype]

### User Feedback Incorporated Prototype
Four users used an initial prototype of the VR experience. Several common themes were present in their feedback. Each of these was addressed to create a user feedback incorporated prototype.

- Video Stability:
Users noticed small amounts of shaking in the video, which was caused by an unsteady camera. A process was developed to correct for this instability. High contrast markers were securely attached to walls in the field of view of the camera. The motion paths of the markers were reconstructed digitally. This was used to "cancel-out" the unsteadiness of the camera. After this effect was applied, users did not notice any video stability issues. Below: Reconstructed paths of high contrast markers.
![High contrast marker paths][markers]

- View Angle:
With the initial prototype, viewers complained that they had to strain their heads in order to get a good view of the virtual body. The pitch of the camera was digitally adjusted by 60 degrees. Despite the fact that this moved the visual location of the virtual body away from the location of the user's actual body, users reported that they felt more immersed after the angle and *believed* that the location of the virtual body was the same as the location of their actual body. Below: The initial view transforms, as shown by the arrows, to bring more of the body into the user's comfortable field of view (FOV).
![initial image][init]
![corrected image][correct]

- Clothing:
Users lost immersion when the location of their clothes did not match the location of the clothes on the virtual body. Now, users will be instructed to wear clothes that are similar to those worn in the video.

### Alpha Build
Several improvements were made between the prototype and the alpha build. A high-quality lighting environment was used to improve the visuals.
![lighting][lighting1]
![lighting][lighting2]

A mirror was added so the user can see more of the virtual body, resulting in a more thought-provoking experience. Two versions were created, one with long pants and the other with shorts, to accommodate the variety of clothing that users might wear during the experience. Overall, the alpha build represents a final visual product that still lacks audio.

![alpha shorts][shorts]
![alpha jeans][jeans]


### Beta Build
No images are included as no visual changes have taken place since the alpha build. A technical challenge that arose in creating the beta build was rendering the video. This is difficult due to the large amount of time required to process the video. Rendering of one of the two videos was initiated on the lab computer on Tuesday April 24th and is expected to complete by 4:30 PM on Wednesday April 25th assuming that no one shut down the computer during the day. The second video will be rendered after the first is complete.

The main component of the beta build was creating audio to accompany the visual experience. I decided against my initial plan of using a personal narrative of the person in the video because I felt it distracted too much from the already busy experience. After several iterations, I settled on a narration that draws inspiration from the concept of a body scan meditation. The user is asked to ground themselves and focus simply on how their body feels. The user can then reflect on the significance of the experience afterwards.

As the audio cannot be added to the video until rendering has completed, a transcript is below.

#### Transcript
Focus your attention on the souls of your feet. Now, raise your left and hand stretch out your fingertips. Raise your right hand and feel your clenched fist. As you move your hands, feel each part of your body. Finally, drag your hands up your body to trace out the shape of yourself, and then drag them back down. Return your attention to the souls of your feet.

## Author Bio
Ellie Litwack is a mechanical engineering student at the University of Maryland.

[paperPrototype]: https://i.imgur.com/lMmCdsK.jpg
[init]: https://i.imgur.com/XF2Gr3n.jpg
[correct]: https://i.imgur.com/nD3nzBe.jpg
[markers]: https://i.imgur.com/wIMIwSf.png
[shorts]: https://i.imgur.com/YNQjArl.jpg
[jeans]: https://i.imgur.com/IhkVFqJ.jpg
[lighting1]: https://i.imgur.com/IACb2pe.jpg
[lighting2]: https://i.imgur.com/u64Ew9M.jpg
[lowerfinal1]: https://i.imgur.com/itPiCIq.jpg
[lowerfinal2]: https://i.imgur.com/6kuhMin.jpg
[capstone1]: https://i.imgur.com/m4DOrbr.jpg
[capstone2]: https://i.imgur.com/sSQS8nz.jpg
