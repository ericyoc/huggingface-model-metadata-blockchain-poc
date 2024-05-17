# Pre-trained Model Registration Using Blockchain

## Overview

This project demonstrates the registration of pre-trained models found on [Hugging Face](https://huggingface.co/) using blockchain technology. The code fetches random pre-trained models from the Hugging Face Model Hub, extracts metadata about each model, and registers it in a blockchain. This process ensures the integrity of the models, safeguarding against adversarial modifications.

## Huggingface Platform

[Hugging Face](https://huggingface.co/) is a leading platform for natural language processing (NLP) models and resources. It hosts a vast collection of pre-trained models, datasets, and other NLP tools, facilitating research and development in the field.

## Blockchain Technology

Blockchain is a decentralized, distributed ledger technology that enables secure and transparent record-keeping. Each record, or block, in the blockchain is cryptographically linked to the previous block, forming an immutable chain. This ensures data integrity and tamper resistance, making blockchain suitable for applications where data integrity is critical, such as model registration.

## Usage

1. Clone the repository.
2. Install the required dependencies (`transformers`, `requests`, `prettytable`).
3. Run the `main.py` script.
4. View the generated final table of model metadata.
5. Check the saved CSV file (`models_metadata.csv`) for model metadata.
6. Inspect the blockchain data saved in JSON format (`blockchain_data.json`).

## Blockchain Registry Results

![](https://github.com/ericyoc/huggingface-model-metadata-blockchain-poc/blob/main/models_metadata.csv)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the functionality or documentation of the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
