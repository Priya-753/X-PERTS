### X-PERTS READ-ME ###

SUMMARY:

This project evaluates PEFT approaches, BitFit and LoRA, as well as Prompt Tuning, used for large language models (LLMs) with an emphasis on small scale models and ultra-low resource fine-tuning.

We explore three models (OPT125-m, ALBERT and GPT2) and their efficacy on sentiment analysis tasks derived from popular datasets IMDb50k and Sentiment140, comparing baseline inference with baseline (post-trained, no PEFT/Prompt Tuning added) classification peformance with and without the addition of BitFit, LoRA and Prompt Tuning.

TO-DO:

To run the experiments as we have, simply upload to Google Drive the *****_solo.ipynb notebooks found in ****_solo folders, where the asterisks are some prefix denoting the model and dataset. Please also upload to the same Google Drive the sentiment140.py script. We will need to add this to the session storage on Google Colab.

In order to run the notebooks, you simply need to add the sentiment140.py script to the local session for any notebook that experiments on Sentiment140. For the IMDb50k dataset, we can simply import the necessary data from HuggingFace directly, with no need for any additional documents to be added to the session storage. In the case where you are importing sentiment140.py, you may need to adjust the file path slightly. From time to time, Google Colab seems to change where drag-and-drop will land your sentiment140.py, so it'll either be /sentiment140.py or /content/sentiment140.py.

For that matter, wherever your sentiment140.py file ends up per session, the .csv files you generate that capture model performance and necessary data for generating or re-generating visuals, should also wind up in the same directory.

The last block of each notebook will zip all the active session data .csv files cleanly for you and download to your local machine.

Aside from that, the rest should be clear. Have fun! :)

GITHUB REPO:

https://github.com/Priya-753/X-PERTS
