# Shared-Resource
Sample for how to setup vllm, example shown with Qwen2.5 Coder 14B Instruct

## Setup
### Download desired model
- Download desired model into folder [Qwen2.5 Coder 14B Instruct](https://huggingface.co/Qwen/Qwen2.5-Coder-14B-Instruct).

```
sudo apt-get install git-lfs # Install git-lfs if downloading using git clone

git clone https://huggingface.co/Qwen/Qwen2.5-Coder-14B-Instruct
```

- Ensure that the path is `./models/Qwen2.5-Coder-14B-Instruct`.

## Startup
```
docker compose up -d
```
