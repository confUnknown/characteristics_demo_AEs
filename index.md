# Adversarial example demo

Supplementary material containing a selection of benign, adversarial, and noisy data employed in our [*paper*](https://openreview.net/forum?id=R1crLHQ4kf).

For each sample, we include the word error rate (WER) as an accuracy metric and the segmental signal-to-noise ratio (SNR<sub>seg</sub>) as a quality noise metric. An SNR<sub>seg</sub> exceeding 0 dB indicates a stronger signal presence compared to noise. These samples are sourced from the [*Librispeech*](https://www.openslr.org/12), [*Commonvoice*](https://commonvoice.mozilla.org/en), and [*Aishell*](https://www.openslr.org/33/) corpus datasets.


## Librispeech - English
###### Sample 1 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_benign.flac" type="audio/flac" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_noisy.flac" type="audio/flac" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=24.50],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=25.36]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-0.60]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_gc.wav" type="audio/wav" />
</audio>

###### Sample 2 
<pre>Benign transcription:       <em>HOW JOLLY IT WAS BEING YOUNG HILDA</em>
Adversarial transcription:  <em>THERE WAS A GRIM SMILE OF AMUSEMENT ON HIS SHREWD FACE</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=0.00, SNR<sub>seg</sub>=6.03]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/4446-2273-0017_benign.flac" type="audio/flac" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/4446-2273-0017_noisy.flac" type="audio/flac" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=22.04],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=22.95]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/4446-2273-0017_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/4446-2273-0017_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-5.87]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/4446-2273-0017_gc.wav" type="audio/wav" />
</audio>


## Common Voice v.6 - German

###### Sample 1 
<pre>Benign transcription:       <em>DAS HAT SCHON MEINE URGROßMUTTER GESAGT</em>
Adversarial transcription:  <em>NEU DELHI IST DIE HAUPTSTADT VON INDIEN</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=0.00, SNR<sub>seg</sub>=-20.24]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_17914813_benign.mp3" type="audio/mp3" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_17914813_noisy.flac" type="audio/wav" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=9.05],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=11.72]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_17914813_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_17914813_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-25.41]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_17914813.wav" type="audio/wav" />
</audio>


###### Sample 2 
<pre>Benign transcription:       <em>ICH GLAUBE ES AUCH NICHT</em>
Adversarial transcription:  <em>WAS SOLLS ICH BIN BEREIT</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=20.00, SNR<sub>seg</sub>=-17.16]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_benign.mp3" type="audio/mp3" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_noisy.wav" type="audio/wav" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=8.86],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=11.23]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-12.88]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_gc.wav" type="audio/wav" />
</audio>

## Common Voice v.6 - Italian

###### Sample 1 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_benign.mp3" type="audio/mp3" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_noisy.wav" type="audio/wav" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=24.50],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=25.36]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-0.60]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_gc.wav" type="audio/wav" />
</audio>

###### Sample 2 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_benign.mp3" type="audio/mp3" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_noisy.wav" type="audio/wav" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=24.50],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=25.36]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/common_voice_de_18217625_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-0.60]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_gc.wav" type="audio/wav" />
</audio>

## Aishell - Mandarin

###### Sample 1 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_benign.flac" type="audio/flac" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_noisy.flac" type="audio/flac" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=24.50],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=25.36]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-0.60]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_gc.wav" type="audio/flac" />
</audio>

###### Sample 2 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_benign.flac" type="audio/flac" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_noisy.flac" type="audio/flac" />
</audio>
[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=24.50],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=25.36]
 <audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_cw.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_psy.wav" type="audio/wav" />
</audio>
[**adaptive adversarial**: *WER*=0.00, SNR<sub>seg</sub>=-0.60]
<audio style="width:320px" controls="controls">
	<source src="audio_clips/Librispeech/1995-1837-0013_gc.wav" type="audio/flac" />
</audio>
