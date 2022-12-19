# Detecting Covariate Shift

This blog post shows why univiariate drift detection methods are not enough and how the PCA reconstruction error-based approach allows us to detect multivariate shift. It also discusses the assumptions behind this appraoch and its limitations.

## Datasets

The blog posts uses the following two datasets:

* Yandex’s weather dataset - [LINK](https://research.yandex.com/shifts/weather)
* Datasaurus dataset - [LINK](https://cran.r-project.org/web/packages/datasauRus/vignettes/Datasaurus.html)

## Python packages

The code snippets used in the blog post use the following packages:

* `nannyml == 0.8.1`
* `pandas == 1.3.5`
