# FullstackTranscriptInterview

### Preface
Welcome! We're working on empowering sales reps and need your help.
We want to render a transcript to the screen and perform a simple search function on it.

### Quick Jargon
transcript = the transcribed audio recording

utterance = a word + punctuation

## Housekeeping 
Feel welcome to look things up when you need to. Please ensure anything you look up is shared on your screen.
You may use AI autocomplete or suggestion features in your IDE, but please don't use AI prompts to generate code. If you do incorporate any AI-generated code, please describe what it does.

### Instructions

For this interview, you'll be building a S.P.A. that displays transcript data fetched from an api endpoint, and allows the user to perform a simple search function. This can be done on the JS/TS framework of your choice. 
Please feel free to clone this repo to complete this locally. We've also built a template using React, Svelte, and Vue.

You are also welcome to use a code pen to get started without cloning the repo as well.
[React](https://stackblitz.com/edit/siro-react-interview?file=src/App.tsx)
[Svelte](https://stackblitz.com/edit/siro-svelt-interview?file=src/App.svelte)
[Vue](https://stackblitz.com/edit/siro-vue-interview?file=src/App.vue)



Here are the tasks you'll be completing:

**1. Fetch the transcript information:**

Fetch the transcript from the following endpoint : https://fullstack-transcript-interview-api-26940969056.us-central1.run.app


**2. Render the transcript meaningfully:**

Render the transcript in a readable way from the data provided.
No need to worry too much about styling - as long as the transcript is readable that is what we're looking for.

**3. Create an utterance search based on timestamp:**

On the top of the screen, render an input box.
This input box should accept a timestamp in milliseconds as an integer.
When an integer is typed, the utterance of the transcript that overlaps with the timestamp should be highlighted yellow.

When highlighting the utterance, use startTimeInMillis inclusive, endTimeinMillis exclusive to the timestamp input.

Example of an acceptable response:

<img width="562" alt="Screenshot 2025-04-09 at 1 40 54 PM" src="https://github.com/user-attachments/assets/08de2c9f-8c07-4ca6-b6b9-a69daedcf3be" />
