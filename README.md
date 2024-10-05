# Radio Theater from Text (audio book generator)

This Jupyter Notebook explores the process of transforming a text file into an audiobook-style experience, similar to a radio theater play.  It utilizes text-to-speech synthesis, in a dialog format.
q
<audio controls>
  <source src="./audio_books/john-carter-1.mp3" type="audio/mpeg">
</audio>

Download an example of the output can be found here: [john-carter-1.mp3](./audio_books/john-carter-1.mp3) (click on "View raw" to download)

It is an excerpt from the book *"Princess of Mars"* (as found on project Gutenberg). Note that the audio play does not
follow the original text exactly, but rather(arguably) attempts to create a more engaging and immersive listening experience.

## Functionality

* **Text Input:** Takes a text file as input (currently needs to be formatted for best results; see notes below).
* **Text-to-Speech:** Converts the text into speech using a chosen TTS engine (e.g., Google Cloud Text-to-Speech).
* **Output:** Generates an audio file (MP3) of the audiobook.

## To Use:

1. Install required libraries, run: `make`
2. Run the notebook cells sequentially.

## Future work

Explore the use of sound effects, and potentially music to create a more immersive listening experience than a simple text-to-speech reading.

## Credits:

A significant portion of the code in this project is based on the excellent [pdf-to-podcast](https://github.com/knowsuchagency/pdf-to-podcast) project. 


