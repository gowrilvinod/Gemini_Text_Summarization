# Gemini_Text_Summarization

This README provides instructions for using Hugging Face models to perform text summarization tasks.

### Steps

1. **Install Libraries**

   Ensure you have the required libraries installed:
   - `langchain-huggingface`
   - `huggingface_hub`
   - `transformers`
   - `accelerate`
   - `bitsandbytes`
   - `langchain`

2. **Set Up Environment**

   - Import necessary libraries.
   - Set your Hugging Face API key as an environment variable.

3. **Load Model and Tokenizer**

   - Load your desired Hugging Face model using `AutoModel`.
   - Initialize the tokenizer associated with your model using `AutoTokenizer`.

4. **Download Additional Model Files**

   - If necessary, download additional model files like `config.json`, `pytorch_model.bin`, etc., using `hf_hub_download`.

5. **Set Up Text Generation Pipeline**

   - Create a text generation pipeline using `pipeline("text2text-generation", model=model, tokenizer=tokenizer)`.

6. **Usage**

   - Use the pipeline to generate summaries for text or code snippets as per your requirements.

7. **Adjust Model and Key**

   - Replace `model_id` and `token` with your specific model ID and Hugging Face API key.

