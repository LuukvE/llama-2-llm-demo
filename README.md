## Installation

```
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
sudo apt-get install -y nodejs
git clone https://github.com/LuukvE/llama-2-llm-demo.git
cd llama-2-llm-demo
sudo npm install
cd models
wget https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/resolve/main/llama-2-7b-chat.ggmlv3.q2_K.bin
```

## Run

```
npm start
```