# End-to-end-medical-chatbot-using-llama2



## Steps to run the project

clone the repository

```bash
https://github.com/JagrutiShinde/End-to-end-medical-chatbot-using-llama2.git
```


```bash
$ conda create -n medicalchatbot python=3.8 -y
```

```bash
conda activate medicalchatbot
```

```bash
pip install -r requirements.txt
```
```bash
Create a .env file in the root directory and add your Pinecone credentials as follows:
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
## Download the Llama 2 Model
llama-2-7b-chat.ggmlv3.q4_0.bin
```

```bash
Download the quantize model from the link provided in model folder & keep the model in the model directory:
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin
model should be placed in model folder

## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

```bash
python store_index.py
```
```bash
# Finally run the following command
python app.py
```
```bash
Now,

open up localhost:
```