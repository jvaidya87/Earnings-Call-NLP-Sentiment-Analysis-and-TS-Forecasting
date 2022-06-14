# Earnings-Call-NLP-Sentiment-Analysis-and-TS-Forecasting
Using publicly available earnings call transcripts, we attempt to fine-tune pre-trained Masked Language Models using modest hand-annotated datasets, in order to perform sentiment analysis on Executive's utterances. By segmenting those sentiment readings by time and industry, and through the development and application of a proprietary "negative sentiment tripwire", we generate a rich NLP-based feature set upon which to train tree-based &amp; transformer-based classification models for time-series classification and prediction of the next month's S&amp;P500 returns

## The current version of this notebook uses the following packages/versions:

torch == 1.8.1<br>
tensorflow == 2.8.0<br>
nltk == 3.6.2<br>

## Original Data
Original Transcript data soourced from the WRDS CapitalIQ Transcripts database; the transcripts data was then merged with various company-specific databases to generate information on company origin (only U.S. domiciled companies were included in this analysis), indsutry sector and various other identifiers

## For more information
Please contact the authors, Jay Vaidya (jvaidya@journeymcap.com) and Ruchi Kumar (ruchikumar12@yahoo.com)
