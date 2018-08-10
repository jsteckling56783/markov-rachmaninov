# markov-rachmaninov
Markov process chord study for Prelude in G minor by Rachmaninov, 1901

I chose this piece as initial training data because it produces primarily chords rather than melodic sequences of individual notes.
Phase 1 queries the notes into chords of 2, 3, and 4 notes that are played as the same time. These are treated as markov states.
Frequencies of how often each chord is played and the probability of each possibly subsequent chord are used to make an initial state
matrix and a transition matrix to generate audio.

To learn about how Rachmaninov uses chord structure in his pieces, I created data visualizations to demonstrate how notes are combined.
In one iteration, I considered the 12 tones in the scale, ignoring octaves, to show common intervals, consonance, and dissonance.
I also visualized relationships on the scale of the entire 88 key spectrum to demonstrate how these intervals are expressed.
