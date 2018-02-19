# Methodology for data collection for voice corpora

Starting with rough points to address:

- Sentences should come from an open data source, preferrably public domain.
  - What type of source should be preferred? Written? Transcripts of spoken? News, articles, books, social media?
  - What type of register should be preferred?
  - How modern should be the source? Is there any use for older data sources?

- The data set should be constructed to provide good coverage of different language components and aspects:
  - Words
    - Inflections: How good a coverage can and should we aim for? Which types of inflections (gender, tense, number, person, mood, etc.)?
  - Phonemes? 
  - Accents? Gender or age of speakers? Geographical origin? What is even feasible here?
  - Are any properties of word and/or phoneme frequency distribution in the language be kept? If so, distribution measured/obtain on what corpora (should they be estimated on written corpora)?  

- Should data on contributers be collected and kept, if possible? If so, which? Age, gender, etc.

- A train/validation/test split should be determined beforehand.
  - What is a proper ratio?
  - It should be constructed such that no sentence overlap is present between the different splits. [source: https://github.com/mozilla/voice-web/issues/806]
  - Once collection begins, it should be managed such that no speaker overlap is present between the different splits. [source: https://github.com/mozilla/voice-web/issues/806]
  - Validation and test utterances are all unique utterances (no repetitions). [source: https://github.com/mozilla/voice-web/issues/806]
  - Train set may have utterance repetitions, but not too much. How much is too much? [source: https://github.com/mozilla/voice-web/issues/806]
  - Also, if all of the above is kept, the validation and test set (or the validation and train set) can always be joind to get just a train-test split with different ratios.

- A minimum dataset size (taking splits ratios into account) enabling research applications should be determined beforehand.

- What instructions should be given to recorders?
  - Record in a quiet place?
  - Any other enviroment characteristic to be requested/avoided?
  - Any limit on the number of consecutive sentences recorded?
  
- Should metadata on recordings be kept?
  - Device model, microphone model, etc.
  - Time of day, consecutive recordings, etc.
