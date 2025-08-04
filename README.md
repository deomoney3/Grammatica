To run this project:

1. Make a fresh folder and copy all scripts file, final_data.csv file from datasets folder, all vocab files and final_model.pth from models folder to one new single folder

2. If you want to run your inference from our last trained model (i.e. final_model which is epoch 70th model) then just run the model_inference file by: python model_inference.py

3. if you want to train the model:
	a. If you want to train from first epoch then just run: "python model_training.py"
	   It will also save checkpoints after every epoch so that you can resume training whenever you want.

	b. If you want to train after last saved epoch then just open the model_training.py file and uncheck the "#resume_checkpoint='./checkpoints/checkpoint_epoch_5.pth'" in model training code



To run this project:

1. Make a fresh folder and copy all scripts file, final_data.csv file from datasets folder, all vocab files and final_model.pth from models folder to one new single folder

2. If you want to run your inference from our last trained model (i.e. final_model which is epoch 70th model) then just run the model_inference file by: python model_inference.py

3. if you want to train the model:
	a. If you want to train from first epoch then just run: "python model_training.py"
	   It will also save checkpoints after every epoch so that you can resume training whenever you want.

	b. If you want to train after last saved epoch then just open the model_training.py file and uncheck the "#resume_checkpoint='./checkpoints/checkpoint_epoch_5.pth'" in model training code
