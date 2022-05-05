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
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/17e8op6X5sPvoYqNwO8bwpw), password: 4n7d; size: 36.14 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID006.**</font>  
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
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID007.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1prIlkCMwl01YeEI3ZuplXQ), password: 9y4x; size: 3.47 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/138o7Wagq1SozcWnynO6vRA), password: rjfx; size: 3.61 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1RkDu2qSS2yu_3iPUR-S70Q), password: ppsf; size: 8.60 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID008.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1DC5xB_FoNBRvvkGoYgVwMQ), password: ft01; size: 2.84 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1xBvprKtYvOB4RXnWUPm-dQ), password: cf0w; size: 2.78 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1O8OFpHSTBmIMDtMzBqcaoQ), password: 2v1t; size: 1.10 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1QBr6_fs-uPr7bksJ2w3yYQ), password: laoh; size: 2.94 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1xH72dEJwI6GFaLLerkzt4w), password: ua9h; size: 2.87 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/10EVvzWY-1I9q3NJCeGOkeg), password: 9713; size: 1.14 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1EMGNk1C86gDqq-PbR2VPNw), password: v1ki; size: 12.95 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID009.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1cz2ftNEZsjc87odOSwyctQ), password: owo3; size: 3.26 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1OdNlTT2HskTLFvhuxpF_Og), password: enj6; size: 2.78 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1qppHWuSKwkVsfeVkOUXIMg), password: dw53; size: 2.88 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1Hkp1jfjyRZOBOtioDWcElw), password: 5dqw; size: 3.28 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1RWlg7HITcOh5ySxkiYQSMA), password: 8b17; size: 2.84 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1dlywzEIQkDiB2N4NBZ1rUg), password: lajy; size: 2.93 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/19zyY8FQqnSF0WC9DS02TgA), password: run6; size: 24.57 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID010.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/19ypL3GOsXKGaeG_T5hmufA), password: z85z; size: 2.54 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1QzwtICpySJQAJWKKL-vxsw), password: 0cbc; size: 2.62 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1Zao2RVU7xmVwQqzNeWoR4g), password: 4n4s; size: 7.23 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID011.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [download](https://pan.baidu.com/s/1YlF3ULcrOl7dWtgvFQT6og), password: s7fz; size: 1.00 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [download](https://pan.baidu.com/s/1pyaL1eA-E3Jd8oKHuqMGyw), password: ilji; size: 1.02 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1UkfYeu3vx1HFa2HsTn7H-Q), password: 68dz; size: 3.51 MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID012.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1Am5QR31G5BonrWj7bh_zow), password: 11co; size: 2.82 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1ayEWwDbUuZnZftmaO2LG9g), password: uqwb; size: 3.20 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1zLxPHyh6jQe6-JungVMmRw), password: wx7y; size: 2.77 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1GTnSY2PKgjh99ld3vKKL2A), password: lajr; size: 2.98 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1TBCzdxNwDTTiEZeUwg54Wg), password: bf5c; size: 3.35 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1vMdUnCyfvOKpBVoSQDFjdg), password: aemg; size: 2.82 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/13apgNSakdg_KKfZ2yqn2OA), password: ocb8; size: 25.46 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID013.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1mK7Qd9pZyfN64sZY_dKA0w), password: hgs8; size: 4.87 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1vmj1IF-EPCWXoFHNO0JNVg), password: eaq2; size: 4.96 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1Uq8Xl96QxnLeaAg5bQnXpA), password: qk7w; size: 5.13 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/1BjEh4VTsBUWCTiBGqTEL0Q), password: 1d4f; size: 2.37 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1JAjkqxANZmmB-D_ss-bNBw), password: y6an; size: 4.82 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1ywnzwCUu-jEeAoN5Fj-ozg), password: ghfu; size: 4.88 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1cX15KhYK1RSmMFmHRg5M_g), password: rkyj; size: 5.06 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/1K4wSRMlqSbIFhexTpFG2qA), password: efql; size: 2.30 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1pIAKTdgenCmi_SILSKwnfw), password: 8s65; size: 29.21 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID014.**</font>  
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
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID015.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/1G-JHfCl0BZywuCAvqHJAUA), password: 5sis; size: 5.50 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/14I2n1AsTxlJ-fuP3bR_cxg), password: d2kf; size: 2.68 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/1VRTJgfj-KjtxiTROteMfAg), password: sq7k; size: 5.41 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1uK0xryKdpErf-6RRedGrPg), password: tmym; size: 2.62 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/18G4VD1lxgN84zDs-U_Riiw), password: bsol; size: 13.16 MB.</font> 
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID016.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1: [download](https://pan.baidu.com/s/10KCnI7O31YTFrm6S20Rf6g), password: qpl8; size: 4.89 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2: [download](https://pan.baidu.com/s/1zqeLpKxjih1ImTvth2iUKQ), password: vzzy; size: 5.22 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3: [download](https://pan.baidu.com/s/1OnkIBS4ci965n_c3bA2mqA), password: 53jw; size: 5.05 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4: [download](https://pan.baidu.com/s/1U0mi8T6VbTMPloSdvyKHxQ), password: 1kcr; size: 3.00 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1: [download](https://pan.baidu.com/s/10Z_J9XxOCpzsYx85B49yoA), password: 4tsg; size: 4.83 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2: [download](https://pan.baidu.com/s/1nIKKfz0eAhaywOUxORNMRg), password: x6he; size: 5.14 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3: [download](https://pan.baidu.com/s/1uBhOTdwegGTGyXy3FiYtKQ), password: bibx; size: 5.01 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4: [download](https://pan.baidu.com/s/13poecMZCVRA25U1eWKv4NA), password: 5a4o; size: 2.99 GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [download](https://pan.baidu.com/s/1T7h_Ms2HoBn7ersFhOFghQ), password: 6kcu; size: 30.56 MB.</font> 
  
  *<font color="#dd0000">(The following sections of data are being uploaded and cannot be accessed temporarily. We will update the data upload progress every day.)</font>*  

&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID017.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID018.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID019.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx MB.</font>  
  
&emsp;&emsp; <font face="Times New Roman" size = 5>**WHUVID020.**</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam0: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>cam1: [xxx](), password: xxx; size: xxx GB.</font>  
  &emsp;&emsp;&emsp; <font face="Times New Roman" size = 3>other_files: [xxx](), password: xxx; size: xxx MB.</font>  
  


## <center><font face="Times New Roman"> WHUVID021 - WHUVID034: Coming soon... </font></center>
  
## <center><font face="Times New Roman"> Cite:</font></center>  
  
<font face="Times New Roman" size = 5>If you use this dataset for your research, please cite our paper. </font>  
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
