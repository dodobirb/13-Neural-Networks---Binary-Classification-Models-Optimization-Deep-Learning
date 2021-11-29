# Module_13_Challenge
FinTech Boot Camp Module 13: Neural Networks - Binary Classification Models

---

These models were created to predict whether funding applicants will be successful if funded by Alphabet Soup VC. As a large number of applications are received daily, there was a need for a model to filter the list of applicants based on previous recipients' success (or lack thereof).

The features in the provided dataset are used to create a binary classifier model that will predict whether an applicant will become a successful business.

---

## Technologies

This application was written in Python 3.9.4 . 

Google Colab may serve as the most ideal IDE with which to run the models in this program, given the implications of boosted performance and decreased training time of neural network models. However, as these models are relatively simple, this program can still be run in your environment of choice.

---

## Installation Guide

Ensure through your local terminal that your development environment supports the following imports and dependencies:

```
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler, OneHotEncoder
```

If it does not, reference your terminal installation guide to download the missing software.

---

## Contributors

Brought to you by risk management associate Erin Kenny at Alphabet Soup VC.

ekenny3@uncc.edu

www.linkedin.com/in/e-kenny

---

## License

MIT

License file included in repository.

