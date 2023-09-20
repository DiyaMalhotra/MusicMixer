# MusicMixer
In this code, I have implemented multi-threading to efficiently download songs based on the available threads in the system. The input parameters include the name of the artist, the number of videos to download, the duration of the trimmed part, and the desired name of the output file.

The code performs the following tasks:

1. Download a specified number of videos from YouTube, focusing on the relevance to the artist of interest.
2. Converts the downloaded videos from MP4 format to audio in MP3 format.
3. Trims the first part of the audio, based on the specified duration.
4. Merges all the trimmed audio files to create a single output file in MP3 format.

By utilizing multi-threading, the code optimizes the downloading and processing of songs, effectively dividing the tasks among the available threads for improved efficiency.



