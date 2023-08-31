# mouse-pose-analysis-dataset

**Mouse Pose Analysis Dataset** includes 80 CT scans, 5460 annotated video
frames of mouse in their home cage, and 108 annotated multiple-view frames.

## Downloads

Follow the directions in the
[dataset website](http://google.github.io/mouse-pose-analysis-dataset) to access
the data.

## Code sample

[A Colab Notebook](./usage_example.ipynb) shows how to read and visualize the
data.

## Citation

```
@article{mouse_pose_analysis_2023,
        title = {3D mouse pose from single-view video and a new dataset},
        volume = {13},
        issn = {2045-2322},
        url = {https://www.nature.com/articles/s41598-023-40738-w},
        doi = {10.1038/s41598-023-40738-w},
        abstract = {We present a method to infer the 3D pose of mice, including the limbs and feet, from monocular videos. Many human clinical conditions and their corresponding animal models result in abnormal motion, and accurately measuring 3D motion at scale offers insights into health. The 3D poses improve classification of health-related attributes over 2D representations. The inferred poses are accurate enough to estimate stride length even when the feet are mostly occluded. This method could be applied as part of a continuous monitoring system to non-invasively measure animal health, as demonstrated by its use in successfully classifying animals based on age and genotype. We introduce the Mouse Pose Analysis Dataset, the first large scale video dataset of lab mice in their home cage with ground truth keypoint and behavior labels. The dataset also contains high resolution mouse {CT} scans, which we use to build the shape models for 3D pose reconstruction.},
        number = {1},
        journal = {Scientific Reports},
        author = {Hu, Bo and Seybold, Bryan and Yang, Shan and Sud, Avneesh and Liu, Yi and Barron, Karla and Cha, Paulyn and Cosino, Marcelo and Karlsson, Ellie and Kite, Janessa and Kolumam, Ganesh and Preciado, Joseph and Zavala-Solorio, José and Zhang, Chunlian and Zhang, Xiaomeng and Voorbach, Martin and Tovcimak, Ann E. and Ruby, J. Graham and Ross, David A.},
}
```
