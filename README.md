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

You are also welcome to use a code pen to get started without cloning the repo as well.
[React JS Codepen](https://reactplayground.vercel.app)
[Vue Playground](https://play.vuejs.org/)
[Svelt Playground](https://svelte.dev/playground/hello-world?version=5.25.9)



Here are the tasks you'll be completing:

**Fetch the transcript information:**

Fetch the transcript from the following endpoint : https://fullstack-transcript-interview-api-26940969056.us-central1.run.app


**Render the transcript meaningfully:**

Render the transcript meaningfully from the data provided.

**Create an utterance search based on timestamp:**

On the top of the screen, render a text box.
This text box should accept integers.
When an integer is typed, the utterance of the transcript that contains that timestamp should be highlighted yellow.

When highlighting the utternace, use startTimeInMillis inclusive, endTimeinMillis exclusive to the timestamp input.

Example of an acceptable response:

<img width="562" alt="Screenshot 2025-04-09 at 1 40 54 PM" src="https://github.com/user-attachments/assets/08de2c9f-8c07-4ca6-b6b9-a69daedcf3be" />
