Matriculation number: G2102327H
Codalab username: JunHaoGoh

Details to run script:
- Run 'ACV_Project1_Goh_Jun_Hao.ipynb' in google colab with GPU
- data files were on google drive that is mounted by the user using the user's own google drive, 
  below are the data directory needed to run the code:
	- data_root = Root of data file that contains folders with training image, training mask, 
		      validation images, validation mask, testing images
	- train_img_dir = folder containing training images (train_image)
	- train_ann_dir = folder containing training mask images (train_mask)
	- val_img_dir = folder containing validation images (val_image)
	- val_ann_dir = folder containing validation mask images (val_mask)

- work_dir = directory to store the checkpoints and json log file
- Run all cells except for ORCNet Config (experimental)
- Run PSPNet Config, 512x512_20k (Actual)
- Run Output Segmentation File and state file directory of test_image and file directory for output of test_mask file

Third-party library:
Experiment were ran with the help of MMSegmentation from OpenMMLab:
https://github.com/open-mmlab/mmsegmentation

Files that is submited:
Code: ACV_Project1_Goh_Jun_Hao.ipynb
Checkpoint: Checkpoint.pth (Final checkpoint)
Screenshot of Codalab Leaderboard: Leaderboard SS.jpg
PDF Report: Project1_G2102327H.pdf
Best results (predicted masks): pred_mask_final (folder)


