# tiktok-political-project
An exploratory project examining partisan preferences in TikTok repost content. This project makes use of VLMs, LLMs, and deep transformer embeddings.

## Files:

`llm_finetuning.ipynb`: Fine-tuning GPT-2 to Republican repost data and Democrat repost data using LoRA

`political_embedding_analysis.ipynb`: EDA of the text embeddings for Republican and Democrat repost data

`sdxl_bias_examination.ipynb`: Bias examination of SDXL generated images by using GPT-4o to categorize images

`tiktok_political_vision_classifier.ipynb`: Generating images using video description text to prompt SDXL, and then embedding images using Qwen. The outputs are cleared to save on storage space. To the TAs: there should a link in my final submission to a google drive folder where all the outputs are visible.

`tiktok_text_political_classifier.ipynb`: Embedding text, then training classifiers to separate Democrat and Republican repost content.

**Note:** Due to privacy restriction, data is not yet uploaded. An anonymized version of the database is forthcoming, and SQL queries in the code will be updated to represent the new database structure.

Read the main essay on Substack here: [substack essay](https://consequunturaegre596267.substack.com/p/democrats-and-republicans-use-tiktok)
