What is the just noticeable difference (JND) for the brightness of a sound?

Research Question And Relevance
What is the just noticeable difference (JND) for the brightness of a sound? The spectral centroid is directly connected to the subjective perception of brightness. The aim of this research is to find what’s the smallest variation in the spectral centroid of the spectrum of a sound sample, that creates noticeable variations in brightness. 

It is important to notice that within the framework of current research, we use the notions of brightness and spectral centroid interchangeably. Although there were proposed many different definitions of brightness, it is still an open and quite complex question how such a purely subjective concept as brightness can be measured and quantified. Therefore, we decided to use the most popular definition of brightness as a spectral centroid, since we believe it will be adequate for the purposes of measuring the JND.

We decided to focus on sounds with broad spectral information, specifically we use pink noise samples with limited bandwidth. Thus, we will be able to study brightness perception of a sound independently of its timbre. Two groups of people will be tested: with and without musical knowledge. As a consequence, apart from determining the JNDs for brightness, we will see if the characteristics of the sound and the type of listeners influence the JND. 

This study could be relevant to determine the subjectivity of brightness perception, the influence of musical background into listening skills and the importance of adaptive listening in the perception of sound characteristics. In addition, the discovered information could be useful to develop some audio tools like for example a brightness plug-in. This plug-in could consist of a scroll bar of steps, to modify brightness. Each step would be determined by the JND we propose.

Research Question condensed : How much of a shift in the spectral centroid must occur before a difference in perceived brightness can be observed ?

CHOICE OF SOUND
The sounds presented in our experiments will be pink noise sounds. Each sample will be a narrowed band version of pink noise with different low and high limits. 

STIMULI
Just like some other psycho-acoustic phenomenon like pitch or loudness, brightness perception changes with respect to frequency. Therefore,we want to get more accurate and trustable JND values that can be generalized for the whole spectrum. In order to do that, we are going to divide the frequency spectrum into four bands:  

Low: 20Hz - 200Hz
Mid-low: 200Hz-1kHz
Mid-high: 1kHz-3kHz
High: 3kHz-8kHz

The procedure for generating the stimuli will be the following:
We will generate one base sound for each frequency band (A1 for low frequency band, A2 for mid-low frequency band, A3 for mid-high frequency band, A4 for high frequency band). Each An will be obtained by applying Low-Pass + High-Pass filters to the pink noise sound. For each band, different cut off frequencies will be used. These limits will be determined by the band limits exposed in the previous paragraph. So our base sounds for each band will be:
Base sound for low-band: band-passed-filtered pink noise with cut off frequencies fL=20Hz  and fH=200Hz
Base sound for mid-low-band: band-passed-filtered pink noise with cut off frequencies fL=200Hz  and fH=1kHz
Base sound for mid-high-band: band-passed-filtered pink noise with cut off frequencies fL=1kHz  and fH=3kHz
Base sound for high-band: band-passed-filtered pink noise with cut off frequencies fL=3kHz  and fH=8kHz

Later, for each An we generate a series of four sounds Bn0, …, Bn4 by selecting a different band of pink noise, very close to the band of An. Namely, we set Bnk to be the result of “upward band” version of An. 
Inside each bands, the step between Bnk and Bn(k+1) is the same, but between different bands, it is different, since brightness perception changes along frequency. The steps have been manually selected by the authors of this project, by generating loads of samples and : establishing Bn0 sample to be nearly indistinguishable from An in terms of brightness and Bn4 sample to be distinguishable enough from An in terms of brightness.
After this process of selecting appropriate Bnk, these are the limits for the LPF and HPF applied to the pink noise to generate the samples:



LOW 
MID-LOW
MID-HIGH
HIGH
 An
