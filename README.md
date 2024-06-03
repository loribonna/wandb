# WHY?
- Add PID of process when loading data to wandb
    - Address issue [4929](https://github.com/wandb/wandb/issues/4929) by letting you KILL the worker 

# Installation

### Manual build (requires GO binary)
```bash
git clone https://github.com/loribonna/wandb
cd wandb
pip install -e .
```

### With wheels
```bash
pip install https://github.com/loribonna/wandb/releases/download/0.0.1/wandb-0.0.1a1-py3-none-linux_x86_64.whl
```
