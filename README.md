# FineTune

Adapter for the text-gen model: Lornng/Llama2-7B-QLoRA-cpgQA-adapter-text-gen-final

Merged model for text-gen: Lornng/Llama2-7b-merged-qlora-cpgQA-text-gen-final

Dataset used: Lornng/cpgQA-textcol-splitted

Wandb will be used to keep track of the training of the fine tuned model 

Steps:
1. Use the **code: Llama2_text_gen_cpgQA.ipynb**
2. Before step 1, split the dataset according to the QA or Text-gen format **code: split_dataset.ipynb**
3. After the Training Done from step 1, use **code: merge_model.ipynb to merge**
4. Here is to evaluate the model **code: Evaluation_of_Llama2_7B_hf.ipynb**
5. Use to deploy the model **code: Finetuned_Llama2_Interface.ipynb**
