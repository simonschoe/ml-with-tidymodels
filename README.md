# Modeling Workflows with Tidymodels
*This lecture is part of the "Machine Learning in R" graduate course held at University of Münster, School of Business and Economics (winter term 2021/22).* :mortar_board:

**Slides:** https://simonschoe.github.io/ml-with-tidymodels/

<a href="https://www.wiwi.uni-muenster.de/"><img src="https://www.wiwi.uni-muenster.de/fakultaet/sites/all/themes/wwucd/assets/images/logos/secondary_wiwi_aacsb_german.jpg" alt="fb4-logo" height="45"></a> <a href="https://www.wiwi.uni-muenster.de/ctrl/aktuelles"><img src="https://www.wiwi.uni-muenster.de/ctrl/sites/all/themes/wwucd/assets/images/logos/berenslogo5.jpg" alt="ftb-logo" height="45"></a> <a href="https://www.wiwi.uni-muenster.de/iff2/de/news"><img src="https://www.wiwi.uni-muenster.de/iff2/sites/all/themes/wwucd/assets/images/logos/logo_iff2_en2.jpg" alt="ipb-logo" height="45"></a>


## Contents

This lecture gives a deep insight into `tidymodels`, a unified framework towards modeling and machine learning in `R` using tidy data principles. It introduces and motivates tools that facilitate every step of the machine learning workflow, from resampling, over preprocessing and model building, to model tuning and performance evaluation.

More specifically, after this lecture you will
- be familiar with the core packages of the `tidymodels` ecosystem and hopefully realize the value of a unified modeling framework,
- know how to design a full-fledged machine learning pipeline for a particular prediction task,
- broaden your technical skills by learning about declarative programming, hyperparameter scales and parallel processing, and
- most importantly, be capable of conducting your own machine learning projects in `R`.


## Agenda

**1 Learning Objectives**

**2 Introduction to `tidymodels`**

**3 Himalayan Climbing Expeditions Data**

**4 The Core `tidymodels` Packages**

>4.1 `rsample`: General Resampling Infrastructure  
4.2 `recipes`: Preprocessing Tools to Create Design Matrices  
4.3 `parsnip`: A Common API to Modeling and Analysis Functions  
4.4 `workflows`: Modeling Workflows  
4.5 `dials`: Tools for Creating Tuning Parameter Values  
4.6 `tune`: Tidy Tuning Tools  
4.7 `broom`: Convert Statistical Objects into Tidy Tibbles  
4.8 `yardstick`: Tidy Characterizations of Model Performance

**5 Additions to the `tidymodels` Ecosystem**
