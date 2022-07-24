# Deep_Learning_Colon_Cancer_Indentification
Identify different types of cell nuclei in a colon cancer sample

**Overall Goal
Colon cancer is the 3rd most common cancer in the world.

The normal colon has projections known as villi which absorb food and appear as circles of cells on a microscope image of the tissue (since the villi are cut through):
Histopathology image of early colon cancer.

The cell nuclei of these images can be segmented and coloured according to the different cell types:
Image segmented according to cell type.
(Orange cells are normal, red cells are cancer, green cells are immune cells invading to help, and blue cells are connective tissue.)

The following image shows a worse grade of colon cancer where you can see that the circles of normal cells have disintegrated and the nuclei have become larger and less well formed (due to DNA damage):
More advanced colon cancer with cell types indicated.

Digital pathology aims to apply machine learning to digital pathology images like these to determine if the tissue is normal or cancerous. One approach is to segment out the nuclei of cells from these images and classify them into different cell types including malignant cell nuclei (i.e. cancerous cells).

Your overall goal for this data science task is to train a deep neural network which can take a 32x32 image with a cell nuclei and classify it into one of the following types which are shown in the figures above:

Normal epithelial cells (shown orange).
Cancer epithelial cells (shown in red).
Immune leukocyte cells (shown in green).
Connective fibroblast cells (shown in blue).
