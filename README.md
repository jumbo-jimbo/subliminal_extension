ALL CODE MODIFIED/FROM https://github.com/MinhxLe/subliminal-learning (I butchered this to run in jupyter notebooks.)

TLDR: replicated subliminal learning using 4o mini. 

I used gpt-4o-mini-2024-07-18. I uploaded all files to OpenAI platform website instead of CLI. 

Replicated subliminal learning phenomena by:

1) create datasets (with and without system prompt) for batch processing in create_batch.ipynb (goes to batch_prompts)
2) upload for batch processing. put results in batch_responses/
3) create finetuning datasets in create_ft_datasets.ipynb . this creates the filtered datasets in preft_sample/ and then samples 10,000 prompt/response pairs for finetuning into ft_datasets/
4) upload these for finetuning. 
5) create the evaluation datasets in create_eval_datasets.ipynb 
6) upload for batch processing. put results in eval_responses/
7) analyze favorite animal in analysis.ipynb . this roughly replicates phenomenon from the paper.

Now to extend the idea and finetune base models WITH DATA GENERATED FROM THE STUDENTS to see if the subliminal learning goes beyond one layer of students.

8) create datasets (no system prompt) for batch processing in create_batch_student.ipynb
9) upload for batch processing.
10) create finetuning datasets.
11) upload for finetuning.
12) create evaluation datasets.
13) upload for batch processing.
14) analyze results. 

27 Jul 2025, 1633: waiting to complete

