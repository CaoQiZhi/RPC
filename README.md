# Be An Excellent Student: Review, Preview and Correction
We propose a more reasonable and efficient knowledge distillation scheme to acquire informative and complementary knowledge. Just like students, while achieving
good performance, continuous improvement requires doing well in knowledge review, preview and correction.
# Overview
![image](https://github.com/CaoQiZhi/RPC/assets/125184046/4362f326-7904-40e6-9a8f-d15bdf59efd1)
# Visualization
Visualization comparisons of models’feature activation map in the first row. The ”KD” denotes the correlation matrices of teacher and student predictions with the vanilla knowledge distillation, the ”RPC” denotes that with our method and the ”RC” denotes the correlation matrices between teacher prediction and corrected student prediction in the second row.
![image](https://github.com/CaoQiZhi/RPC/assets/125184046/19889965-88b7-4d4d-a33e-ddce44f1b2ab)
# Comparision
Our method  reverses the situation in previous methods where the performance of the student deteriorated due to the significant gap between the teacher(resnet110) and the student(resnet20).
![Fig4](https://github.com/CaoQiZhi/RPC/assets/125184046/263a39a9-5640-4d54-90cb-205d1b8e9308)
