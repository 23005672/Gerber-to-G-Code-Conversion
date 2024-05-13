# Gerber-to-G-Code-Conversion
# Aim
To convert the Gerber File into G-Code using Copper CAM.
# Software required
Copper CAM
# Procedure
1. Open your Gerber file (File → Open → New circuit)</br>
2. Open your Drill file (File → Open → Drill)</br>
3. Match the drill file and engraving file if not matched </br>
4. Right click the pad and set define as pad and then Right click and select edit all identical pads as set the drill size as 0.8mm,1mm.</br>
5. Open your Cutting file (File → Open → Additional Layer and load your cutting file</br>
6. Go to file/Orgin and set x=0,y=0 </br>
7. Go to file/offset and select the option shift manually</br>
8. Select the layer 6 and move the cutting file and set the border</br>
9. Go to parameter/ tool library and check the identifaication and specification</br>
10. Go to parameter/selected tool and check the engraving tool, cutting tool and drill tool</br>
11. Go to machine/ Contours/calculate Contours</br>
12. Go to machine/mill and select engraving you will get the g code,similarly for Drill and cut. </br>
13. Save the G code</br>
# Contours Output
![Screenshot 2024-05-13 143850](https://github.com/23005672/Gerber-to-G-Code-Conversion/assets/138971519/37f1a4cc-167d-4d71-ae25-a31c8a627c38)

# G Code
### Engraving G Code
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 13/05/2024 at 12:56 )
( Workpiece dimensions: 94.92 x 71.237 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #1 "Basic Engraver" / Diameter 3.17 mm )
T1 M06
M03 S12000
M07
G00 X49.294 Y5.462
G00 Z0
G01 F60 Z-0.2
G01 F600 X48.919 Y5.836
G01 X47.601
G01 X46.668 Y4.904
G01 Y4.425
G01 X14.589
G01 X14.506 Y4.526
G01 X14.391 Y4.62
G01 X14.26 Y4.69
G01 X14.151 Y4.724
G01 Y9.118
G01 X16.047 Y11.015
G01 X16.089 Y10.981
G01 X16.22 Y10.911
G01 X16.362 Y10.868
G01 X16.51 Y10.853
G01 X16.658 Y10.868
G01 X16.8 Y10.911
G01 X16.931 Y10.981
G01 X17.046 Y11.075
G01 X17.14 Y11.19
G01 X17.21 Y11.321
G01 X17.253 Y11.463
G01 X17.268 Y11.611
G01 X17.253 Y11.758
G01 X17.21 Y11.9
G01 X17.14 Y12.031
G01 X17.046 Y12.146
G01 X16.931 Y12.24
G01 X16.8 Y12.31
G01 X16.658 Y12.354
G01 X16.51 Y12.368
G01 X16.362 Y12.354
G01 X16.22 Y12.31
G01 X16.089 Y12.24
G01 X15.974 Y12.146
G01 X15.88 Y12.031
G01 X15.81 Y11.9
G01 X15.767 Y11.758
G01 X15.752 Y11.611
G01 X15.767 Y11.463
G01 X15.81 Y11.321
G01 X15.871 Y11.206
G01 X13.929 Y9.264
G01 X13.913 Y9.244
G01 X13.901 Y9.222
G01 X13.893 Y9.197
G01 X13.891 Y9.172
G01 Y4.74
G01 X13.822 Y4.734
G01 X13.68 Y4.69
G01 X13.549 Y4.62
G01 X13.434 Y4.526
G01 X13.34 Y4.411
G01 X13.27 Y4.28
G01 X13.227 Y4.138
G01 X13.212 Y3.991
G01 X13.227 Y3.843
G01 X13.27 Y3.701
G01 X13.34 Y3.57
G01 X13.434 Y3.455
G01 X13.549 Y3.361
G01 X13.68 Y3.291
G01 X13.822 Y3.248
G01 X13.97 Y3.233
G01 X14.118 Y3.248
G01 X14.26 Y3.291
G01 X14.391 Y3.361
G01 X14.506 Y3.455
G01 X14.6 Y3.57
G01 X14.67 Y3.701
G01 X14.713 Y3.843
G01 X14.728 Y3.991
G01 X14.713 Y4.138
G01 X14.705 Y4.166
G01 X46.668
G01 Y3.585
G01 X47.601 Y2.653
G01 X48.919
G01 X49.852 Y3.585
G01 Y4.904
G01 X49.477 Y5.278
G01 X80.978 Y36.779
G01 X81.217
G01 X81.23 Y36.737
G01 X81.296 Y36.614
G01 X81.385 Y36.506
G01 X81.493 Y36.417
G01 X81.616 Y36.351
G01 X81.75 Y36.31
G01 X81.89 Y36.297
G01 X83.21
G01 X83.35 Y36.31
G01 X83.484 Y36.351
G01 X83.607 Y36.417
G01 X83.715 Y36.506
G01 X83.804 Y36.614
G01 X83.87 Y36.737
G01 X83.911 Y36.871
G01 X83.924 Y37.011
G01 X83.911 Y37.15
G01 X83.87 Y37.284
G01 X83.804 Y37.407
G01 X83.715 Y37.515
G01 X83.607 Y37.604
G01 X83.484 Y37.67
G01 X83.35 Y37.711
G01 X83.21 Y37.725
G01 X81.89
G01 X81.75 Y37.711
G01 X81.616 Y37.67
G01 X81.493 Y37.604
G01 X81.385 Y37.515
G01 X81.296 Y37.407
G01 X81.23 Y37.284
G01 X81.189 Y37.15
G01 X81.178 Y37.039
G01 X80.924
G01 X80.899 Y37.036
G01 X80.875 Y37.029
G01 X80.852 Y37.017
G01 X80.833 Y37.001
G01 X49.294 Y5.462
G00 Z2
G00 X48.181 Y33.268
G00 Z0
G01 F60 Z-0.2
G01 F600 X47.601
G01 X46.668 Y32.336
G01 Y31.017
G01 X47.601 Y30.085
G01 X48.919
G01 X49.852 Y31.017
G01 Y32.336
G01 X48.919 Y33.268
G01 X48.441
G01 Y37.515
G01 X48.661 Y37.536
G01 X49.046 Y37.653
G01 X49.401 Y37.843
G01 X49.712 Y38.098
G01 X49.967 Y38.41
G01 X50.157 Y38.765
G01 X50.274 Y39.15
G01 X50.314 Y39.551
G01 X50.274 Y39.951
G01 X50.157 Y40.336
G01 X49.967 Y40.691
G01 X49.712 Y41.003
G01 X49.401 Y41.258
G01 X49.046 Y41.448
G01 X48.661 Y41.565
G01 X48.26 Y41.604
G01 X47.859 Y41.565
G01 X47.474 Y41.448
G01 X47.119 Y41.258
G01 X46.808 Y41.003
G01 X46.552 Y40.691
G01 X46.363 Y40.336
G01 X46.246 Y39.951
G01 X46.229 Y39.782
G01 X25.463
G01 X25.45 Y39.824
G01 X25.384 Y39.947
G01 X25.295 Y40.055
G01 X25.187 Y40.144
G01 X25.064 Y40.21
G01 X24.93 Y40.251
G01 X24.79 Y40.265
G01 X23.47
G01 X23.33 Y40.251
G01 X23.196 Y40.21
G01 X23.073 Y40.144
G01 X22.965 Y40.055
G01 X22.876 Y39.947
G01 X22.81 Y39.824
G01 X22.769 Y39.69
G01 X22.756 Y39.551
G01 X22.769 Y39.411
G01 X22.81 Y39.277
G01 X22.876 Y39.154
G01 X22.965 Y39.046
G01 X23.073 Y38.957
G01 X23.196 Y38.891
G01 X23.33 Y38.85
G01 X23.47 Y38.837
G01 X24.79
G01 X24.93 Y38.85
G01 X25.064 Y38.891
G01 X25.187 Y38.957
G01 X25.295 Y39.046
G01 X25.384 Y39.154
G01 X25.45 Y39.277
G01 X25.491 Y39.411
G01 X25.502 Y39.522
G01 X46.209
G01 X46.246 Y39.15
G01 X46.363 Y38.765
G01 X46.552 Y38.41
G01 X46.808 Y38.098
G01 X47.119 Y37.843
G01 X47.474 Y37.653
G01 X47.859 Y37.536
G01 X48.181 Y37.505
G01 Y33.268
G00 Z2
G00 X60.451 Y39.782
G00 Z0
G01 F60 Z-0.2
G01 F600 X60.434 Y39.951
G01 X60.317 Y40.336
G01 X60.127 Y40.691
G01 X59.872 Y41.003
G01 X59.561 Y41.258
G01 X59.206 Y41.448
G01 X58.821 Y41.565
G01 X58.42 Y41.604
G01 X58.019 Y41.565
G01 X57.634 Y41.448
G01 X57.279 Y41.258
G01 X56.968 Y41.003
G01 X56.712 Y40.691
G01 X56.523 Y40.336
G01 X56.406 Y39.951
G01 X56.366 Y39.551
G01 X56.406 Y39.15
G01 X56.523 Y38.765
G01 X56.712 Y38.41
G01 X56.968 Y38.098
G01 X57.279 Y37.843
G01 X57.634 Y37.653
G01 X58.019 Y37.536
G01 X58.42 Y37.497
G01 X58.821 Y37.536
G01 X59.206 Y37.653
G01 X59.561 Y37.843
G01 X59.872 Y38.098
G01 X60.127 Y38.41
G01 X60.317 Y38.765
G01 X60.434 Y39.15
G01 X60.471 Y39.522
G01 X81.178
G01 X81.189 Y39.411
G01 X81.23 Y39.277
G01 X81.296 Y39.154
G01 X81.385 Y39.046
G01 X81.493 Y38.957
G01 X81.616 Y38.891
G01 X81.75 Y38.85
G01 X81.89 Y38.837
G01 X83.21
G01 X83.35 Y38.85
G01 X83.484 Y38.891
G01 X83.607 Y38.957
G01 X83.715 Y39.046
G01 X83.804 Y39.154
G01 X83.87 Y39.277
G01 X83.911 Y39.411
G01 X83.924 Y39.551
G01 X83.911 Y39.69
G01 X83.87 Y39.824
G01 X83.804 Y39.947
G01 X83.715 Y40.055
G01 X83.607 Y40.144
G01 X83.484 Y40.21
G01 X83.35 Y40.251
G01 X83.21 Y40.265
G01 X81.89
G01 X81.75 Y40.251
G01 X81.616 Y40.21
G01 X81.493 Y40.144
G01 X81.385 Y40.055
G01 X81.296 Y39.947
G01 X81.23 Y39.824
G01 X81.217 Y39.782
G01 X60.451
G00 Z2
G00 X82.731 Y59.157
G00 Z0
G01 F60 Z-0.2
G01 F600 X83.21
G01 X83.35 Y59.17
G01 X83.484 Y59.211
G01 X83.607 Y59.277
G01 X83.715 Y59.366
G01 X83.804 Y59.474
G01 X83.87 Y59.597
G01 X83.911 Y59.731
G01 X83.924 Y59.871
G01 X83.911 Y60.01
G01 X83.87 Y60.144
G01 X83.804 Y60.267
G01 X83.715 Y60.375
G01 X83.607 Y60.464
G01 X83.484 Y60.53
G01 X83.35 Y60.571
G01 X83.21 Y60.585
G01 X81.89
G01 X81.75 Y60.571
G01 X81.616 Y60.53
G01 X81.493 Y60.464
G01 X81.385 Y60.375
G01 X81.296 Y60.267
G01 X81.23 Y60.144
G01 X81.189 Y60.01
G01 X81.176 Y59.871
G01 X81.189 Y59.731
G01 X81.23 Y59.597
G01 X81.296 Y59.474
G01 X81.385 Y59.366
G01 X81.493 Y59.277
G01 X81.616 Y59.211
G01 X81.75 Y59.17
G01 X81.89 Y59.157
G01 X82.471
G01 Y42.805
G01 X81.89
G01 X81.75 Y42.791
G01 X81.616 Y42.75
G01 X81.493 Y42.684
G01 X81.385 Y42.595
G01 X81.296 Y42.487
G01 X81.23 Y42.364
G01 X81.189 Y42.23
G01 X81.176 Y42.091
G01 X81.189 Y41.951
G01 X81.23 Y41.817
G01 X81.296 Y41.694
G01 X81.385 Y41.586
G01 X81.493 Y41.497
G01 X81.616 Y41.431
G01 X81.75 Y41.39
G01 X81.89 Y41.377
G01 X83.21
G01 X83.35 Y41.39
G01 X83.484 Y41.431
G01 X83.607 Y41.497
G01 X83.715 Y41.586
G01 X83.804 Y41.694
G01 X83.87 Y41.817
G01 X83.911 Y41.951
G01 X83.924 Y42.091
G01 X83.911 Y42.23
G01 X83.87 Y42.364
G01 X83.804 Y42.487
G01 X83.715 Y42.595
G01 X83.607 Y42.684
G01 X83.484 Y42.75
G01 X83.35 Y42.791
G01 X83.21 Y42.805
G01 X82.731
G01 Y59.157
G00 Z2
G00 X14.666 Y62.642
G00 Z0
G01 F60 Z-0.2
G01 F600 Y62.699
G01 X14.258 Y63.106
G01 X13.682
G01 X13.274 Y62.699
G01 Y62.122
G01 X13.682 Y61.715
G01 X14.258
G01 X14.666 Y62.122
G01 Y62.382
G01 X81.178
G01 X81.189 Y62.271
G01 X81.23 Y62.137
G01 X81.296 Y62.014
G01 X81.385 Y61.906
G01 X81.493 Y61.817
G01 X81.616 Y61.751
G01 X81.75 Y61.71
G01 X81.89 Y61.697
G01 X83.21
G01 X83.35 Y61.71
G01 X83.484 Y61.751
G01 X83.607 Y61.817
G01 X83.715 Y61.906
G01 X83.804 Y62.014
G01 X83.87 Y62.137
G01 X83.911 Y62.271
G01 X83.924 Y62.411
G01 X83.911 Y62.55
G01 X83.87 Y62.684
G01 X83.804 Y62.807
G01 X83.715 Y62.915
G01 X83.607 Y63.004
G01 X83.484 Y63.07
G01 X83.35 Y63.111
G01 X83.21 Y63.125
G01 X81.89
G01 X81.75 Y63.111
G01 X81.616 Y63.07
G01 X81.493 Y63.004
G01 X81.385 Y62.915
G01 X81.296 Y62.807
G01 X81.23 Y62.684
G01 X81.217 Y62.642
G01 X14.666
G00 Z2
G00 X14.151 Y54.095
G00 Z0
G01 F60 Z-0.2
G01 F600 X14.258
G01 X14.666 Y54.502
G01 Y55.079
G01 X14.258 Y55.486
G01 X13.682
G01 X13.274 Y55.079
G01 Y54.502
G01 X13.682 Y54.095
G01 X13.891
G01 Y40.265
G01 X13.31
G01 X13.17 Y40.251
G01 X13.036 Y40.21
G01 X12.913 Y40.144
G01 X12.805 Y40.055
G01 X12.716 Y39.947
G01 X12.65 Y39.824
G01 X12.609 Y39.69
G01 X12.596 Y39.551
G01 X12.609 Y39.411
G01 X12.65 Y39.277
G01 X12.716 Y39.154
G01 X12.805 Y39.046
G01 X12.913 Y38.957
G01 X13.036 Y38.891
G01 X13.17 Y38.85
G01 X13.31 Y38.837
G01 X13.891
G01 Y17.44
G01 X13.822 Y17.434
G01 X13.68 Y17.39
G01 X13.549 Y17.32
G01 X13.434 Y17.226
G01 X13.34 Y17.111
G01 X13.27 Y16.98
G01 X13.227 Y16.838
G01 X13.212 Y16.691
G01 X13.227 Y16.543
G01 X13.27 Y16.401
G01 X13.34 Y16.27
G01 X13.434 Y16.155
G01 X13.549 Y16.061
G01 X13.68 Y15.991
G01 X13.822 Y15.948
G01 X13.97 Y15.933
G01 X14.118 Y15.948
G01 X14.26 Y15.991
G01 X14.391 Y16.061
G01 X14.506 Y16.155
G01 X14.6 Y16.27
G01 X14.67 Y16.401
G01 X14.713 Y16.543
G01 X14.728 Y16.691
G01 X14.713 Y16.838
G01 X14.67 Y16.98
G01 X14.6 Y17.111
G01 X14.506 Y17.226
G01 X14.391 Y17.32
G01 X14.26 Y17.39
G01 X14.151 Y17.424
G01 Y38.837
G01 X14.63
G01 X14.77 Y38.85
G01 X14.904 Y38.891
G01 X15.027 Y38.957
G01 X15.135 Y39.046
G01 X15.224 Y39.154
G01 X15.29 Y39.277
G01 X15.331 Y39.411
G01 X15.344 Y39.551
G01 X15.331 Y39.69
G01 X15.29 Y39.824
G01 X15.224 Y39.947
G01 X15.135 Y40.055
G01 X15.027 Y40.144
G01 X14.904 Y40.21
G01 X14.77 Y40.251
G01 X14.63 Y40.265
G01 X14.151
G01 Y54.095
G00 Z2
M09
M05
M02
%
```
### Drilling G code
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 13/05/2024 at 12:57 )
( Workpiece dimensions: 94.92 x 71.237 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #4 "Basic Drill" / Diameter 1 mm )
T4 M06
M03 S12000
M07
G00 X48.26 Y39.551
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y31.677
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X58.42 Y39.551
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X82.55
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y42.091
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y37.011
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y59.871
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y62.411
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X24.13 Y39.551
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X13.97
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y54.791
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y62.411
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y16.691
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X16.51 Y11.611
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X13.97 Y3.991
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X48.26 Y4.245
G00 Z0
G01 F60 Z-1
G00 Z2
M09
M05
M02
%
```
### Cutting G code
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 13/05/2024 at 12:56 )
( Workpiece dimensions: 94.92 x 71.237 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #2 "Basic Cutter" / Diameter 3 mm )
T2 M06
M03 S12000
M07
G00 X4.746 Y-1.318
G00 Z0
G01 F60 Z-2
G01 F300 X89.966
G01 Y67.712
G01 X4.746
G01 Y-1.318
G00 Z2
M09
M05
M02
%
```
# Result

Thus the Gerber File into G-Code using Copper CAM.
