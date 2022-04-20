
# <center><font face="Times New Roman"> WHUVID: Wuhan Urban Visual-inertial Dataset </font></center>

*<center><font face="Times New Roman" size = 3> Author：[chentianyang](https://github.com/chentianyangWHU) &emsp;&emsp; E-mail：tychen@whu.edu.cn &emsp;&emsp; </center>*

&emsp; &emsp;<font face="Times New Roman" size = 4> **Here, we present a challenging stereo-inertial dataset collected onboard a sports utility vehicle for the tasks of visual-inertial odometry/simultaneous localization and mapping (VIO/SLAM), autonomous driving, object detection, and other computer vision techniques.** We recorded a large set of time-synchronized stereo image sequences (2x1280x720@30fps RGB) and corresponding inertial measurement unit (IMU) readings (400Hz) from a Stereolabs ZED2 camera, along with centimeter-level-accurate six-degree-of-freedom ground truth (100Hz) from a u-blox GNSS-IMU navigation device with real-time-kinematic correction signals. The dataset comprises 34 sequences recorded during November 2020 in Wuhan, the largest city of Central China. Further, the dataset contains abundant unique urban scenes and features of a complex modern metropolis, which have rarely appeared in previously released benchmarks. Results from milestone VIO/SLAM algorithms reveal that methods exhibiting excellent performance on established datasets such as KITTI and EuRoC perform unsatisfactorily when moved outside the laboratory to the real world. We expect our dataset to reduce this limitation by providing more challenging and diverse scenarios to the research community. The full dataset with raw and calibrated data is publicly available along with a lightweight MATLAB/Python toolbox for preprocessing and evaluation.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>The presented novel large dataset (up to 570GB) has complex urban scenarios for VIO/SLAM and autonomous driving. To further promoting the development of these technologies, we make it public. Owning to the space limitation of github, we can only upload the groundtruth images and videos for preview, which are in **folder "groundtruth" and folder "previews"**, respectively. Calibration results using kalibr are stored in **folder "[calibration](https://github.com/chentianyangWHU/WHUVID/tree/main/Calibration)"** and raw data used for calibrating can be downloaded from links listed below. **To get full dataset with 34 image sequences, please click the links of Baidu Netdisk shared below.** Note that due to the dataset is so huge, we have only uploaded part of the dataset so far (April 19, 2022), and the rest is being uploaded. The whole dataset is expected to be completed **within two week**.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>The links are as follows:</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>Calibration data.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>zip file:[link](), password:xxx; size: 1.80 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>ros bag :[link](), password:xxx; size: 2.51 GB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID001.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: 9.61 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: 9.46 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: 35.18 MB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID002.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: 9.25 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: 9.01 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: 15.41 MB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID003.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: 9.79 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: 9.48 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: 14.92 MB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID004.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: 4.62 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: 4.60 GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: 5.27 MB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID005.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part1:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part2:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part3:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part4:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part5:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part6:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part7:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0_part8:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part1:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part2:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part3:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part4:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part5:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part6:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part7:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1_part8:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: 36.14 MB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID006, size: 32.9GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: xxx GB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID007, size: 7.1GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: xxx GB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID008, size: 13.6GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: xxx GB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID009, size: 18GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: xxx GB.</font>

&emsp;&emsp; <font face="Times New Roman" size = 4>WHUVID010, size: 5.2GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam0:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>cam1:[link](), password:xxx; size: xxx GB.</font>
&emsp;&emsp; <font face="Times New Roman" size = 3>other_files:[link](), password:xxx; size: xxx GB.</font>



## <center><font face="Times New Roman"> WHUVID011 - WHUVID034: Coming soon... </font></center>
