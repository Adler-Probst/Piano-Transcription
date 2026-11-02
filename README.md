# Piano Transcription
A Python script designed to take a solo piano audio file and output sheet music.

## The Problem

The problem I am trying to solve is missing sheet music for many piano songs. Though you could do this with any instrument, it is mostly piano songs that lack sheet music and it's very annoying when trying to learn something you heard and liked.

## How It Works

The program takes an audio file that should be a solo piano audio file, analyzes the frequencies of the audio, and based on the timing, creates sheet music.

## Tech Stack
Language - Python

Libraries - librosa, music21

Data Storage - local CSV file for storing music history and summary AND output file of sheet music

External Data - publicly available piano audio files for testing. (librosa).

## Setup

1. git clone https://github.com/Adler-Probst/Piano-Transcription
2. cd Piano-Transcription
3. pip install -r requirements.txt

## Usage

cd Piano-Transcription

python main.py inputs/name_of_sound_file.wav

## Future Plans
Advanced music analysis - implement more features such as tempo, dynamics, key, etc.

Complex music handling - be able to handle very complex chords and multiple octaves

Interface / GUI - create an interface or GUI for easier use of program.

## Author

Adler Probst - https://github.com/Adler-Probst
