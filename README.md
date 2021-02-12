# Audio Splitter Cable
![alt text](img/trigbox_and_splitter.png)

## Purpose
When performing electrophysiological experiments with auditory stimuli, you often want to know precisely when the auditory stimuli is presented to the subject. This is often done with a device such as the g.tec gTRIGbox. If the stimuli have different envelopes, the time it takes for the trigger to occur may vary. This cable removes this possibility and allows you to clearly define what point during your stimuli you want the gTRIGbox to trigger.  

## How to Connect the Hardware
The cable has three ends, one that goes into the PC, one that goes to the g.tec gTRIGbox, and one that goes to headphones. The end that goes to headphones has another plug that converts mono to stereo.

## Setting Up the Audio File
![audacity](img/audacity_screenshot.png)

You will have to modify the audio stimuli using a program like audacity. The auditory stimuli should be on the right channel, and the trigger (which is a constant frequency beep) should be on the left channel, as shown in the image above. This file in the form of a `.wav` and audacity project is included in this repository under the name `stimuli_train`.

Now, when playing back the audio file through the splitter, the beep in the left channel will be routed to the gTRIGbox, and the audio stimuli on the right channel will be converted to stereo and presented through the headphones. 