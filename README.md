# Materials Science and Chemistry LLM Resources
A public repository collecting links to state-of-the-art training sets, QA, benchmarks and other evaluations for various ML and LLM applications in materials science and chemistry.

## Chemistry
* [ChemQA](https://huggingface.co/datasets/shangzhu/ChemQA): ChemQA is a Multimodal Question-and-Answering dataset on chemistry reasoning. This work is inspired by IsoBench and ChemLLMBench. Containts 5 QA Tasks in total: Counting Numbers of Carbons and Hydrogens in Organic Molecules, Calculating Molecular Weights in Organic Molecules, Name Conversion: From SMILES to IUPAC, Molecule Captioning and Editing, and retro-synthesis Planning: inspired by [2], adapted from dataset provided in [4], following the same training, validation and evaluation splits.
* [ChemLLMBench](https://github.com/ChemFoundationModels/ChemLLMBench): A comprehensive benchmark on eight chemistry tasks
* [SMolInstruct](https://huggingface.co/datasets/osunlp/SMolInstruct): SMolInstruct is a large-scale, comprehensive, and high-quality instruction tuning dataset crafted for chemistry. It centers around small molecules, and contains 14 meticulously selected tasks and over 3M samples. This dataset has both SMILES and SELFIES versions, and you could switch to SELFIES by using use_selfies=True when loading. Tasks include name conversion, property prediction, molecule description, and chemical reaction prediction.
* [CamelAI - Chemistry](https://huggingface.co/datasets/camel-ai/chemistry): Chemistry dataset is composed of 20K problem-solution pairs obtained using gpt-4. The dataset problem-solutions pairs generating from 25 chemistry topics, 25 subtopics for each topic and 32 problems for each "topic,subtopic" pairs.
* [ChemData700k](https://huggingface.co/datasets/AI4Chem/ChemData700K?row=0): ChemData is a large-scale chemistry competency instruction tuning dataset for language models, which includes nine chemistry core tasks and 730K high-quality questions and answers, sampled from 1/10 of 7 million pieces of data.
* [ChemBench4k](https://huggingface.co/datasets/AI4Chem/ChemBench4K): ChemBench is a large-scale chemistry competency evaluation benchmark for language models, which includes nine chemistry core tasks and 4100 high-quality single-choice questions and answers.
* [ChemBench - Lamalab](https://github.com/lamalab-org/chem-bench):  A benchmark with more than 7000 questions, manually curated for various chemical topics. Covering multi-choice and free-form questions. Supports models as well as tool-augmented systems. Provides [leaderboards](https://lamalab-org.github.io/chem-bench/leaderboard/) and [human baseline](https://chembench.org/). See [paper](https://arxiv.org/abs/2404.01475) for more details.
* [Chem-RnD and ChemEDU CLAIRify](https://github.com/ac-rad/xdl-generation/tree/master/datasets): Chem-EDU (Everyday Educational Chemistry) - 40 natural language instructions containing only safe (edible) chamicals. Chem-RnD (Chemistry Research & Development) - 108 detailed chemistry-protocols for synthesizing different organic compounds in real-world chemisty labs. This is a subset of Benchmarking results and the XDL XML schema.

## Materials
* [Battery Device QA](https://huggingface.co/datasets/batterydata/battery-device-data-qa): Battery device records, including anode, cathode, and electrolyte.
Examples of the question answering evaluation dataset: {'question': 'What is the cathode?', 'answer': 'Al foil', 'context': 'The blended slurry was then cast onto a clean current collector (Al foil for the cathode and Cu foil for the anode) and dried at 90 °C under vacuum overnight.', 'start index': 645}
* [MaScQA](https://github.com/M3RG-IITD/MaScQA.git): A dataset of 650 challenging questions from the materials domain that require the knowledge and skills of a materials science student who has cleared their undergraduate degree. Questions are classified based on their structure and the materials science domain-based subcategories.
* [Optical BERT Training Data](https://huggingface.co/datasets/opticalmaterials/test_datasets): Has HF errors, but data are available.
* [Optical Table QA](https://huggingface.co/datasets/opticalmaterials/OpticalTableQA): 
* [LLMs for Sustainable Concrete](https://github.com/BAMcvoelker/LLM-s-can-Design-Sustainable-Concrete-a-Systematic-Benchmark-Code-) [paper](https://www.researchsquare.com/article/rs-3913272/v1)
* [PNCExtract: Extracting Polymer Nanocomposite Samples from Articles](https://github.com/ghazalkhalighinejad/PNCExtract): The contains a manually curated list of samples for each PNC article. The data is divided into 52 validation articles and 151 test articles.

## Multimodal
* [Wikipedia Materials Multimodal](https://huggingface.co/datasets/lamm-mit/Cephalo-Wikipedia-Materials)

## Unknown Quality
[Chemistry Dataset from Andrersonbcedef](https://huggingface.co/datasets/andersonbcdefg/chemistry)

## Contributing Guidelines
Add other resources to the list by 1. forking the repository and creating a pull request back to the main repository or 2. create an issue with the markdown that should be added to the repository and one of the admins will add to the main document.

If you would like to help maintain this repository, open an issue expressing your interest and we will reach out to you!

