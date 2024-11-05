<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## POP-ROK Dataset

POP-ROK is an open audio dataset featuring an uncurated collection of synthetic drum recordings in the style of pop rock music. It includes 5,378 audio loops recorded in uncompressed stereo WAV format, along with paired JSON files intended for the supervised training of generative AI audio models.

## Overview

The POP-ROK Dataset was developed by sonifying a collection of approximately 30 acoustic drum kits with a paired MIDI dataset covering basic rhythm patterns, excluding toms. Data augmentation included a random drum-swapping method to generate unique drum kits and reverb simulations to represent various room sizes. This dataset is intended for training or fine-tuning AI models in rhythm notation with paired drum note labels, aiming to replicate the sound of live drumming.

The primary purpose of this dataset is to provide accessible content for machine learning applications in music and audio. Potential use cases include generative music, feature extraction, tempo detection, audio classification, rhythm analysis, drum synthesis, music information retrieval (MIR), sound design and signal processing.

**Specifications**

- 5,378 audio loops (approximately 24 hours)
- 16-bit 44.1kHz WAV format
- Tempo range: 100-130 BPM
- Paired label data (WAV + JSON)
- Variational drum patterns
- Subgenre styles (Pop, classic rock, soft rock, country)

## Examples

See examples folder to preview mp3 demos.


## License

This dataset is developed by WaivOps, a crowdsourced music project managed by sound label company Patchbanks. All recordings have been compiled by verified sources for copyright clearance.

The POP-ROK dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
## Download

Direct WAV Download (12.6 GB) [pop_rok_drm_id_001_wav](https://zenodo.org/records/14038284/files/pop_rok_drm_id_001_wav.tar.gz?download=1)

Direct JSON Download (210.2 KB) [pop_rok_drm_id_001_json](https://zenodo.org/records/14038284/files/pop_rok_drm_id_001_json.tar.gz?download=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14038284.svg)](https://doi.org/10.5281/zenodo.14038284)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| pop | Main genre (pop)|
| rok | Subgenre (rock)|
| drm | Instrument (drums)|
| id | Identification number|
| 0000 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@dataset{POP-ROK,
author = {WaivOps},
title = {WaivOps POP-ROK: Open Audio Resources for Machine Learning in Music},
year = {2024},
doi = {10.5281/zenodo.14038284},
url = {https://doi.org/10.5281/zenodo.14038284},
}
```
## Additional Info

For any questions or feedback please email info@patchbanks.com.
