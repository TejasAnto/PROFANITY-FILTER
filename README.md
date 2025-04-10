# PROFANITY-FILTER
A profanity filter that uses sentiment analysis and toxicity detection to intelligently censor swear words in funny/lighthearted contexts while blocking and warning for truly aggressive/threatening messages.

# A Python tool that intelligently filters profanity using:

  >> Word censoring -> (replaces swear words with ****)
  >> Context detection -> (allows casual swearing, blocks true toxicity)
  >> Sentiment analysis -> (VADER) + Toxicity detection (RoBERTa-HateSpeech)

# Key Features:
  >> Real-time input processing
  >> Distinguishes jokes from hate speech
  >> Customizable word lists and thresholds
