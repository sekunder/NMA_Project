# NMA_Project
Group project for Neuromatch Academy, summer 2020.


#### Scientific question

How does neural encoding of simple visual stimuli (with few easily-described parameters) in mouse primary visual cortex relate to encoding of more complex visual stimuli (e.g. a cartoon of Minnie Mouse)? How do animal behaviors relate to these encodings? Can the decoding be improved by learning a modulation relationship between behavior and neural activity from spontaneous activity?

#### Brief scientific background

It is not fully understood how V1 encodes simple and complex stimuli. Neill and Stryker (2010) showed that sensory systems are modulated by locomotion, and more recently, Churchland et al. showed that neural activity is dominated by behavior (“fidgeting”).

#### Proposed analyses

We will use GLMs and other machine learning methods to decode stimuli from V1 activity. We will compare the performance of decoders which do or do not incorporate  spontaneous behavior, such as whisking, saccades, and running.

Using dimensionality reduction techniques, we will consider how spontaneous (not stimulus evoked) neural activity changes with animal behavior. If we can learn a modulation relationship, we will see if incorporating that relationship directly in the decoding model can improve decoding accuracy, as compared to using behavior as another input to the model.

#### Predictions

We predict that we will be able to decode simple stimuli, such as static gratings, fairly well. We expect that incorporating behavioral data into the model will improve decoding accuracy.

#### Dataset

[Stringer](https://github.com/MouseLand/stringer-et-al-2019) 
