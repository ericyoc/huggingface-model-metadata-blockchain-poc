# Pre-trained Model Registration Using Blockchain

## Overview

This project demonstrates the registration of pre-trained models found on [Hugging Face](https://huggingface.co/) using blockchain technology. The code fetches random pre-trained models from the Hugging Face Model Hub, extracts metadata about each model, and registers it in a blockchain. This process ensures the integrity of the models, safeguarding against adversarial modifications.

## Motivating Articles
Bouchiha, M. A., Telnoff, Q., Bakkali, S., Champagnat, R., Rabah, M., Coustaty, M., & Ghamri-Doudane, Y. (2024). LLMChain: Blockchain-based Reputation System for Sharing and Evaluating Large Language Models. arXiv preprint arXiv:2404.13236. https://arxiv.org/abs/2404.13236

Y. Liu et al., "Blockchain-Empowered Lifecycle Management for AI-Generated Content Products in Edge Networks," in IEEE Wireless Communications, doi: 10.1109/MWC.003.2300053. https://ieeexplore.ieee.org/document/10422884

Gschnaidtner, Christoph and Dehghan, Robert and Hottenrott, Hanna and Schwierzy, Julian, Adoption and Diffusion of Blockchain Technology ( 2024). ZEW - Centre for European Economic Research Discussion Paper No. 24-018, Available at SSRN: https://ssrn.com/abstract=4775993 or http://dx.doi.org/10.2139/ssrn.4775993

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

## Huggingface Model Collection (Five Random Models)

[Model Collection Results](https://github.com/ericyoc/huggingface-model-metadata-blockchain-poc/blob/main/models_metadata.csv)

## Blockchain Registry
Blockchain:
Block # 0
Timestamp: 2024-05-17 16:09:30.577741
Data: Genesis Block
Previous Hash: 0
Hash: 201577e05a4fc8fc08070d1a38c1a373d507f670c4768480c5a01c451d7cbaa2

Block # 1
Timestamp: 2024-05-17 16:09:40.974353
Data: {'Model Name': 'Akari/albert-base-v2-finetuned-squad', 'Architecture': 'AlbertForQuestionAnswering', 'Vocabulary Size': 30000, 'Special Tokens': {'bos_token': '[CLS]', 'eos_token': '[SEP]', 'unk_token': '<unk>', 'sep_token': '[SEP]', 'pad_token': '<pad>', 'cls_token': '[CLS]', 'mask_token': '[MASK]'}, 'Model Category': 'natural language processing', 'Model Type': 'question-answering', 'Last Modified': '2021-12-02T05:36:13.000Z'}
Previous Hash: 201577e05a4fc8fc08070d1a38c1a373d507f670c4768480c5a01c451d7cbaa2
Hash: 028ba86f4ea485aeffdc2147c4927bc6d5e4fe6145ec8dde04b04373ab5a953c

Block # 2
Timestamp: 2024-05-17 16:09:52.918372
Data: {'Model Name': 'AnonymousSub/rule_based_twostagequadruplet_hier_epochs_1_shard_1', 'Architecture': 'BertModel', 'Vocabulary Size': 30522, 'Special Tokens': {'unk_token': '[UNK]', 'sep_token': '[SEP]', 'pad_token': '[PAD]', 'cls_token': '[CLS]', 'mask_token': '[MASK]'}, 'Model Category': 'other', 'Model Type': 'feature-extraction', 'Last Modified': '2022-01-10T21:09:40.000Z'}
Previous Hash: 028ba86f4ea485aeffdc2147c4927bc6d5e4fe6145ec8dde04b04373ab5a953c
Hash: 1686c889801d988b1f7af2ceab402621b40a66815195f23d05be70f0c187bc37

Block # 3
Timestamp: 2024-05-17 16:09:58.646899
Data: {'Model Name': 'AnonymousSub/rule_based_hier_quadruplet_epochs_1_shard_1_wikiqa', 'Architecture': 'BertForSequenceClassification', 'Vocabulary Size': 30522, 'Special Tokens': {'unk_token': '[UNK]', 'sep_token': '[SEP]', 'pad_token': '[PAD]', 'cls_token': '[CLS]', 'mask_token': '[MASK]'}, 'Model Category': 'natural language processing', 'Model Type': 'text-classification', 'Last Modified': '2022-01-23T01:42:47.000Z'}
Previous Hash: 1686c889801d988b1f7af2ceab402621b40a66815195f23d05be70f0c187bc37
Hash: 47ac7d44f1f5c3fcad9f40facae47820b1743c8bdc47c36c7d0db76d0d03b551

Block # 4
Timestamp: 2024-05-17 16:10:27.566505
Data: {'Model Name': '0x7o/keyt5-base', 'Architecture': 'T5ForConditionalGeneration', 'Vocabulary Size': 32100, 'Special Tokens': {'eos_token': '</s>', 'unk_token': '<unk>', 'pad_token': '<pad>', 'additional_special_tokens': ['<extra_id_0>', '<extra_id_1>', '<extra_id_2>', '<extra_id_3>', '<extra_id_4>', '<extra_id_5>', '<extra_id_6>', '<extra_id_7>', '<extra_id_8>', '<extra_id_9>', '<extra_id_10>', '<extra_id_11>', '<extra_id_12>', '<extra_id_13>', '<extra_id_14>', '<extra_id_15>', '<extra_id_16>', '<extra_id_17>', '<extra_id_18>', '<extra_id_19>', '<extra_id_20>', '<extra_id_21>', '<extra_id_22>', '<extra_id_23>', '<extra_id_24>', '<extra_id_25>', '<extra_id_26>', '<extra_id_27>', '<extra_id_28>', '<extra_id_29>', '<extra_id_30>', '<extra_id_31>', '<extra_id_32>', '<extra_id_33>', '<extra_id_34>', '<extra_id_35>', '<extra_id_36>', '<extra_id_37>', '<extra_id_38>', '<extra_id_39>', '<extra_id_40>', '<extra_id_41>', '<extra_id_42>', '<extra_id_43>', '<extra_id_44>', '<extra_id_45>', '<extra_id_46>', '<extra_id_47>', '<extra_id_48>', '<extra_id_49>', '<extra_id_50>', '<extra_id_51>', '<extra_id_52>', '<extra_id_53>', '<extra_id_54>', '<extra_id_55>', '<extra_id_56>', '<extra_id_57>', '<extra_id_58>', '<extra_id_59>', '<extra_id_60>', '<extra_id_61>', '<extra_id_62>', '<extra_id_63>', '<extra_id_64>', '<extra_id_65>', '<extra_id_66>', '<extra_id_67>', '<extra_id_68>', '<extra_id_69>', '<extra_id_70>', '<extra_id_71>', '<extra_id_72>', '<extra_id_73>', '<extra_id_74>', '<extra_id_75>', '<extra_id_76>', '<extra_id_77>', '<extra_id_78>', '<extra_id_79>', '<extra_id_80>', '<extra_id_81>', '<extra_id_82>', '<extra_id_83>', '<extra_id_84>', '<extra_id_85>', '<extra_id_86>', '<extra_id_87>', '<extra_id_88>', '<extra_id_89>', '<extra_id_90>', '<extra_id_91>', '<extra_id_92>', '<extra_id_93>', '<extra_id_94>', '<extra_id_95>', '<extra_id_96>', '<extra_id_97>', '<extra_id_98>', '<extra_id_99>']}, 'Model Category': 'other', 'Model Type': 'text2text-generation', 'Last Modified': '2022-01-11T03:52:53.000Z'}
Previous Hash: 47ac7d44f1f5c3fcad9f40facae47820b1743c8bdc47c36c7d0db76d0d03b551
Hash: 5b6f7e586e6026f015802dac2b4a5c0893272fa4c8695a5f6e67371bdd3bca83

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the functionality or documentation of the project.

## Disclaimer
This repository is for education and research purpose only.

## License
Copyright 2024 Eric Yocam

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
