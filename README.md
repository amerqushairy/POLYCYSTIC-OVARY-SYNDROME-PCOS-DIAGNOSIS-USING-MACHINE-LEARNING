# POLYCYSTIC-OVARY-SYNDROME-PCOS-DIAGNOSIS-USING-MACHINE-LEARNING
**<span style="color:teal;"> Polycystic Ovary Syndrome (PCOS) </span>** is a hormonal condition that affects many women of reproductive age. Women with PCOS may have irregular or prolonged menstrual cycles, as well as high levels of the male hormone androgen. The ovaries may produce a large number of tiny collections of fluid (follicles) and fail to release eggs on a regular basis. (Source: https://www.mayoclinic.org/diseases-conditions/pcos/symptoms-causes/syc-20353439#:~:text=Polycystic%20ovary%20syndrome%20(PCOS)%20is,fail%20to%20regularly%20release%20eggs)

The high prevalence of PCOS (12.6%) among Malaysian women could indicate the emergence of a public health problem in the country.

The following are some of the most common PCOS symptoms:

1) Periods that are irregular or nonexistent.

2) Having trouble getting pregnant (because of irregular ovulation or failure to ovulate)

3) Hair growth that is excessive which  typically on the face, chest, back, or buttocks.

4) gaining weight

5) Hair thinning and hair loss on the head

6) Acne or greasy skin

In this project, we have proposed a Random Forest Classifier as the best model for PCOS Diagnosis.

* **Importing Necessary Libraries**
* **Read In and Explore the Data**
* **Data Cleaning**
* **EDA and Data Visualization**
* **Best Model: Random Forest Classifier**
* **Discussion**
* **Impact**
* **Conclusion**

# This Python 3 environment comes with many helpful analytics libraries installed
# It is defined by the kaggle/python Docker image: https://github.com/kaggle/docker-python
# For example, here's several helpful packages to load

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

# Input data files are available in the read-only "../input/" directory
# For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))

# You can write up to 20GB to the current directory (/kaggle/working/) that gets preserved as output when you create a version using "Save & Run All" 
# You can also write temporary files to /kaggle/temp/, but they won't be saved outside of the current session
