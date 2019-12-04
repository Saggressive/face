# face
1.运行get_faces_from_camera.py,录入人脸，按n键创建存储人脸的文件夹，创建文件夹后，控制台输入姓名
目前只支持英文名，s键，摄像头会录入人脸，q键退出

2.运行features_extraction_to_cvs.py,将人脸库的照片作为神经网络的输入，提取28维人脸特征并存储cvs文件里

3.运行face_reco_from_camera.py,识别人脸。

4.name.pkl存储的是人脸的姓名，每个名字对应data/data_face_from_camera的每个文件夹名，.pkl存储的是一个字典，
可以通过修改这个字典修改姓名
