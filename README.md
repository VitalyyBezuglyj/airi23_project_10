# 10 - Обучаемые расширенные векторные представления трехмерного пространства 
Repo for the AIRI Summer School research project on "Application of differentiable object representation of 3D scene recognition"


## Abstract

В рамках данного проекта был проведен обзор подходов применения обчуаемых векторных представлений трёхмерного пространства, выделена одна из наиболее перспективных задача в данной области - "Сегментация трёхмерной сцены по произвольному текстовому запросу" и рассмотрены и экспериментально изучены две актуальные работы в этой области - [OpenScene, CVPR 2023](https://pengsongyou.github.io/openscene) и VLMap (добавить ссылку, год).

## Project Structure

Исследование проводилось параллельно по обеим работам, в различных репозиториях:
1. OpenScene - [VitalyyBezuglyj/openscene_experiments](https://github.com/VitalyyBezuglyj/openscene_experiments)
2. VLMap - [github]()

## Data

 Для экспериментов использовались данные собранные на робототехнической платформе Husky внутри учебного корпуса университета, оснащенной 16-лучевым лидаром VLP-16, а также стереокамерой ZED (1280x720).

 ![husky](/img/Figure_Robot.png)

 Для экспериментов использовались такие данные как:
 - RGB-D Изображения
 - 3D облака точек (LiDAR)
 - Внутренние параметры камеры (intrinsics)
 - 6DoF позы камеры, полученные при помощи алгоритма [Cartographer](https://github.com/cartographer-project/)


## Experiments

[to be added]

## Results

[to be added]