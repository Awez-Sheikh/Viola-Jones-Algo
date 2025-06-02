# Viola-Jones-Algo
The Viola-Jones Algorithm is a real-time object detection framework primarily used for face
detection. It was introduced by Paul Viola and Michael Jones in 2001 and is known for its speed
and accuracy. The algorithm consists of four main steps:

1. Haar Feature Selection – Uses rectangular Haar-like features to detect edges and textures
in an image.
2. Integral Image – Converts the image into a summed-area table, allowing rapid feature
computation.
3. Adaboost Training – A machine learning technique that selects the most important
features and forms a strong classifier.
4. Cascade Classifier – Arranges classifiers in a series to quickly eliminate non-face regions
and focus on potential faces.

This approach makes face detection highly efficient, even on low-powered devices.

