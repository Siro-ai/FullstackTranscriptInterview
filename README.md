# FullstackTranscriptInterview

### Preface
Welcome! We're working on empowering sales reps and need your help.
We want to render a transcript to the screen and perform a simple search function on it.

### Quick Jargon
transcript = the transcribed audio recording

utterance = a word

### Instructions

For this interview, you'll be building a SPA that displays transcript data fetched from an api endpoint, and allows the user to perform a simple search function on. This can be done on the JS/TS framework of your choice. 
We've built a template using React and Svelt with tailwind installed to help you get started quickly.

Here are the tasks you'll be completing:

**Fetch the transcript information:**

Fetch the transcript from the following endpoint : https://fullstack-transcript-interview-api-26940969056.us-central1.run.app


**Render the transcript meaningfully:**

Render the transcript with meaningful utterances from the data provided.

**Create an utterance search based on timestamp:**

On the top of the screen, render a text box.
This text box should accept integers.
When an integer is typed, the utterance of the transcript that contains that timestamp should be highlighted.
