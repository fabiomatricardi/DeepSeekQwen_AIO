# DeepSeekQwen_AIO
Terminal base chatbot with DeepSeek-R1-Distill-Qwen-1.5B-Q6_K.gguf

<img src='https://github.com/fabiomatricardi/DeepSeekQwen_AIO/raw/main/deppseekR1.png' width=800>


### CLONE THE REPO
```

```

the main project directory will be called `DeepSeekQwen_AIO`
- Enter the project directory `DeepSeekQwen_AIO`
- from the terminal run `install.bat`
> this will create a virtual environment and install the dependencies (basically only `openai` library)

- download in the project directory the GGUF from the [Bartowski repo](https://huggingface.co/bartowski/DeepSeek-R1-Distill-Qwen-1.5B-GGUF) I used the [DeepSeek-R1-Distill-Qwen-1.5B-Q6_K.gguf](https://huggingface.co/bartowski/DeepSeek-R1-Distill-Qwen-1.5B-GGUF/resolve/main/DeepSeek-R1-Distill-Qwen-1.5B-Q6_K.gguf?download=true).


With the venv activated from the terminal run 
```
python runDeepSeekR1_all.py
```

This will automatically open another window that runs the compatible openAI API server

The main python window is ready for chat

<img src='https://github.com/fabiomatricardi/DeepSeekQwen_AIO/raw/main/interface.png' width=800>

---