fL=20Hz   fH=200Hz
fL=200Hz   fH=1kHz
fL=1kHz   fH=3kHz
fL=3kHz fH=8kHz
Bn1
fL=27.5Hz   fH=207.5Hz
fL=212.5Hz   fH=1012.5Hz
fL=1015Hz   fH=3015Hz
fL=3050Hz   fH=8050Hz
Bn2
fL=35Hz   fH=215Hz
fL=225Hz     fH=1025Hz
fL=1030Hz  fH=3030Hz
fL=3100Hz   fH=8100Hz
Bn3
fL=42.5Hz   fH=222.5Hz
fL=237.5Hz   fH=1037.5Hz
fL=1045Hz   fH=3045Hz
fL=3150Hz   fH=8150Hz
Bn4
fL=50Hz   fH=230Hz
fL=250Hz     fH=1050Hz
fL=1060Hz
fH=3060Hz
fL=3200Hz   fH=8200Hz
Step (Hz)
7.5
12.5
15
50


All of the samples have equal loudness =  -26.5 LUFS.
	
	Once all the samples are generated, a calculation of the spectral centroids has to be computed. Of course, the centroid of An will be smaller than the centroid of An+1 and the centroid of Bnkis smaller than the centroid of Bn(k+1)

CENTROIDS:


LOW 
MID-LOW
MID-HIGH
HIGH
 An
121.199Hz
573.386Hz
1952.742Hz
5382.496Hz
Bn1
128.053Hz
584.055Hz
1968.506Hz
5473.200Hz
Bn2
135.567Hz
595.810Hz


1984.198Hz
5526.11Hz
Bn3
145.510Hz
612.470Hz
1999.860Hz
5578.901Hz
Bn4
159.503Hz
628.004Hz
2015.468Hz
5631.549Hz



Finally, we must select how to organize the generated stimuli in the questions for the test. The test, as it will be explained later in another section, will be composed of 21 questions. In each question, two samples will be presented.
The pairs of sounds to be presented to our subjects are (An, Bnk) for n=1...4, k=0...4. Between every pair of samples there is a difference in the spectral centroid given by DifferenceCentroidCents=1200·log2(centroidBnk/centroidAn)

Questions for each band:
(An, An)
(An, Bn1)
(An, Bn2)
(An, Bn3)
(An, Bn4)

That makes 5 questions x 4 bands = 20 questions. In addition, we are also adding a “trick” question where two samples are very different in brightness to control which subjects provide truthful answers. This serves as calibration to the test: if the difference is too big, the other pairs will sound too similar or equal in brightness; if they are too similar, people won’t be able to differentiate them and that’s important for the next point. Those subjects that answer this question wrong will be discarded, and their answers won’t be considered.
Control question pair is formed by:
Mid-band with  fL=1kHz   fH=3kHz
Mid-band with fL=1kHz   fH=3kHz

Once we have constructed the pairs, we will put the pairs in the questionnaire in random order (except for the control question, which will always go first). 

Image. Example of question selection					
VARIABLES
Parameters to manipulate (independent variables):
Frequency band limits
Spectral centroid of a sound

The other important parameter we are taking into consideration is loudness:
We will normalize all sounds so that they have equal loudness (-26.5 LUFS) because there might be an additional dependency between brightness perception and loudness, and we want to avoid that.

Dependent variable:
Brightness sensation

SUBJECTS
The experiment will include two subject groups of 15 integrants each: one experimental group of people with no musical-background and another one with people that play an instrument, produce music or similar. The reason for this is to find out whether there is a difference in how these different groups perceive brightness, and therefore, see if we can find different JNDs. 

TEST - EQUIPMENT
The pink noise sound was generated using  Audacity.
We then processed and edited them using the reliable and industry-standard tool Reaper and the plug-in Fabfilter Pro Q.

The test will be done in dual channel mono, the participants will be asked to wear headphones. The frequency response of the headphones must be as flat as possible.
The test will be conducted through the online tool PsyToolkit.

TEST - INSTRUCTIONS
The instructions presented at the beginning of the test will the following:
As you can see in the images above, the main page of the test has some very clear instructions.
An introductory explanation of the test is given, as well as an example of two sounds, bright and dark.
The subject is told to adapt their volume to approx. 50%.
Some information about us, the creators of the test.
Technical requirements advising to check the correct functioning of the headphones.
The subject confirms that wants to participate in this test and that is aware of the information we collect.

In order to distribute the test, we have created a document with some additional information for the subject to better understand the matter, and a link to the test.

Link to this document
TEST - PROCEDURE
Initially, the following questions are asked to the subject:



