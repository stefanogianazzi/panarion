**Local transcription**

SOX+Whisper

1. Navigate to the folder you want to use as an archive
2. CLI: sox -d filename.mp3
3. CTRL+C to stop recording
4. whisper filename.mp3 --model medium

**Options for Sox**
See here: https://hyaline.systems/blog/sox-guide/ (e.g. type of file output)
Or, to read the manual, open up a terminal and type: 
`man sox`

**comando ottimizzato:**  
whisper Hpc\ quindi.wav --language Italian --model large-v3
whisper 2025_09_10_09_35_12.wav --language Italian --model large-v3 --output_format txt




Optimized command examples
whisper "Hpc quindi.wav" --language Italian --model large-v3
whisper "2025_09_10_09_35_12.wav" --language Italian --model large-v3 --output_format txt


These examples use the large-v3 model for better transcription quality in Italian and save the result as a text file.

Useful options for Whisper
Option	Description
--model <name>	Selects the model size (tiny, base, small, medium, large, large-v3).
--language <lang>	Forces transcription language (e.g., Italian, English, etc.).
--output_format <format>	Sets output format: txt, vtt, srt, json, etc.
--output_dir <path>	Saves transcriptions to a specific directory.
--verbose False	Suppresses progress messages for cleaner logs.
--temperature <float>	Adjusts sampling variability (default: 0).
--task translate	Translates non-English speech to English instead of transcribing.
Tips

For long recordings, prefer --model medium or --model large-v3 for improved accuracy.

Keep SoX recordings short (under a few minutes) when using Whisper locally to avoid memory overload.

To speed up transcription, install the CUDA version of Whisper if you have a compatible GPU.
