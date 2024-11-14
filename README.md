### Step 1: Clone the repo

Clone this repository. All Biomedical data used in the paper are uploaded to this repository, hence you don't have to download that separately.

### Step 2: Create a virtual environment
Note: Scripts in this repository were run using python 3.10.9
conda create -n kg_rag python=3.10.9
conda activate kg_rag


### Step 3: Install dependencies

pip install -r requirements.txt


### Step 4: Run the setup script
Note: Make sure you are in KG_RAG folder. 

Running the setup script will create disease vector database for KG-RAG

python -m kg_rag.run_setup

## Steps to run the code and generate output:
## Instructions to run the code

**1. Set up the environment following Steps 1-4 in the original README.**

**2. Update your Google API key in `gpt_config.env`.**

**3. Replicate KG-RAG with gemini-1.5-flash via `sh run_gemini.sh`.**

**4. Evaluate the model via `python data/assignment_results/evaluate_gemini.py`**

**5. Implement three enhancement strategies in `kg_rag/rag_based_generation/GPT/run_mcq_qa.py`.**

**6. Evaluate these model variants by changing the model output path in the file `data/assignment_results/evaluate_gemini.py` and running the command `python data/assignment_results/evaluate_gemini.py`**













## Citation

@article{soman2023biomedical,
  title={Biomedical knowledge graph-enhanced prompt generation for large language models},
  author={Soman, Karthik and Rose, Peter W and Morris, John H and Akbas, Rabia E and Smith, Brett and Peetoom, Braian and Villouta-Reyes, Catalina and Cerono, Gabriel and Shi, Yongmei and Rizk-Jackson, Angela and others},
  journal={arXiv preprint arXiv:2311.17330},
  year={2023}
}
 prepare a readme.md file  