Then, as mentioned before, the test consists of 21 simple and quick questions. In each of them, we will show the subject a pair of samples. In each pair, both samples present different brightness levels. We will ask the subjects if they think both samples present the same brightness or not. The interface will be similar to the following image.



At the end of the test, we are including this in order to get some feedback from the subjects.

DATA ANALYSIS
In order to calculate the spectral centroid this we can rely on libraries such as Essentia or Librosa. 
The general formula for the computation of the S.C. is:
Spectral Centroid =k=1NkF[k]k=1NF[k]
In which F [k] is the amplitude corresponding to bin k in the DFT spectrum.


ANALYSIS OF SUBJECTS’ ANSWERS

Once the subjects have answered all of the questions, their answers will be stored in a csv file. In each question, we have the information corresponding to: 
Pair of audio samples involved
Difference in their spectral centroids
One answer per participant declaring whether they think that left sound is brighter, right sound is brighter, or there is no difference.

We will re-organise the answers according to b), from big differences in centroids down to very small differences in centroids. Then, we could plot in a circular chart each question, with two sections: “right” and “wrong” answers. Hopefully, we will see that at the beginning most people choose the sound with the higher brightness, but as we move down the csv file, people will start switching to agree that both samples of the pair are as bright. The JND will be determined by that first circular chart that shows that more than 75% of participants gave the right answer.



REFERENCES
Allen, Jont B., and Stephen T. Neely. 1997. “Modelling the Relation between the Intensity Just-Noticeable Difference and Loudness for Pure Tones and Wideband Noise.” The Journal of the Acoustical Society of America 102 (6): 3628–46. https://doi.org/10.1121/1.420150.
Almeida, Andre, Emery Schubert, John Smith, and Joe Wolfe. 2017. “Brightness Scaling of Periodic Tones.” Attention, Perception, & Psychophysics 79 (7): 1892–96. https://doi.org/10.3758/s13414-017-1394-6.
Cousineau, Marion, Samuele Carcagno, Laurent Demany, and Daniel Pressnitzer. 2014. “What Is a Melody? On the Relationship between Pitch and Brightness of Timbre.” Frontiers in Systems Neuroscience 7. https://doi.org/10.3389/fnsys.2013.00127.
Dye, Raymond H., and Ervin R. Hafter. 1980. “Just‐noticeable Differences of Frequency for Masked Tones.” The Journal of the Acoustical Society of America 67 (5): 1746–53. https://doi.org/10.1121/1.384301.
Manocha, Pranay, Adam Finkelstein, Richard Zhang, Nicholas J. Bryan, Gautham J. Mysore, and Zeyu Jin. 2020. “A Differentiable Perceptual Audio Metric Learned from Just Noticeable Differences.” arXiv. http://arxiv.org/abs/2001.04460.
Prawda, Karolina, Vesa Valimaki, and Stefania Seraﬁn. 2020. “Evaluation of Accurate Artiﬁcial Reverberation Algorithm,” 8.
Schubert, Emery. 2006. “Does Timbral Brightness Scale with Frequency and Spectral Centroid?” ACTA ACUSTICA UNITED WITH ACUSTICA 92: 6.
Schwendicke, Anna, and M. Ercan Altinsoy. 2020. “Frequency Masking Effects for Vertical Whole-Body Vibration for Seated Subjects.” Vibration 3 (4): 357–70. https://doi.org/10.3390/vibration3040024.
Siedenburg, Kai. 2018. “Timbral Shepard-Illusion Reveals Ambiguity and Context Sensitivity of Brightness Perception.” The Journal of the Acoustical Society of America 143 (2): EL93–98. https://doi.org/10.1121/1.5022983.
Siedenburg, Kai, Feline Malin Barg, and Henning Schepker. 2021. “Adaptive Auditory Brightness Perception.” Scientific Reports 11 (1): 21456. https://doi.org/10.1038/s41598-021-00707-7.

About Harmonic Distortion measurements: https://www.listeninc.com/resources/technical-notes/harmonic-distortion-measurement-the-effects-of-sampling-rate-and-stimulus-frequency-on-the-measured-harmonic-frequency-including-thd-and-rub-buzz/

