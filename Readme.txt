Steps that might help to integrate whisper model into Frontend

UI-Model integration:
1- Convert model file into pickle file
2- Find out a place in UI code to place the pickle file

Firebase Solution structure:
1- We might need a main collectin/folder to store our youtube data transcriptions
2- Text chunks to be stored in Firebase subfolder/sub collection

Working:
1- By clicking on the "Transcribe" button on "COLLECT IT" pop-up, we need to convert the video into audio file and split the audio into 10 sec length chunks and store the chunks into a subfolder/subcollection in Firebase
2- We need to load whisper model on the audio chunks to convert audio into text(subtitles.txt) 
3- Subtitles.txt is to be converted into JSON file to be stored in the last folder(having JSON files) in firebase. 
4- Fetch JSON file from firebase and show the transcriptions on the COLLECT IT pop-up.

Note: The steps mentioned above may be subject to change.
