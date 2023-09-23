# Adversarial example demo

Supplementary material containing a selection of benign, adversarial and noisy data employed in our [*paper*](https://openreview.net/forum?id=R1crLHQ4kf).

For each sample, we include the word error rate (WER) as an accuracy metric and the segmental signal-to-noise ratio (SNR<sub>seg</sub>) as a quality noise metric. An SNR<sub>seg</sub> exceeding 0 dB indicates a stronger signal presence compared to noise. These samples are sourced from the [*Librispeech*](https://www.openslr.org/12), [*Commonvoice*](https://commonvoice.mozilla.org/en), and [*Aishell*](https://www.openslr.org/33/) corpus datasets.


## Librispeech - English

###### Sample 1 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;

[**benign**: *WER*=0.00],                                     [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
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
 [**original**: *SIG*=4.06, *BAK*=4.16, *OVR*=3.73],   [**perturbed**: *SIG*=0.99, *BAK*=1.00, *OVR*=1.00]
<audio style="width:320px" controls="controls">
	<source src="wavs/DNS/original_DNSMOS_SIG_4.06_BAK_4.16_OVR_3.73_book_00007_chp_0008_reader_01326_9_7J3kchZ5UAg-0BQdzcum73Y-door_Freesound_validated_419319_3_snr27_fileid_39095.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/DNS/attacked_DNSMOS_SIG_0.99_BAK_1.00_OVR_1.00_book_00007_chp_0008_reader_01326_9_7J3kchZ5UAg-0BQdzcum73Y-door_Freesound_validated_419319_3_snr27_fileid_39095.wav" type="audio/wav" />
</audio>


## Common Voice v.6- German

###### Sample 1 
 [**original**: *SIG*=1.06, *BAK*=1.05, *OVR*=1.00],   [**perturbed**: *SIG*=5.00, *BAK*=4.24, *OVR*=4.35]
<audio style="width:320px" controls="controls">
	<source src="wavs/TIMIT/original_DNSMOS_SIG_1.06_BAK_1.05_OVR_1.00_helicopter_0dB_DR4_MLLL0_SI1363.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/TIMIT/attacked_DNSMOS_SIG_5.00_BAK_4.24_OVR_4.35_helicopter_0dB_DR4_MLLL0_SI1363.wav" type="audio/wav" />
</audio>


###### Sample 2 
 [**original**: *SIG*=3.85, *BAK*=1.82, *OVR*=2.22],   [**perturbed**: *SIG*=4.06, *BAK*=5.00, *OVR*=4.17]
<audio style="width:320px" controls="controls">
	<source src="wavs/TIMIT/original_DNSMOS_SIG_3.85_BAK_1.82_OVR_2.22_helicopter_10dB_DR4_MLLL0_SI733.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/TIMIT/attacked_DNSMOS_SIG_4.06_BAK_5.00_OVR_4.17_helicopter_10dB_DR4_MLLL0_SI733.wav" type="audio/wav" />
</audio>


###### Sample 3 
 [**original**: *SIG*=4.05, *BAK*=3.07, *OVR*=3.21],   [**perturbed**: *SIG*=1.00, *BAK*=1.00, *OVR*=1.00]
<audio style="width:320px" controls="controls">
	<source src="wavs/TIMIT/original_DNSMOS_SIG_4.05_BAK_3.07_OVR_3.21_wind1_10dB_DR2_MWEW0_SX101.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/TIMIT/attacked_DNSMOS_SIG_1.00_BAK_1.00_OVR_1.00_wind1_10dB_DR2_MWEW0_SX101.wav" type="audio/wav" />
</audio>


## Common Voice v.6- Italian

###### Sample 1 
 [**original**: *SIG*=1.03, *BAK*=1.05, *OVR*=0.98],   [**perturbed**: *SIG*=4.01, *BAK*=3.27, *OVR*=3.23]
<audio style="width:320px" controls="controls">
	<source src="wavs/VCTK/original_DNSMOS_SIG_1.03_BAK_1.05_OVR_0.98_p226_133.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/VCTK/attacked_DNSMOS_SIG_4.01_BAK_3.27_OVR_3.23_p226_133.wav" type="audio/wav" />
</audio>


###### Sample 2 
 [**original**: *SIG*=1.38, *BAK*=1.09, *OVR*=1.09],   [**perturbed**: *SIG*=4.28, *BAK*=4.00, *OVR*=3.70]
<audio style="width:320px" controls="controls">
	<source src="wavs/VCTK/original_DNSMOS_SIG_1.38_BAK_1.09_OVR_1.09_p226_206.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/VCTK/attacked_DNSMOS_SIG_4.28_BAK_4.00_OVR_3.70_p226_206.wav" type="audio/wav" />
</audio>


###### Sample 3 
 [**original**: *SIG*=2.33, *BAK*=1.40, *OVR*=1.54],   [**perturbed**: *SIG*=4.00, *BAK*=4.00, *OVR*=3.72]
<audio style="width:320px" controls="controls">
	<source src="wavs/VCTK/original_DNSMOS_SIG_2.33_BAK_1.40_OVR_1.54_p226_236.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/VCTK/attacked_DNSMOS_SIG_4.00_BAK_4.00_OVR_3.72_p226_236.wav" type="audio/wav" />
</audio>
