# DT-MARS-CycleGAN
The repository is for the paper: DT/MARS-CycleGAN: Improved Object Detection for MARS Phenotyping Robot, including the code and dataset for reproducing. 

The paper is published on [Arxiv](https://arxiv.org/abs/2310.12787) , and under review on Journal of field robotics.

Abstract— Robotic crop phenotyping has emerged as a key
technology to assess crops’ phenotypic traits at scale, which
is essential for developing new crop varieties with the aim
of increasing productivity and dealing with environmental
challenges such as climate change. However, developing and
deploying crop phenotyping robots face many challenges such
as complex and variable crop shapes that complicate robotic
object detection, dynamic and unstructured environments that
confound robotic control, and real-time computing and manag-
ing big data that challenge robotic hardware/software. This
work specifically tackles the first challenge by proposing a
novel Digital Twin(DT)/MARS-CycleGAN model for image
augmentation to improve our Modular Agricultural Robotic
System (MARS)’s crop object detection from complex and
variable backgrounds. Our core idea is that in addition to the
cycle consistency losses in the CycleGAN model, we designed
and enforced a new DT/MARS loss in the deep learning model
to penalize the inconsistency between real crop images captured
by MARS and synthesized images sensed by DT MARS.
Therefore, the generated synthesized crop images closely mimic
real images in terms of realism, and they are employed to fine-
tune object detectors such as YOLOv8. Extensive experiments
demonstrated that our new DT/MARS-CycleGAN framework
significantly boosts crop object and row detection performance
for MARS, contributing to the field of robotic crop phenotyping
