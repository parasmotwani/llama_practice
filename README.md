# llama_practice
In this mini project i tend to explore text generation using llama 3.2 1B model
you can easily use this project in Colab.

1.) **Create a `requirements.txt` file** in colab - 
Add the following dependencies:
  bitsandbytes==0.45.0
  accelerate==1.2.1
  transformers==4.48.0

2.) **Install Dependencies** - 
Run the following command in your Colab notebook to install the required packages: 
!pip install -r requirements.txt

3.) **Obtain a Hugging Face Access Token** - 
Log in to your Hugging Face account.
Create an Access Token in your account settings. [https://huggingface.co/settings/tokens]
Copy the token.

4.) **Create a config.json file** in colab - 
Create a file named config.json with the following content:
  {"HF_TOKEN" : "YOUR_HUGGING_FACE_API_KEY"} replace "YOUR_HUGGING_FACE_API_KEY" with your copied token.

5.) **Log in to Hugging Face on Colab** - 
Execute the following command in your Colab notebook:
  !huggingface-cli login

**Important Note:** - 
Access Requirement: LLaMA 3.2 1B is a gated repository. Ensure you request and receive access from Hugging Face; otherwise, the model will throw an error.
