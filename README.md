# Face-Recognition

Overview

The Dataset contains 400 face images of 40 distinct individuals, with ten images per person. These grayscale images, captured between April 1992 and April 1994, exhibit variations in lighting, facial expressions, and facial details. All images have a consistent black background, are sized at 64x64 pixels, and have been scaled to fit within the [0, 1] interval. The dataset encodes the names of the 40 individuals as integers from 0 to 39.

Face Recognition History

The history of facial recognition systems dates back to Bledsoe's semi-automatic study between 1964 and 1966, where facial feature points were manually determined and classified by a computer. However, Kanade's work in 1977 marked the first fully functional facial recognition application, initiating a feature-based approach. Subsequently, two-dimensional (2D) face recognition was extensively studied, with three-dimensional (3D) approaches emerging after the 2000s.

Categorization of Face Recognition Approaches

The development of 3D facial recognition techniques differs significantly from 2D methods. Hence, discussions surrounding face recognition commonly categorize methodologies into 2D and 3D approaches.

For 2D face recognition, methodologies fall into three main categories: analytical (feature-based, local), global (appearance), and hybrid methods. Analytical methods focus on recognizing facial components' properties, while global methods analyze the entire face for recognition. Hybrid approaches combine both local and global methodologies to achieve a more comprehensive understanding of facial features.

Methodology Employed

The face recognition applied in this repository aligns with global face recognition approaches. It's based on Turk and Pentland's work, particularly their Eigenface method developed in the 1990s. Eigenface leverages Principal Component Analysis (PCA) to transform entire face images into vectors and compute eigenfaces from a set of samples. However, it's important to note that PCA may present weaknesses in addressing different facial and illumination variations within the same individual.

The face recognition implemented in this repository relies on the principles established by Turk and Pentland's Eigenface method.

Repository Contents

This repository contains code that applies global-based face recognition methodologies, primarily inspired by the Eigenface approach developed by Turk and Pentland. It utilizes the Olivetti Dataset, allowing users to explore and understand the concepts and practical implementations of facial recognition techniques in Python.

