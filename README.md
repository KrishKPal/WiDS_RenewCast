# Week 1: Foundations for RenewCast

Welcome to RenewCast. Over the next five weeks you will build a system that forecasts solar power hour by hour, compares different models, checks how they hold up as conditions change, and presents everything in a dashboard.

This week is about getting the foundations in place. You will not touch the real project data yet. Instead, you will work through a small solar-power dataset that behaves like the real one, so that when we start Week 2 the tools already feel familiar.

Plan for about 6 to 8 hours.

## What you should be able to do by the end of the week

- Write and read basic Python without looking up every line.
- Use NumPy arrays for vectorised maths, boolean masks and simple statistics.
- Load, inspect, filter and group a table with Pandas, and add new columns to it.
- Explain what a feature, a target, a training set and a test set are.
- Split time-ordered data correctly and say why a random split is wrong for forecasting.
- Fit a scikit-learn regression model, make predictions, and judge them with MAE and RMSE.
- Explain why you always compare a model against a simple baseline.

## Setup

You can work on your laptop or on Google Colab. Colab needs no installation and is the easier choice if you are unsure.

**On your laptop:** install Python 3.10 or newer, then run

```
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook
```

**On Colab:** upload `Week1_Foundations_Student.ipynb` to Google Colab. Everything we need is already installed there.

Open `Week1_Foundations_Student.ipynb`. This is the notebook you will complete.

## Suggested schedule

| Part | Time | What to do |
|---|---|---|
| Setup | 30 min | Get the notebook running. Run the data cell and look at the table. |
| Python refresher | as needed | Skip it if you are comfortable. Otherwise do the Kaggle Python course below. |
| NumPy | about 2 hours | Read the NumPy quickstart, then do Exercises 1 to 3. |
| Pandas | about 2 hours | Read "10 minutes to pandas", then do Exercises 4 to 7. |
| First ML model | about 2 hours | Read the scikit-learn getting started page, then do Exercises 8 to 11. |
| Wrap-up | 30 min | Restart and run the whole notebook, fill in your written answers, write your note. |

Do the reading first, then the exercises. Trying to do the exercises while searching for syntax is much slower than reading for 30 minutes beforehand.

## Resources

- Python basics: [Kaggle Learn, Python](https://www.kaggle.com/learn/python)
- NumPy: [NumPy quickstart](https://numpy.org/doc/stable/user/quickstart.html)
- Pandas: [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html) and [Kaggle Learn, Pandas](https://www.kaggle.com/learn/pandas)
- Machine learning basics: [Kaggle Learn, Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning)
- scikit-learn: [Getting started](https://scikit-learn.org/stable/getting_started.html)
- Error metrics: [Regression metrics in scikit-learn](https://scikit-learn.org/stable/modules/model_evaluation.html#regression-metrics)

You do not need to finish all of these. Read the ones that cover what you do not already know.

## What to submit

By the end of the week, send me:

1. Your completed notebook, with every check passing and the notebook running cleanly from top to bottom (Kernel, then Restart and Run All).
2. Your written answers to Exercises 7 and 11.
3. One short note at the end of the notebook: the single thing that confused you most this week.

Please do not copy solutions from anywhere. A wrong answer you understand is worth more to us than a right answer you cannot explain. If you are stuck for more than 20 minutes, write down what you tried and bring it to the group.

## Looking ahead

In Week 2 we move to the real weather and solar dataset. We will explore its structure, build time features such as lags and seasonality, and set up a persistence baseline that every later model has to beat.
