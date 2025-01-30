# Deepseek
![image](https://github.com/user-attachments/assets/cb1f1383-423c-4008-8d48-5911ec407ea3)

![image](https://github.com/user-attachments/assets/84e91351-1109-4598-9c68-d9d9fa9daf3e)

## How to Setup Deepseek Locally 

# Ollama

Ollama is a tool that allows you to run and manage large language models (LLMs) locally on your computer. It provides a simple way to download, run, and interact with AI models without relying on cloud-based services.

## Key Features

- **Run AI models locally**: Supports models like LLaMA, Mistral, Gemma, and more.
- **Offline functionality**: No internet required once models are downloaded.
- **Faster responses**: Local execution ensures low latency and quick results.
- **Custom models**: Supports custom models and fine-tuning.
- **Cross-platform**: Works on Linux, macOS, and Windows (via WSL).

## Getting Started

To get started with Ollama, follow these steps:

1. **Download Ollama**: Visit the official [Ollama website](https://ollama.ai) to download the latest version for your operating system.
2. **Install Ollama**: Follow the installation instructions for your platform.
3. **Download Models**: Use the command-line interface to download and manage AI models.
4. **Run Models**: Start interacting with the models locally.

## Usage

### Download a Model
To download a model (e.g., LLaMA), use the following command:
```bash
ollama pull llama
```
Step 1 Setup Ollama on Linux.
```bash
 sudo snap install ollama
```
Windows User use https://ollama.com/

Step 2 Install deepseek-r1 Dependencies These dependencies take time to install into the system.
https://ollama.com/library/deepseek-r1:1.5b

![image](https://github.com/user-attachments/assets/daa79e77-9cb8-4bc2-adc4-947dc4e07bfc)

Step 3 To Access Ollama On linux you can install using this command 

![image](https://github.com/user-attachments/assets/af23abe9-4952-42c6-842d-4c040656a9ee)

Step 4 To run the DeepSeek-R1 1.5B model using Ollama, use the following command its take some time maybe 15 mint's depend on server configuration 
```bash
ollama run deepseek-r1:1.5b
```
Step 5 Enter Your Prompt if you connect with local machine without internet then its sake 3 seconds to think your prompt 

![image](https://github.com/user-attachments/assets/6430de61-f878-4c97-8a3b-82eb667345a9)

![image](https://github.com/user-attachments/assets/1f9b17ab-f09d-4de2-a7c3-1d6544bfe88e)




