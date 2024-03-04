# LLAMA 2 Fine-Tuning

This repository, [LLAMA_2_FineTuning](https://github.com/true-ncoder-dcoder/LLAMA_2_FineTuning/tree/main), contains the code for fine-tuning the LLAMA 2 model using Python and several supporting libraries such as Hugging Face's Transformers, PEFT, and BitsAndBytes. The project aims to enhance the LLAMA 2 model's performance for specific tasks or datasets by applying techniques like Quantization and LoRA (Low-Rank Adaptation).

## Installation

To set up your environment to run the code, you need to install the required libraries. Execute the following command to install them:

```bash
pip install transformers peft bitsandbytes trl deepeval evaluate

```
## Usage
The main script for fine-tuning the LLAMA 2 model is included in this repository. Before running the script, make sure to replace XXXXXXXXXXXXX with your Hugging Face token in the code.

You can start the fine-tuning process by running the following command:

python <your_script_name>.py

Ensure you have the necessary data and resources specified in the script.

## Dataset
The training script uses the mlabonne/guanaco-llama2-1k dataset for fine-tuning. You can replace this with your dataset by changing the train_dataset_name variable.

## Contributing
Contributions are welcome! If you have improvements or bug fixes, please open a pull request or issue.

## Acknowledgements

Hugging Face for the Transformers library and the hosted models.
The original authors and contributors to the LLAMA 2 model and related libraries.


