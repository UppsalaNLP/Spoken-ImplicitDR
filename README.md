## Multimodal Extraction and Recognition of Arabic Implicit Discourse Relations

This repository contains a multimodal implicit discourse relations dataset for Egyptian Arabic (EGY). It includes segmented text examples in EGY with implicit discourse relations, alongside their corresponding audio segments.

## Dataset Contents


1. **Audio-segments/**  
   - Contains all audio clips, organized by discourse relation type.  


2. **Dataset/**  
   - Holds the Excel files comprising the dataset’s splits:
     - `train.xlsx`  
     - `test.xlsx`  
     - `validation.xlsx`
   - Each file contains rows with:
     - **EGY_segments**: Text segments in Egyptian Arabic (labeled `[1]` and `[2]`).  
     - **Segment1_audio_path** / **Segment2_audio_path**: Paths to the corresponding audio files in the relevant subfolder.  
     - **Class**: The discourse relation type (e.g., *cause-effect*, *contrast*).  
     - **TED_Talk_Title**: Title of the TED Talk source.  
     - **Implicit_connective(MSA)**: The Modern Standard Arabic connective that corresponds to the discourse relation expressed in the Egyptian Arabic segments.

## Copyright and License

Spoken-ImplicitDR © 2025 by Ahmed Ruby, Christian Hardmeier and Sara Stymne is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/).
