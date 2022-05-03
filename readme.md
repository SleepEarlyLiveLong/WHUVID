# <center><font face="Times New Roman"> WHUVID (Wuhan Urban Visual-inertial Dataset) for vSLAM and VIO </font></center>

*<center><font face="Times New Roman" size = 3> Author：[chentianyang](https://github.com/chentianyangWHU) &emsp;&emsp; E-mail：tychen@whu.edu.cn &emsp;&emsp; </center>*

&emsp; &emsp;<font face="Times New Roman" size = 5> **Here, we present a challenging stereo-inertial dataset collected onboard a sports utility vehicle for the tasks of visual-inertial odometry/simultaneous localization and mapping (VIO/SLAM), autonomous driving, object detection, and other computer vision techniques.** We recorded a large set of **time-synchronized stereo image sequences (2x1280x720@30fps RGB) and corresponding inertial measurement unit (IMU) readings (400Hz)** from a Stereolabs ZED2 camera, along with **centimeter-level-accurate six-degree-of-freedom ground truth (100Hz)** from a u-blox GNSS-IMU navigation device with real-time-kinematic correction signals. The dataset comprises **34 sequences recorded during November 2020 in Wuhan, the largest city of Central China**. Further, the dataset contains abundant unique urban scenes and features of a complex modern metropolis, which have rarely appeared in previously released benchmarks. Results from milestone VIO/SLAM algorithms reveal that methods exhibiting excellent performance on established datasets such as KITTI and EuRoC perform unsatisfactorily when moved outside the laboratory to the real world. We expect our dataset to reduce this limitation by providing more challenging and diverse scenarios to the research community. The full dataset with raw and calibrated data is publicly available along with a lightweight MATLAB/Python toolbox for preprocessing and evaluation.</font>

&emsp;&emsp; <font face="Times New Roman" size = 5>The presented novel large dataset **(up to 570GB)** has complex urban scenarios for VIO/SLAM and autonomous driving. To further promoting the development of these technologies, we make it public. Owning to the space limitation of github, we can only upload the groundtruth images and videos for preview, which are in folder **[groundtruths](https://github.com/chentianyangWHU/WHUVID/groundtruths)** and folder **[previews](https://github.com/chentianyangWHU/WHUVID/previews)**, respectively. Calibration results using kalibr are stored in folder **[Calibration](https://github.com/chentianyangWHU/WHUVID/Calibration)** and raw data used for calibrating can be downloaded from links listed below. **To get full dataset with 34 image sequences, please click the links of Baidu Netdisk shared below.** Note that due to the dataset is so huge, we have only uploaded part of the dataset so far (April 19, 2022), and the rest is being uploaded. The uploading work is expected to be completed **within two week**.</font>

  
## <center><font face="Times New Roman"> Download</font></center>
<font face="Times New Roman" size = 8>**Links are as follows:**</font>  
  
  *<font color="#dd0000">(The following sections of data have been uploaded and can be downloaded.)</font>*  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**Calibration data.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>zip file: [download](https://pan.baidu.com/s/1vEJYteSgoEzjKjSE4Ae2xg), password: CAzp; size: 1.80 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>ros bag : [download](https://pan.baidu.com/s/1oRQV3-NHgUUnmmwHgttKJQ), password: CArb; size: 2.51 GB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID001.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1ah8hkRhkWkwY22kD_v4ofA), password: 8x14; size: 9.61 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1MdXfC-LKP6djzQ1WgHoW0A), password: e2sd; size: 9.46 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1encX6-eBbM0-lyRI5WkcTA), password: d60b; size: 35.18 MB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID002.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1plinLkG-7ff8IbyQa5e5Rw), password: t3du; size: 9.25 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1piuU9i9hbMczcb3U-A-w0w), password: cw8i; size: 9.01 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/15KXPY02h1EHDfG20xGSRig), password: v1me; size: 15.41 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID003.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1iQ_K0Lym7bTgzI7FZWb6wQ), password: t3hi; size: 9.79 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1FSkJWkGs-CD667gbHmgW_A), password: e56x; size: 9.48 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1DGOMgIyVIBJ_Ynqb9oCRiw), password: fdgu; size: 14.92 MB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID004.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1QI0gcYiqqAS44mz5HIStCw), password: 6ijv; size: 4.62 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1VlQfe7fR3Rgr4vJfi-fwYg), password: a7nf; size: 4.60 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1zcq2dNPtDbWWlhlsrnAgqA), password: z83q; size: 5.27 MB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID005.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1FzcqGjSBrbOLWBHn5Tyc5g), password: svgg; size: 4.35 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1hbgtWZpRmP91exEK0M34xg), password: trla; size: 5.52 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1GXjUHvonJhfsvgHSJ4gVbA), password: g51v; size: 6.08 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/1abyPSFm_P-5FJwQcqMqHfQ), password: 8ao8; size: 5.52 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part5: [download](https://pan.baidu.com/s/19AThG8kEFpM3N3vVrdioLQ), password: 1t0k; size: 5.10 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part6: [download](https://pan.baidu.com/s/1eOG2-RguRrtfonGe21JC3Q), password: 6gau; size: 4.34 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part7: [download](https://pan.baidu.com/s/1c1qS6Y8qHGZ63j2cBWw96w), password: oidx; size: 3.46 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part8: [download](https://pan.baidu.com/s/1w7PJjNcNjxVOUIMfjqVE3w), password: c0i5; size: 0.40 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/14yHekaSC26ZYXfRg_83_8g), password: h4bq; size: 4.31 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1zRvCa9HVzzdv38LhYpBJ4A), password: 52me; size: 5.44 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1Bx7rZlk-iTvTmM78AcHpZA), password: bfad; size: 5.90 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/1bwzTVNgmWaO9KOafKdnivg), password: e2eu; size: 5.44 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part5: [download](https://pan.baidu.com/s/1M4fEY0UuHKiIjhXnnrlOtg), password: 55gp; size: 5.05 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part6: [download](https://pan.baidu.com/s/112LVeOmPfoXk3DPc4zwomA), password: 2v8c; size: 4.27 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part7: [download](https://pan.baidu.com/s/1rpr03llP81jocuBMLOAYJw), password: bu2p; size: 3.49 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part8: [download](https://pan.baidu.com/s/1eiddVLyTjPGTUjxQya_b5A), password: li1y; size: 0.43 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files :[download](https://pan.baidu.com/s/17e8op6X5sPvoYqNwO8bwpw), password: 4n7d; size: 36.14 MB.</font>  
  
  *<font color="#dd0000">(The following sections of data are being uploaded and cannot be accessed temporarily. We will update the data upload progress every day.)</font>*  
  
&emsp;&emsp; <font face="Times New Roman" size = 4>**WHUVID006.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx GB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 4>**WHUVID007.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx GB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 4>**WHUVID008.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx GB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 4>**WHUVID009.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx GB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 4>**WHUVID010.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx GB.</font>  



## <center><font face="Times New Roman"> WHUVID011 - WHUVID034: Coming soon... </font></center>
  
## <center><font face="Times New Roman"> Cite:</font></center>  
  
<font face="Times New Roman" size = 5>If you use this dataset for your research, please cite our paper: </font>  
  
  ```
  [WHUVID: A Large-Scale Stereo-IMU Dataset for Visual-Inertial Odometry and Autonomous Driving in Chinese Urban Scenarios](https://www.mdpi.com/2072-4292/14/9/2033)
  ```
  
<font face="Times New Roman" size = 5>... or citation with BibTeX: </font>  
  
  ```
  @article{chen2022whuvid,
  title={WHUVID: A Large-Scale Stereo-IMU Dataset for Visual-Inertial Odometry and Autonomous Driving in Chinese Urban Scenarios},
  author={Chen, Tianyang and Pu, Fangling and Chen, Hongjia and Liu, Zhihong},
  journal={Remote Sensing},
  volume={14},
  number={9},
  pages={2033},
  year={2022},
  publisher={MDPI}
  }
  ```
