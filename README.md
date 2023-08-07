# Safe Model-Based Multi-Agent Mean-Field Reinforcement Learning Repository

To install the package, run `pip install -e .`

To run an experiment:
1. It is necessary to modify *logdir* and *input_data_path* fields in config files provided in configs directory
2. Optionally modify other fields, including *entity*, for wandb logging
3. Execute `python safe_mf/main.py --config path/to/config.yaml`

