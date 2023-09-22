# Demo

Supplementary Material containing a selection of the adversarial examples and noisy data employed in our paper.

Each sample is accompanied by the Signal-to-Noise Ratio, as detailed in the paper. These samples are sourced from the Librispeech, Commonvoice, and Aishel corpus datasets.

In the paper we found adversarial examples for DNSMOS, a CNN-based speech quality predictor. In this demo, we share the perturbed and original wav files from three datasets: [*DNS-challenge*](https://www.microsoft.com/en-us/research/academic-program/deep-noise-suppression-challenge-interspeech-2020/), [*TIMIT*](https://catalog.ldc.upenn.edu/LDC93s1), and [*VCTK-Demand*](https://datashare.ed.ac.uk/handle/10283/2791).

## Librispeech - English

###### Sample 1 
 [**original**: *SIG*=4.17, *BAK*=4.49, *OVR*=3.98],   [**perturbed**: *SIG*=1.14, *BAK*=1.22, *OVR*=0.97]
<audio style="width:320px" controls="controls">
	<source src="CTC_Deutsch/Benign/common_voice_de_17315084.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="CTC_Deutsch/Benign_noise/common_voice_de_17315084.wav" type="audio/wav" />
</audio>


###### Sample 2 
 [**original**: *SIG*=4.06, *BAK*=4.16, *OVR*=3.73],   [**perturbed**: *SIG*=0.99, *BAK*=1.00, *OVR*=1.00]
<audio style="width:320px" controls="controls">
	<source src="wavs/DNS/original_DNSMOS_SIG_4.06_BAK_4.16_OVR_3.73_book_00007_chp_0008_reader_01326_9_7J3kchZ5UAg-0BQdzcum73Y-door_Freesound_validated_419319_3_snr27_fileid_39095.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/DNS/attacked_DNSMOS_SIG_0.99_BAK_1.00_OVR_1.00_book_00007_chp_0008_reader_01326_9_7J3kchZ5UAg-0BQdzcum73Y-door_Freesound_validated_419319_3_snr27_fileid_39095.wav" type="audio/wav" />
</audio>


###### Sample 3 
 [**original**: *SIG*=2.37, *BAK*=2.50, *OVR*=1.83],   [**perturbed**: *SIG*=4.89, *BAK*=4.97, *OVR*=4.69]
<audio style="width:320px" controls="controls">
	<source src="wavs/DNS/original_DNSMOS_SIG_2.37_BAK_2.50_OVR_1.83_book_00007_chp_0008_reader_01326_48_CXtk8W2gNmY-JwhlLR98Zac-S_ilE4zabbA_snr36_fileid_15337.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="wavs/DNS/attacked_DNSMOS_SIG_4.89_BAK_4.97_OVR_4.69_book_00007_chp_0008_reader_01326_48_CXtk8W2gNmY-JwhlLR98Zac-S_ilE4zabbA_snr36_fileid_15337.wav" type="audio/wav" />
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
