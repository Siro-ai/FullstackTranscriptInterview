# FullstackTranscriptInterview

### Preface
Welcome! We're working on empowering sales reps and need your help.
We want to render a transcript to the screen and perform a simple search function on it.

### Quick Jargon
transcript = the transcribed audio recording

utterance = a word

### Instructions


**Fetch the transcript information:**

Fetch the transcript from the following endpoint : https://fullstack-transcript-interview-api-26940969056.us-central1.run.app


**Render the transcript meaningfully:**

Render the transcript with meaningful utterances from the data provided.
At the start of the transcript and after each line_break utterance, you should render a timestamp to indicate that a new speech block is beginning.
Create the notion of an "active" position in the transcript. If you click an utterance of the transcript, this part of the transcript should be highlighted.

**Create an utterance search based on timestamp:**

On the top of the screen, render a text box.
This text box should accept integers.
When an integer is typed, the utterance of the transcript that contains that timestamp should be highlighted.
