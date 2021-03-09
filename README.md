# Audio Splitter Cable
![alt text](img/trigbox_and_splitter.png)

## Purpose
When performing electrophysiological experiments with auditory stimuli, you often want to know when the auditory stimuli are presented to the subject. This is often done by duplicating the auditory stream to another device, such as the g.tec gTRIGbox, which detects the stimuli' onset. A problem is introduced if you have multiple different stimuli with differing envelopes as the time it takes for the trigger to occur may vary. This cable attempts to solve this problem by allowing you to clearly define what point during your stimuli you want the trigger to occur.  

## How to Connect the Hardware
The male end of the 3.5mm audio cable goes into the PC. The black female 3.5mm audio cable connects to the gTRIGbox, and the red female 3.5mm cable goes to headphones. The red connector that goes to the headphones has another plug that converts mono to stereo.

## Setting Up the Audio File
![audacity](img/audacity_screenshot.png)

You will have to modify the audio stimuli using a program like Audacity. The auditory stimuli should be on the right channel, and the trigger (which is a constant frequency beep) should be on the left channel, as shown in the image above. This audio file in its "non-split" form and split form are included in this repository under the name `stimuli_train_non-split.wav` and `stimuli_train_split.wav`, respectively.

Now, when playing back the audio file through the splitter, the beep in the left channel will be routed to the gTRIGbox, and the audio stimuli on the right channel will be converted to stereo and presented through the headphones.
