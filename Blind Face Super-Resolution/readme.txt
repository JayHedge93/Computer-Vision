Matriculation number: G2102327H
Codalab username: JunHaoGoh

Details to run script:
- Run 'ACV_Project2_Goh_Jun_Hao.ipynb' in google colab with GPU
- data files were on google drive that is mounted by the user using the user's own google drive, 
  below are the data directory needed to run the code:
	For Configuration
	- cfg.data.train.dataset.lq_folder = training data GT folder
	- cfg.data.train.dataset.gt_folder = training data GT folder
	- cfg.data.val.lq_folder = validation LQ folder
	- cfg.data.val.gt_folder = validation GT folder
	- cfg.data.test.lq_folder = test LQ photo
	- cfg.data.test.gt_folder = validation GT folder (as a place-holder for the code to run)
	
	For Testing:
	- save_path = directory to save predicted HQ data
	
- work_dir = directory to store the checkpoints and json log file
- Run all cells from top to bottom

Third-party library:
Experiment were ran with the help of MMEditing from OpenMMLab:
https://github.com/open-mmlab/mmediting

Files that is submited:
Code: ACV_Project2_Goh_Jun_Hao.ipynb
Checkpoint: checkpoint.pth (Final checkpoint)
Screenshot of Codalab Leaderboard: leaderboard_SS.jpg
PDF Report: Project2_G2102327H.pdf
Predicted HQ images from model: pred_HQ (Folder)
Training Log: train.log


