# A Bidirectional Understanding of Contextual Information within Humor
Our project code is organized into 3 directories:
 - Code:
 This contains our python code for the project. We parse our input files, form them into prompts, and then make queries to GPT-3. In order to run the code, you must create a "secret.py" file containing your GPT-3 API Secret Key. The file was not uploaded to github for security reasons.
 - Data:
 This contains our input data files.
 - Results:
 This contains some samples of the results of using these files.
 Task 1 results are in the format of dalle_results_*shot.json.
 
Run experiments:
python ./Code/finetune_gpt3.py 

Run data cleaning script:
python ./Data/file_parser.py
 
 
 
