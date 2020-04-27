# Text2Speech (MaryTTS)
An adapted version of the marytts TTS engine, for use in Wikispeech (http://stts-se.github.io/wikispeech). MaryTTS is a multilingual open-source MARY text-to-speech synthesis platform (MaryTTS). MaryTTS is a client-server system written in Java.

## MaryTTS (Project Info)
[Website](https://github.com/marytts/marytts)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/text2speech/)

## Build image
`$ docker build -t macabees/text2speech:latest .`

## Docker Push
`$ docker push -t macabees/text2speech:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --name text2speech -p 59125:59125 macabees/text2speech`

To access the container: http://localhost:59125/
