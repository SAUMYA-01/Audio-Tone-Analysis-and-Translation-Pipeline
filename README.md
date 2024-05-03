# Audio Tone Analysis and Translation Pipeline
This project is designed to extract voice tones from a video file, perform language translations from English to Hindi, and integrate the translated audio back into the video. The aim is to showcase a simple machine learning pipeline for voice analysis and language processing.

#  Technologies Used

#  Python Libraries:

-MoviePy: Used for video editing tasks such as extracting audio from the video, integrating audio into the video, and exporting the final video file.

-pyAudioAnalysis: Utilized for audio processing tasks such as recognizing speech from audio files.

-googletrans: Employed for language translation services, translating English text to Hindi.

-SpeechRecognition: Used for speech recognition, converting audio to text.

-gTTS (Google Text-to-Speech): Utilized for converting translated text into audio in Hindi.

#  Other Tools:

-IPython.display: Used for displaying audio files within Jupyter Notebooks.

#  Project Overview

Audio Extraction from Video:

The input video file is processed using MoviePy to extract the audio track from it.

The extracted audio is saved as a separate audio file in WAV format.

Voice Tone Recognition and Translation:

The extracted audio file is loaded and analyzed using SpeechRecognition to recognize the speech and convert it into text.

The recognized English text is then translated into Hindi using the googletrans library.

Text-to-Audio Conversion and Playback:

The translated Hindi text is converted into audio using gTTS.

The generated audio file is saved in MP3 format and played back to the user.

Integration of Translated Audio into Video:

The original video file is loaded using MoviePy.

The translated audio file is loaded.

The audio of the video is replaced with the translated audio.

The modified video with the integrated translated audio is saved as a new MP4 file.

#  Outcome

The project demonstrates a simple pipeline for extracting voice tones from a video, translating the spoken text from English to Hindi, and integrating the translated audio back into the video.
By leveraging various Python libraries, the project showcases how machine learning techniques can be applied to audio and language processing tasks, providing a glimpse into the possibilities of multimedia analysis and translation.
