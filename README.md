# Assignment-3
Code files related to the questions asked in assignment 3 of deep learning

To train a model without the attention network (q2,3,4), use the **train_test_model.ipynb ** file.
To crerate and evaluate amodel with a specific set of hyperparameters, run the **train_test()** function. The user will be asked to input the hyperparameters and the after training the evaluation of the model in the validation and the test set is displayed. To perform a hyperparameter search, run the train_wandb_sweep() function. Please make sure that the hyperparameter ranges and the sweep configurations are entered before hand. 
The predictions of the best model (without attention) are stored as csv file in the folder predictions_vanilla. The langauge studied in this assignment is Tamil.


The file named ***RnnWithAttn.ipynb*** can be used to train the model with attention, hyper parameter tuning, usingthe best model after hyper parameter tuning to generate the attention heat as well as connectivity visualisations. The predictions of the best model (without attention) are stored as csv file in the folder predictions_attention. The langauge studied in this assignment is Tamil.



The lyrics are generated using a GPT-2 model which is fine tuned on two seperate datasets, with each containing songs from the rock and hip hop genres respectively. The **GPT_2_lyric_generate.ipynb** file contains functions which import the datasets and train the model. The last two code cells can be used to generate songs by providing a desirable prompt. 
Note- The run_clm and run_generate files are used to train the gpt-2 model and generate lyrics respectively.
