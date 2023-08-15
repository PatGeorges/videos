# videos

DATA SONIFICATION with PYTHON— Data visualization techniques

Here is my sonification of the fluctuations in the bitcoin exchange rate (with the US dollar) over a 2-year period. A somewhat oriental melody driven exclusively from the exchange rate fluctuations.

Technical note: This data sonification project was done entirely in Python. The financial data was obtained with Python library yfinance. The soundless animation was produced with Python’s Matplotlib and Celluloid libraries. The background image was taken from the internet and read with the matplotlib imread() function. The soundless animation was saved as a mp4 file (video) using FFMpegFileWriter. The sound file was prepared using the Python library music21 by converting the exchange rate fluctuations to music using basic music rules (pitch, amplitude, tempo...), and midi note notations. The orchestration (different instruments for daily high, low and close values of the Bitcoin) was also done using music21. The resulting midi file was converted as an mp3 (audio) file using FluidSynth and IPython. Finally the merging of the mp3 (audio file) and the mp4 (soundlless video of animation of Bitcoin exchange rate) was done using Python’s library ffmpeg-python.

My Bitcoin concerto is obviously no Beethoven concerto, but for accurate comparison one should look at other data sonification projects. See for example: https://lnkd.in/eMtcszna
