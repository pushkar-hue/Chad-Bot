# LLaMA-3 GenZ Chatbot with Google Search Integration

This project features a fine-tuned LLaMA-3-8B model that mimics Gen-Z language and rephrases real-time Google search results into casual, humorous, and stylistic responses.

The chatbot uses live search via the Serper API and responds in a Gen-Z tone. It demonstrates real-world application of retrieval-augmented generation (RAG), language style transfer, and optimized inference on large language models.

## Features

- Fine-tuned LLaMA-3-8B model using LoRA for Gen-Z conversational tone
- Integrated with Serper API to fetch live Google search results
- FastAPI-based backend for low-latency REST API inference
- 4-bit quantized model using bitsandbytes for reduced memory usage and faster response
- Contextual prompt chaining and dynamic response generation

## Tech Stack

- LLaMA-3-8B (fine-tuned with LoRA adapters)
- Quantization via bitsandbytes (4-bit inference)
- FastAPI backend
- Serper API (Google Search integration)
- Hugging Face Transformers
- Prompt engineering for language style transformation

## Example

**Input Query:**  
"Why is the sky blue?"

**Fetched Result (via Serper):**  
"Blue light from the sun scatters in all directions by the gases and particles in the Earth's atmosphere."

**Model Output:**  
"So basically, the sky filters vibes and blue just wins. Physics but make it aesthetic."

## Installation

```bash
git clone https://github.com/pushkar-hue/Chad-Bot.git
cd genz-llama3-chatbot

# (optional) set up virtual environment
python -m venv venv
source venv/bin/activate  # for Linux/Mac
venv\Scripts\activate     # for Windows

pip install -r requirements.txt
```
## Credits

Developed by:


- **Ved Thorat**  
  GitHub: [i3hz](https://github.com/i3hz)
  
- **Pushkar Sharma**
   GitHub: [pushkar-hue](https://github.com/pushkar-hue)


