<h1 align="center"><b><i>Data Science Bowl 2018</i></b></h1>
<p align=center>
    <a><img alt="YOLOv3 model" src="https://img.shields.io/badge/PyTorch-1.3.0-blue"></a>
    <a><img alt="YOLOv3 model" src="https://img.shields.io/badge/python-3.7-blue.svg"></a>
</p>

<h2>:running: Kaggle competition</h2>

This repository will contain solution for [Data Science Bowl 2018](https://www.kaggle.com/c/data-science-bowl-2018) kaggle competition.
Main purpose is nucleuses identification (<b>segmentation</b>) in varied conditions.

<i>Note: Currently it is WIP (work-in-progress) project.</i>

<h2>:chart_with_upwards_trend: Data analysis</h2>

Firstly, exploratory data analysis was conducted to get to know with data. Results can be found [here](https://github.com/joanna-janos/Data_Science_Bowl_2018/blob/master/data_analysis/EDA.ipynb).

It contains observations for:
- Files (filename encoding, directory structure, duplicated files and data format)
- Train and test data (distribution)
- Dimensions (width and height)
- Channels visualization
- Colour models (division into colour and black&white images based on channels)
- Masks (number of masks and how many pixels are considered as a nucleus)
- Outliers

I have also proved that train and test data is from the same distribution using [adversarial validation](https://github.com/joanna-janos/Data_Science_Bowl_2018/blob/master/data_analysis/adversarial_validation.ipynb).
