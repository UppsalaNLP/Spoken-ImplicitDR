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


## Reference
If you use this resource, please consider citing:
```plaintext
@inproceedings{ruby-etal-2025-multimodal,
    title = "Multimodal Extraction and Recognition of {A}rabic Implicit Discourse Relations",
    author = "Ruby, Ahmed  and
      Hardmeier, Christian  and
      Stymne, Sara",
    editor = "Rambow, Owen  and
      Wanner, Leo  and
      Apidianaki, Marianna  and
      Al-Khalifa, Hend  and
      Eugenio, Barbara Di  and
      Schockaert, Steven",
    booktitle = "Proceedings of the 31st International Conference on Computational Linguistics",
    month = jan,
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.coling-main.363/",
    pages = "5415--5429",
    abstract = "Most research on implicit discourse relation identification has focused on written language, however, it is also crucial to understand these relations in spoken discourse. We introduce a novel method for implicit discourse relation identification across both text and speech, that allows us to extract examples of semantically equivalent pairs of implicit and explicit discourse markers, based on aligning speech+transcripts with subtitles in another language variant. We apply our method to Egyptian Arabic, resulting in a novel high-quality dataset of spoken implicit discourse relations. We present a comprehensive approach to modeling implicit discourse relation classification using audio and text data with a range of different models. We find that text-based models outperform audio-based models, but combining text and audio features can lead to enhanced performance."
}
