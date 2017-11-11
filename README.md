
## Cascaded 3D FCN for segmenting Amygdala and its subnuclei [Submitted to ISMRM]

#### Yilin Liu, Brendon Nacewicz, Gregory Kirk, Andrew Alexander, and Nagesh Adluru

### [Results Section]

![Fig1](https://preview.ibb.co/h9BzDG/FCN.png)

Fg.1 The network consists of 10 successive convolutional layers with kernel size 3x3x3 and a fully convolutional layer replaced by a large set of 1x1x1 convolutions. The number of neurons on the classification layer could be either 3 or 11 (denotes the number of classes, including the background), depending on the task.

![Fig2](https://preview.ibb.co/gPvqnb/Our_Net_Result_Amyg.png)

Fg.2 Representative segmentation results for the two whole amygdalae and their subfields.

![Fig3](https://gifyu.com/images/Fg.5.gif)

Fg.3 An animation to show qualitatively how our network output agrees with the ground truth through all the slices in coronal, segittal and axial views. The green outlines show the result of our network and the magenta and orange outlines are the ground truth.

![Fig4](https://preview.ibb.co/gNuSYG/BoxComp.png)

Fg.4 Segmentation results measured using Dice scores for the bilateral whole amygdala (left and right) and their subfields. The bar graph shows our segmentation results compared with other deep learning based and classical approaches.

![Fig5](https://preview.ibb.co/bYdRSb/Dice_Vs_Size.png)

Fg.5 The relationships between several geometric features of the regions and the segmentation performance. Among these factors that could contribute to the final segmentation accuracy we find that the significantly lower volume-surface ratio could account for the lower dice yielded by the residues of the two amygdalae.
