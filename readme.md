# <center><font face="Times New Roman"> WHUVID (Wuhan Urban Visual-inertial Dataset) for vSLAM and VIO </font></center>

*<center><font face="Times New Roman" size = 3> Author：[chentianyang](https://github.com/chentianyangWHU) &emsp;&emsp; E-mail：tychen@whu.edu.cn &emsp;&emsp; </center>*

  
## <center><font face="Times New Roman"> Abstract</font></center>  
<font face="Times New Roman" size = 5>**Here, we present a challenging stereo-inertial dataset collected onboard a sports utility vehicle for the tasks of visual-inertial odometry/simultaneous localization and mapping (VIO/SLAM), autonomous driving, object detection, and other computer vision techniques.** We recorded a large set of **time-synchronized stereo image sequences (2x1280x720@30fps RGB) and corresponding inertial measurement unit (IMU) readings (400Hz)** from a Stereolabs ZED2 camera, along with **centimeter-level-accurate six-degree-of-freedom ground truth (100Hz)** from a u-blox GNSS-IMU navigation device with real-time-kinematic correction signals. The dataset comprises **34 sequences recorded during November 2020 in Wuhan, the largest city of Central China**. Further, the dataset contains abundant unique urban scenes and features of a complex modern metropolis, which have rarely appeared in previously released benchmarks. Results from milestone VIO/SLAM algorithms reveal that methods exhibiting excellent performance on established datasets such as KITTI and EuRoC perform unsatisfactorily when moved outside the laboratory to the real world. We expect our dataset to reduce this limitation by providing more challenging and diverse scenarios to the research community. The full dataset with raw and calibrated data is publicly available along with a lightweight MATLAB/Python toolbox for preprocessing and evaluation.</font>  
  
<font face="Times New Roman" size = 5>The presented novel large dataset **(up to 570GB)** has complex urban scenarios for VIO/SLAM and autonomous driving. To further promoting the development of these technologies, we make it public. Owning to the space limitation of github, we can only upload the groundtruth images and videos for preview, which are in folder **[groundtruths](https://github.com/chentianyangWHU/WHUVID/groundtruths)** and folder **[previews](https://github.com/chentianyangWHU/WHUVID/previews)**, respectively. Calibration results using kalibr are stored in folder **[Calibration](https://github.com/chentianyangWHU/WHUVID/Calibration)** and raw data used for calibrating can be downloaded from links listed below. **To get full dataset with 34 image sequences, please click the links of Baidu Netdisk shared below.** Note that due to the dataset is so huge, we have only uploaded part of the dataset so far (April 19, 2022), and the rest is being uploaded. The uploading work is expected to be completed **within three week**.</font>  

## <center><font face="Times New Roman"> Paper</font></center>  
  <font face="Times New Roman" size = 5>For more information, please refer to our paper: </font>  
  [WHUVID: A Large-Scale Stereo-IMU Dataset for Visual-Inertial Odometry and Autonomous Driving in Chinese Urban Scenarios](https://www.mdpi.com/2072-4292/14/9/2033)
  
## <center><font face="Times New Roman"> Download</font></center>
<font face="Times New Roman" size = 8>**Links are as follows:**</font>  
  
  *<font color="#dd0000">(The following sections of data have been uploaded and can be downloaded.)</font>*  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**Calibration data.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>zip file: [download](https://pan.baidu.com/s/1vEJYteSgoEzjKjSE4Ae2xg), password: CAzp; size: 1.80 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>ros bag : [download](https://pan.baidu.com/s/1oRQV3-NHgUUnmmwHgttKJQ), password: CArb; size: 2.51 GB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID001. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1ah8hkRhkWkwY22kD_v4ofA), password: 8x14; size: 9.61 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1MdXfC-LKP6djzQ1WgHoW0A), password: e2sd; size: 9.46 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1encX6-eBbM0-lyRI5WkcTA), password: d60b; size: 35.18 MB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID002. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1plinLkG-7ff8IbyQa5e5Rw), password: t3du; size: 9.25 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1piuU9i9hbMczcb3U-A-w0w), password: cw8i; size: 9.01 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/15KXPY02h1EHDfG20xGSRig), password: v1me; size: 15.41 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID003. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1iQ_K0Lym7bTgzI7FZWb6wQ), password: t3hi; size: 9.79 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1FSkJWkGs-CD667gbHmgW_A), password: e56x; size: 9.48 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1DGOMgIyVIBJ_Ynqb9oCRiw), password: fdgu; size: 14.92 MB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID004. (Stereo)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1QI0gcYiqqAS44mz5HIStCw), password: 6ijv; size: 4.62 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1VlQfe7fR3Rgr4vJfi-fwYg), password: a7nf; size: 4.60 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1zcq2dNPtDbWWlhlsrnAgqA), password: z83q; size: 5.27 MB.</font>  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID005. (Stereo + BoundingBox)**</font>  
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
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/17e8op6X5sPvoYqNwO8bwpw), password: 4n7d; size: 36.14 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID006. (Stereo + IMU + GT)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/14zSRihjV5ZiUIJEZ_cY7lA), password: vom7; size: 3.46 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1koe_sHWkBkqEBaFdSjqAbw), password: ysff; size: 3.51 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/10obTFvy9W6nmUwuo-wiXcA), password: udu4; size: 3.15 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/1cKgilk1rHzmVXpEVhsYNZQ), password: w2es; size: 2.93 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part5: [download](https://pan.baidu.com/s/1klnOKL8j21oazmfxxDRyiA), password: ea4v; size: 3.14 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1m8jHrpk55TSLUtqyXiGgow), password: lqtd; size: 3.57 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1OPMOIqGF_G8Kk2_vF3SVvw), password: cxvj; size: 3.65 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1SCBlq8sB_Kk3ErZ0uIleDA), password: xioe; size: 3.27 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/1wuQKeID1X15XausWY8MOMA), password: kkyc; size: 3.04 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part5: [download](https://pan.baidu.com/s/1KyEzKSlqDfKYvPW-J6PmLw), password: 2s0s; size: 3.20 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1_6xZAO9zemb_vGgoYy3COA), password: 0dpq; size: 39.94 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID007. (Stereo + IMU + GT)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1prIlkCMwl01YeEI3ZuplXQ), password: 9y4x; size: 3.47 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/138o7Wagq1SozcWnynO6vRA), password: rjfx; size: 3.61 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1RkDu2qSS2yu_3iPUR-S70Q), password: ppsf; size: 8.60 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID008. (Stereo + GT)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1DC5xB_FoNBRvvkGoYgVwMQ), password: ft01; size: 2.84 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1xBvprKtYvOB4RXnWUPm-dQ), password: cf0w; size: 2.78 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1O8OFpHSTBmIMDtMzBqcaoQ), password: 2v1t; size: 1.10 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1QBr6_fs-uPr7bksJ2w3yYQ), password: laoh; size: 2.94 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1xH72dEJwI6GFaLLerkzt4w), password: ua9h; size: 2.87 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/10EVvzWY-1I9q3NJCeGOkeg), password: 9713; size: 1.14 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1EMGNk1C86gDqq-PbR2VPNw), password: v1ki; size: 12.95 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID009. (Stereo + IMU + GT)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1cz2ftNEZsjc87odOSwyctQ), password: owo3; size: 3.26 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1OdNlTT2HskTLFvhuxpF_Og), password: enj6; size: 2.78 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1qppHWuSKwkVsfeVkOUXIMg), password: dw53; size: 2.88 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1Hkp1jfjyRZOBOtioDWcElw), password: 5dqw; size: 3.28 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1RWlg7HITcOh5ySxkiYQSMA), password: 8b17; size: 2.84 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1dlywzEIQkDiB2N4NBZ1rUg), password: lajy; size: 2.93 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/19zyY8FQqnSF0WC9DS02TgA), password: run6; size: 24.57 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID010. (Stereo + IMU + GT)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/19ypL3GOsXKGaeG_T5hmufA), password: z85z; size: 2.54 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1QzwtICpySJQAJWKKL-vxsw), password: 0cbc; size: 2.62 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1Zao2RVU7xmVwQqzNeWoR4g), password: 4n4s; size: 7.23 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID011. (Stereo + IMU + GT)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1YlF3ULcrOl7dWtgvFQT6og), password: s7fz; size: 1.00 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1pyaL1eA-E3Jd8oKHuqMGyw), password: ilji; size: 1.02 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1UkfYeu3vx1HFa2HsTn7H-Q), password: 68dz; size: 3.51 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID012. (Stereo + IMU + GT)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1Am5QR31G5BonrWj7bh_zow), password: 11co; size: 2.82 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1ayEWwDbUuZnZftmaO2LG9g), password: uqwb; size: 3.20 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1zLxPHyh6jQe6-JungVMmRw), password: wx7y; size: 2.77 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1GTnSY2PKgjh99ld3vKKL2A), password: lajr; size: 2.98 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1TBCzdxNwDTTiEZeUwg54Wg), password: bf5c; size: 3.35 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1vMdUnCyfvOKpBVoSQDFjdg), password: aemg; size: 2.82 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/13apgNSakdg_KKfZ2yqn2OA), password: ocb8; size: 25.46 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID013. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1mK7Qd9pZyfN64sZY_dKA0w), password: hgs8; size: 4.87 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1vmj1IF-EPCWXoFHNO0JNVg), password: eaq2; size: 4.96 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1Uq8Xl96QxnLeaAg5bQnXpA), password: qk7w; size: 5.13 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/1BjEh4VTsBUWCTiBGqTEL0Q), password: 1d4f; size: 2.37 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1JAjkqxANZmmB-D_ss-bNBw), password: y6an; size: 4.82 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1ywnzwCUu-jEeAoN5Fj-ozg), password: ghfu; size: 4.88 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1cX15KhYK1RSmMFmHRg5M_g), password: rkyj; size: 5.06 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/1K4wSRMlqSbIFhexTpFG2qA), password: efql; size: 2.30 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1pIAKTdgenCmi_SILSKwnfw), password: 8s65; size: 29.21 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID014. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1bqZgOf5fBkQaR-OjH0LPcw), password: av5c; size: 5.93 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1tzMjcAp_eZXUKR6CYIT-QQ), password: 7bty; size: 5.70 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1hwo267LFuisFpPKsC0eLAw), password: kqg6; size: 5.52 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/1dxfba0AlZGhwbgbHGiBiNw), password: 1y51; size: 5.32 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part5: [download](https://pan.baidu.com/s/1sWiis1_c4FlcTNqv08nYBw), password: qldz; size: 3.95 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1LNubwm1vv-69jL5w4ruMDA), password: z21f; size: 5.75 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1iyNqV4Z17nr8Pa6Rj6jqmg), password: eze2; size: 5.55 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1j_WStlaUx3_AYQQn9bsaZg), password: 94il; size: 5.40 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/15H3_fQ6tvjbrHbcbe5qUBA), password: y6kk; size: 5.22 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part5: [download](https://pan.baidu.com/s/1ORXwJjl8G30_vmdiL1HBtQ), password: 2203; size: 3.87 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1tmyOCsCoYiFOMMz1Oc4t_A), password: q8rq; size: 40.83 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID015. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1G-JHfCl0BZywuCAvqHJAUA), password: 5sis; size: 5.50 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/14I2n1AsTxlJ-fuP3bR_cxg), password: d2kf; size: 2.68 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1VRTJgfj-KjtxiTROteMfAg), password: sq7k; size: 5.41 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1uK0xryKdpErf-6RRedGrPg), password: tmym; size: 2.62 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/18G4VD1lxgN84zDs-U_Riiw), password: bsol; size: 13.16 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID016. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/10KCnI7O31YTFrm6S20Rf6g), password: qpl8; size: 4.89 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1zqeLpKxjih1ImTvth2iUKQ), password: vzzy; size: 5.22 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1OnkIBS4ci965n_c3bA2mqA), password: 53jw; size: 5.05 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/1U0mi8T6VbTMPloSdvyKHxQ), password: 1kcr; size: 3.00 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/10Z_J9XxOCpzsYx85B49yoA), password: 4tsg; size: 4.83 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1nIKKfz0eAhaywOUxORNMRg), password: x6he; size: 5.14 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1uBhOTdwegGTGyXy3FiYtKQ), password: bibx; size: 5.01 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/13poecMZCVRA25U1eWKv4NA), password: 5a4o; size: 2.99 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1T7h_Ms2HoBn7ersFhOFghQ), password: 6kcu; size: 30.56 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID017. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1f7sf3LIhZf7FNVw2sSiCqg), password: u62z; size: 4.73 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1OZ0dn_n_vdh2SEqXtQy1tA), password: 2zke; size: 4.34 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1i0jzkuO0Wj3TLE6g0uB9Wg), password: solx; size: 3.95 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/11Yg95rqVl0_M9mgdAdUj5w), password: 662a; size: 2.93 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1oIh2FeGE0_A8ceSZ24woAA), password: ml35; size: 4.69 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/14MnTwjyfBmq3T2jcjEqU7A), password: sl9x; size: 4.28 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/18cIBJcYRkjzY-x8EimCPgA), password: g3us; size: 3.94 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/1-tZhuaapxFg1nXjCJixY-Q), password: p01j; size: 2.91 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1wUQVwKIHw2chssF3Uchp2g), password: 85wx; size: 32.72 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID018. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1kFbBZUpVXE4_Q1Tgfu_AVg), password: 3u9p; size: 4.29 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1KRjBiL7EkhUXYlBoEm-GlQ), password: 6kna; size: 2.71 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/12QoS065gGEm-YYbP1vtsig), password: 21ly; size: 4.33 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1Iu1o583DeAITBcOggEUrlQ), password: 4ttw; size: 2.72 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1gkFHHsLZTL_ERTK-iiGhiQ), password: 4agx; size: 16.08 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID019. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1Mfu-yr-_YLh0kIHsDdbt9w), password: trms; size: 909.29 MB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1-7XfLDKPBTde5TTgKLuxWw), password: pecn; size: 899.13 MB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1xsgWGWup1dylR8MuCbNJ5w), password: esih; size: 2.43 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID020. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1_mM70TvJNVGITxq_bO4AiQ), password: 8ekf; size: 3.25 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1Pao3VixTm2TXc0CHDbrQlg), password: n77b; size: 3.28 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1HZFOsfJHTwig88fUNvI7oQ), password: deo0; size: 9.94 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID021. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1O_OX2eRPtbcWCvRP0ldSVg), password: yzb8; size: 3.98 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1TH84YZLk2IVcSPI7wMIjVg), password: bi6w; size: 3.94 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1fUvebKi1omDXzHhJXWvIgA), password: qdmn; size: 9.19 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID022. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1AaQRGvI8iHk_ROBiH3rS8Q), password: d6hv; size: 3.58 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/18kkrZW1nIFR0jX0orvEnow), password: tokk; size: 3.56 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1e_eA7YzDZJVOUopch-Quug), password: k0pq; size: 9.23 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID023. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1mRqyd0xGRUR6u1d3p8iDrw), password: jvbi; size: 1.64 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1_fsPSvexuCeW7-Re5kWWWA), password: kfox; size: 1.68 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1uY1t7DS_SJMrBjyjTXfOFw), password: lz4h; size: 4.60 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID024. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1bLiXl0epdWV43GTuuziOpw), password: imew; size: 4.52 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/13G5SqcZ5eh6eucABJnTd9Q), password: 8ozo; size: 4.65 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1uow8Npexau1woqlV9-NPCg), password: dw9t; size: 11.26 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID025. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1m2on-O0dnb8__4ZqwCsqYw), password: vb1f; size: 4.09 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1Lmn7UMna6yBn0EH9bBP0Iw), password: zjgp; size: 2.29 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1RSB_M2UpuCW-_Ke2w_uMEg), password: de0j; size: 4.18 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1c9q7p4ovOR_Qa-0IXuDXVw), password: 7p4p; size: 2.34 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/15ceUSl11wpLAsyhH1NYIfA), password: r099; size: 13.82 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID026. (Stereo + IMU + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/17DwoxxFljqcwfj6PoWxGEQ), password: glt8; size: 4.11 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1hP793-H9P4zbeLXeWx993w), password: dncm; size: 1.21 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1VGY3BX2iKLwVxi6LS3ZB4Q), password: r9rw; size: 4.18 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1OZaz_TZzEQBnnEkyCzW2iQ), password: embz; size: 1.22 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1fdZZN0umwOlkfviwJ7SlXw), password: s0qt; size: 9.66 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID027. (Stereo + IMU + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1uZgas_hc9BR1-5pssnHpQw), password: kcu1; size: 3.97 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1fNI7rU_lcF-SCnLB_C-u7Q), password: hd8g; size: 1.56 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1uVhCjxN9vTb4fbT5FvnQdg), password: n1np; size: 4.06 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1LpgHPSGksrtN66DwrOUr2g), password: gcd3; size: 1.60 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1BYhup2VgtyQ5O8KNW_BhLw), password: gha8; size: 12.02 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID028. (Stereo + IMU + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1ADSei5r5B0_F794HyhX2IQ), password: nrkd; size: 3.45 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1GfaEw16seqIjmd1I1NeUqg), password: xgvz; size: 3.60 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1KPwX-uQa2J35wH3Dju5a6A), password: ewwv; size: 3.56 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1gGeTn7S9-RgtB7VRJWjMiw), password: vog3; size: 3.76 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1DdXQDCPKrSPAPgELKKTODw), password: 3xtk; size: 16.00 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID029. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1Pt2qtZtcPL7cQL8Q3jMK_w), password: eq4q; size: 3.40 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1992cWT4kEmvFhvbBCMf_9w), password: waui; size: 2.86 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1mCt9j3BVpxDBfX9qhVQnHQ), password: icfp; size: 3.47 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1RNzLP8pGLcBz22GsA88Q_Q), password: gsn4; size: 2.89 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1niQVE4wJ6jMe2GVtYgK_wQ), password: k4su; size: 16.15 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID030. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1HTG6jH91_PsNs5iORjc8Ww), password: pvex; size: 3.83 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1UGD0hn_IvnF-QtT58dXvug), password: kqno; size: 3.73 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1yvNXsHKctlFCqL6p1RZz-g), password: 81sv; size: 1.50 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/10SuKOlkasz-NhAqyom3xvQ), password: js35; size: 3.88 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1tW_cVWn20xEr0Z3gDJn4AA), password: dqnx; size: 3.78 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1r27dTP0UaqtA_7cCHTJ7kA), password: p2ek; size: 1.52 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1nE17R6Kcm49124MSzx3nIg), password: b1u3; size: 22.37 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID031. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1ZMm941Q73zL4hn8sZ8dYVg), password: 1vzw; size: 3.72 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1LkFDtS4NRWdIoAon7R1XRQ), password: git8; size: 1.02 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1mD9FgfPAbiBjSVJaNEA2fw), password: ox6s; size: 3.76 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1gsGhPFX1GMlVlULvyAJ2wg), password: 5h40; size: 1.03 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1TV--42jhO2yQBJV685XCJg), password: xssh; size: 13.11 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID032. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1SNHaC1CVJ3F0F674oGqSnQ), password: 8c6z; size: 1.31 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1HbHevreWRyDbpIT3oN-5tw), password: 9uog; size: 1.32 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1IMtEFn_U9Qs1YMxUnoJSLg), password: i2x3; size: 4.58 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID033. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1M4nFv27gMqh49q90NdYA6A), password: ct8z; size: 3.65 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1oYpqRx66h-dtTTp5qfYpag), password: 9qth; size: 2.34 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/18ludCnnLjt_r0TWqaCBwmA), password: gozl; size: 3.69 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/15AOhCHpp8Nl0PNiq63UtyA), password: tl9k; size: 2.46 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/196-X7Ij6-7Ic2R_uiYy1Lw), password: 9mdi; size: 13.65 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID034. (Stereo + IMU + GT + BoundingBox)**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1Rv9gqUXX5qUiLh7_AaYGVQ), password: j5mk; size: 3.79 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/17yc1XoBWQvHLQ8jRfyv_1w), password: a64b; size: 3.87 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1zwG9jRXfBZNuVIgv9E9wdg), password: 264g; size: 3.91 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1VvKl8RIH8TWH_zvUPVctDg), password: fbeb; size: 3.93 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1tn41czkz3TQ6T-ct-sP7WQ), password: ekdq; size: 16.12 MB.</font>  
  
  *<font color="#dd0000">If you have any questions about the dataset or can't get the data from the above links, please don't hesitate to contact me. :)</font>*  
  
## <center><font face="Times New Roman"> Cite:</font></center>  
  
<font face="Times New Roman" size = 5>If you use this dataset for your research, please cite our paper: </font>  
  [WHUVID: A Large-Scale Stereo-IMU Dataset for Visual-Inertial Odometry and Autonomous Driving in Chinese Urban Scenarios](https://www.mdpi.com/2072-4292/14/9/2033)
  
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