About Spectral Centroid: https://ccrma.stanford.edu/~unjung/AIR/areaExam.pdf

ANNEX I - Link to audio files

Low
Low-Mid
Hi-Mid
Hi Mid
low_20_200
low_mid-200-1000
hi-mid-1000-3000


low_27_207
low_mid-212-1012
hi-mid-1015-3015


low_35_215
low_mid-225-1025
hi-mid-1030-3030


low_42_222
low_mid-227-1037
hi-mid-1045-3045


low_50_230
low_mid-250-1050
hi-mid-1060-3060





Control question:
hi-mid-1000-3000
1100-3100Hz: https://drive.google.com/file/d/1ZEJl-qlpx5UAWlbwC-ntPSEnvCFFdcIU/view?usp=sharing 



ANNEX II - Questionnaire code


l: Name
t: textline
q: Name and Surname
- Please enter your name and surname here

l: Personal_Age
t: textline
q: How old are you?
- {min=14,max=80} Please enter your age here

l: Personal_Music
t: radio
q: What's your relation with music?
- None
- I listen to music daily but I don't have any other relation
- I play an instrument and have some knowledge
- I am a professional musician /producer/music creator/similar...

l: Headphones
t: radio
q: What type of headphones are you using?
- {image=in_ear.png}
- {image=over_ear.png}

l: Ready
t: radio
q: Now, the test begins. It consists of 21 questions.
- Okay

l: Question_Control_Different
t: radio
a: control-1100-3100-fade.wav hi-mid-1000-3000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

random: begin

l: Question_low_AA
t: radio
a: low_band-20-200-fade.wav low_band-20-200-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_low_AB1
t: radio
a: low_band-20-200-fade.wav low_band-27-207-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_low_AB2
t: radio
a: low_band-20-200-fade.wav low_band-35-215-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_low_AB3
t: radio
a: low_band-20-200-fade.wav low_band-42-222-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_low_AB4
t: radio
a: low_band-20-200-fade.wav low_band-50-230-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>


l: Question_lo_mid_AA
t: radio
a: low_mid-200-1000-fade.wav low_mid-200-1000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_lo_mid_AB1
t: radio
a: low_mid-200-1000-fade.wav low_mid-212-1012-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_lo_mid_AB2
t: radio
a: low_mid-200-1000-fade.wav low_mid-225-1025-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_lo_mid_AB3
t: radio
a: low_mid-200-1000-fade.wav low_mid-237-1037-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_lo_mid_AB4
t: radio
a: low_mid-200-1000-fade.wav low_mid-250-1050-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>


l: Question_hi_mid_AA
t: radio
a: hi-mid-1000-3000-fade.wav hi-mid-1000-3000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_hi_mid_AB1
t: radio
a: hi-mid-1000-3000-fade.wav hi-mid-1015-3015-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_hi_mid_AB2
t: radio
a: hi-mid-1000-3000-fade.wav hi-mid-1030-3030-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_hi_mid_AB3
t: radio
a: hi-mid-1000-3000-fade.wav hi-mid-1045-3045-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_hi_mid_AB4
t: radio
a: hi-mid-1000-3000-fade.wav hi-mid-1060-3060-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>


l: Question_high_AA
t: radio
a: high-3000-8000-fade.wav high-3000-8000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_high_AB1
t: radio
a: high-3000-8000-fade.wav high-3000-8000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_high_AB2
t: radio
a: high-3000-8000-fade.wav high-3000-8000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_high_AB3
t: radio
a: high-3000-8000-fade.wav high-3000-8000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

l: Question_high_AB4
t: radio
a: high-3000-8000-fade.wav high-3000-8000-fade.wav
q: Listen to both samples and choose one of the following:
- The FIRST sample <u>is brighter</u> than the SECOND sample
- The SECOND sample <u>is brighter</u> than the FIRST sample
- BOTH samples are <u>equally bright</u>

random: end

l: Final
t: textbox
q: END OF THE TEST. How was the test? Express your thoughts (You can use the language you feel most comfortable with)
- {w=100%,h=5}








