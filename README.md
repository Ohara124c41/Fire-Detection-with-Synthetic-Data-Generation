# Fire Detection with Synthetic Data Generation

Synthetic data pipeline and baseline models for industrial fire detection in indoor warehouse scenes.  
Unity is used to render dynamic fire and non-fire images under varied camera poses and lighting.  
Baselines include a TinyVGG classifier and a YOLOv5 detector trained on synthetic data only.  
Initial results (Dec 2023): TinyVGG 96% test accuracy on synthetic data; YOLOv5 mAP@0.5 = 0.88 on synthetic validation; live demo correctly detected 10/10 real images.

**Repository creation date:** Dec 18, 2023  
**Poster presentation:** Jan 9, 2024

# Citing 
If this repository is useful, please cite the Dec 2023 preliminary report:

@misc{ohara2023_synth_fire,
  title  = {Synthetic Data Generation for Industrial Fire Detection: A Unity-Based Pipeline (Preliminary Report, Dec 2023)},
  author = {Christopher A. O'Hara},
  howpublished = {GitHub repository},
  year   = {2023},
  url    = {https://github.com/Ohara124c41/Fire-Detection-with-Synthetic-Data-Generation}
}
