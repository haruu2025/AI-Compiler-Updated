# AI COMPILER

>AI Compiler is a powerful tool that leverages multiple AI models to assist with various coding tasks, including code debugging, documentation and language translation.

## Features

- Debugger AI: Debug and fix code with AI assistance
- Documentation Writer: Automatically generate code documentation
- Code Translator: Translate code between different programming languages
- Mixture of Agents : This MOA  Architechture can harness the collective strengths of multiple LLMs
- Gemini API Code Execution : This feature enables the model to generate and run Python code 
## Preview :


![](Examples/p1.jpg)

## Installation

1. Clone the repository:
 ```bash
    git clone https://github.com/yourusername/AI-Compiler-Updated.git
 ```
2. Change the Current Directory To ai-compiler:
 ``` bash
cd ai_compiler.py
 ```
3. Install required packages:
 ```bash
pip install -r requirements.txt
 ```
4. Set up API keys:
- Create a `.env` file in the project root
- Add the following lines, replacing `your_api_key` with actual keys:
  ```
  GROQ_API_KEY=your_api_key
  GEMINI_API_KEY=your_api_key
  MIXTRAL_API_KEY=your_api_key
  ```
 Groq_API_KEY from: https://console.groq.com/keys

 GEMINI_API_KEY from: https://ai.google.dev/gemini-api/docs/api-key

 Mixtral_API_KEY from: https://build.nvidia.com/explore/discover#mistral-large

5. Run the application:
 ```bash
streamlit run ai_compiler.py
 ```

## Example Use Cases

- Debugging complex Python scripts
- Creating documentation for legacy codebases
- Generating Complex code from scratch
- Translating code snippets between languages
- Learning coding patterns through AI-generated examples

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests to the original repository this is forked from.
