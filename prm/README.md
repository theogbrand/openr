#  Supervised Training for PRMs

## TODO: 
- download full prm800k dataset and process it to match column names used in test.json.

## Finetuning Qwen
```bash
python finetune_qwen_single_gpu.py
torchrun --nproc_per_node=8 finetune_qwen.py
```