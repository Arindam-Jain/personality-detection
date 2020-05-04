
INTRODUCTION

The dataset includes the following material:

1) audio files
2) raw personality questionnaires
3) personality assessments
4) metadata

If you use the database, you are kindly invited to cite the
following paper where you will find extensive information about
the data:

G.Mohammadi and A.Vinciarelli
"Automatic Personality Perception: Prediction of Trait Attribution
Based on Prosodic Features"
IEEE Transactions on Affective Computing, Vol. 3, no. 3, pp. 273-284, 2012

Should you have any question, please contact the following persons:

Alessandro Vinciarelli (vincia@dcs.gla.ac.uk)
Gelareh Mohammadi (gelareh.mohammadi@idiap.ch)


THE DATA

1) Audio files

The dataset includes 640 audio clips of 10 seconds (see paper
above for full description of the content).

Audio files directory: ./Audio_clips
Audio files format: .WAV files(16 bit, mono, 8 kHz) 


2) Raw Personality Questionnaires

This dataset includes the raw questionnaires filled individually
by 11 assessors. The questionnaires correspond to the BFI-10
items (see the paper above for further information):  

#1. This person is reserved 
#2. This person is generally trusting 
#3. This person tends to be lazy 
#4. This person is relaxed, handles stress well 
#5. This person has few artistic interests
#6. This person is outgoing, sociable 
#7. This person tends to find fault with others 
#8. This person does a thorough job 
#9. This person gets nervous easily 
#10. This person has an active imagination 

The answers range from "Strongly Disagree" (1) to
"Strongly Agree" (5).

Raw Personality Questionnaires directory: ./BFI_Item_Answers 
Raw Personality Questionnaires format: comma separated values (csv)


3) Personality assessments

The dataset includes the personality scores assigned individually
by the 11 assessors. The scores are obtained from the raw personality
questionnaires (see the paper above for further information).

The five scores corresponds to the following traits:

Extraversion
Agreeableness
Conscientiousness
Neuroticism
Openness

Personality Assessments directory: ./Personality_Scores
Personality Assessments format: comma separated values (csv)


4) metadata

The dataset includes metadata for each audio sample (see the
paper agove for further information):

speaker ID (integer between 1 and 322)
gender ("M" for male and "F" for female)
status ("J" for journalist and "G" for non-journalist)

metadata directory: ./Metadata
metadata format: comma separated values (csv)