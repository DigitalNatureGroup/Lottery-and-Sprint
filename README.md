# Lottery and Sprint: Generate a Board Game with Design Sprint Method on Auto-GPT
Welcome to the Lottery and Sprint repository!
- This repository is a clone of Auto-GPT v0.3.1 (https://github.com/Significant-Gravitas/Auto-GPT/releases/tag/v0.3.1), with minor modifications made by the author.
- All data used to create board game rules evaluated through TF-IDF is located in `./15_created_data`

## Setup
- Setup Auto-GPT in the same way as original Auto-GPT.
- This project used 'mirvus' for memory management, but other memory tools can also be used.
- Google Search, which requires GOOGLE_API_KEY and CUSTOM_SEARCH_ENGINE_ID, was used.
- Author's original plugin "AutoGPTgpt4" is used. (https://github.com/Auto-GPT-Plugin-Lab/Auto-GPT-use-gpt4-plugin) This allows you to prompt and set parameters independently from the Auto-GPT system's GPT-4.

## Prompts in the "prompt_file"
- Creation prompts for ai_settings.yaml
- Feedback prompts for ai_settings.yaml
- boardgame_material_constrain.txt for defining the material and constraints. File to autogpt/auto_gpt_workspace. It appears when you run the code the first time.
- user_feedback.txt for giving feedback for the created boardgame. File to autogpt/auto_gpt_workspace.


Here is the readme from the original Auto-GPT. -> https://github.com/Significant-Gravitas/Auto-GPT
