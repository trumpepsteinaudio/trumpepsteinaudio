<b>Let's put our AI audio processing skills to good use.</b>

We sure would like to know what Trump and Epstein said to each other during this exchange in the 90s. https://www.youtube.com/watch?v=KLcfpU2cubo&feature=youtu.be
Unfortunately, the song "Rhythm is a Dancer" by Snap! is playing loudly. With the correct reference track, it is possible that an echo canceller can remove the music and expose the conversation. Let's try it as a collective.

In an echo canceller, the reference track is signal that you want to remove. In this case, it would be a clean recording of the song playing in the club. You can use AI to build a model of the music track in the club so that it can be removed. 

<b> FIRST PROBLEM </b>: The official version of this song (below) does not appear to be the one playing in the club. 

<b> Can you help us find (or construct) the perfect reference track?</b> 
You can submit to this repo or mailto: trumpepsteinaudio@gmail.com.

A complete listing of the versions of this song are on wikipedia https://en.wikipedia.org/wiki/Rhythm_Is_a_Dancer#Track_listing_and_formats. Known song versions is in a text file in this repo. You can edit, or indicate which ones should be removed. 

If you want to download youtube videos https://ytdl-org.github.io/youtube-dl/ is an easy command-line utility.


Once the reference track has been identified, let's try some echo cancellers.

A standard open source version is available here: https://www.speex.org/ (see Acoustic Echo Canceller)

A python implementation is here: https://github.com/xiongyihui/speexdsp-python

Apple has done advanced work in this space: https://machinelearning.apple.com/research/optimizing-siri-on-homepod-in-far-field-settings

Successful models might want to submit to the Acoustic Echo Cancellation Challenge at ICASSP 2021 (organized by Microsoft)

Beyond echo cancellation, you might want to try models that use video to select a target voice such as:
https://arxiv.org/abs/1804.03619 and https://arxiv.org/pdf/1804.04121.pdf

Or you might want to try video-to-audio lipreading models:
http://cvit.iiit.ac.in/research/projects/cvit-projects/speaking-by-observing-lip-movements

Send us any references/links/code that could be useful, and we will post here.

Repo contains the starting files.
