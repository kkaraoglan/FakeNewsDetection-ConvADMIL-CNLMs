# FakeNewsDetection-ConvADMIL-CNLMs
This repository contains the code for an innovative research project focused on detecting fake news across social media and online news sources. By leveraging Attention-Based Deep Multiple Instance Learning (ADMIL) alongside state-of-the-art contextual Neural Language Models (cNLMs) like DeBERTa, SGPT, Flair, and GPT-3.5 based ADA-002, this project aims to provide practical and effective solutions for Fake News Detection (FND).

## Introduction

This repository hosts an innovative research focused on the Detection of Fake News (FND) in social media and online news sources. The methods adopted for FND utilize Attention-Based Deep Multiple Instance Learning (ADMIL) and the latest technology in contextual Neural Language Models (cNLMs) for in-depth text analysis. These approaches aim to discern misinformation patterns and disinformation strategies more accurately by contextually analyzing news texts, going beyond superficial analyses. Embeddings provided by state-of-the-art cNLMs such as DeBERTa, SGPT, Flair, and GPT-3.5-based ADA-002 significantly contribute to the development of ADMIL-based detection models. These embeddings support the learning process by enabling the model to extract deeper meanings from data. ADMIL-based models can dynamically focus on significant examples thanks to attention mechanisms. The work also introduces the Conv-ADMIL model, which integrates feature extraction layers from CNNs, significantly enhancing classification performance. Experimental studies on the LIAR and McIntire datasets demonstrate the effectiveness of the proposed methodologies with high F1-scores. This single-authored study has the potential to guide future research in the field of fake news detection, offering practical and innovative approaches for FND tasks.

## Features

- **Deep Multiple Instance Learning**: Uses ADMIL for a nuanced understanding of news articles.
- **Contextual Analysis**: Leverages embeddings from DeBERTa, SGPT, Flair, and ADA-002 to provide deep contextual insights.
- **$Conv-ADMIL$ Model**: Integrates CNN feature extraction layers to enhance classification performance.
- **High Performance**: Demonstrated through experimental studies on LIAR and McIntire datasets, achieving high $F_{1}$-scores.

## Getting Started

### Prerequisites

- Python 3.8+
- Requirements for running the code are listed in `requirements.txt`.

### Installation

1. Clone the repository:

2. Install the required packages:


## Usage

Detailed instructions on how to train and evaluate the models are provided in the `training_instructions.md` file.

## Contributing

Contributions to this project are welcome. Please see `CONTRIBUTING.md` for how to submit improvements.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments

- This project was developed by [Kürşat M. KARAOĞLAN, Ph.D.]. For inquiries or further information, please contact [kursatkaraoglan@gmail.com].
- Special thanks to the developers and researchers behind the cNLMs utilized in this project.



