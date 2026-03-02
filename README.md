# Doubting-Machine
A Machine that doubts each an every sentence of the context.
```bash
  echo '[{"role": "user", "content": "I have a question..."}]' \
    | uvx doubting-machine \
        --provider-api-key=sk-ant-api... \
        --github-token=ghp_... 
```
Or:
```bash
  pip install doubting-machine
```
Then:
```Python
  # Python
  import doubting_machine
```
