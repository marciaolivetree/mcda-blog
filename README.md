# Multi-Criteria Decision Analysis (MCDA) in Python

Welcome to the repository for my blog series on **Multi-Criteria Decision Analysis (MCDA)**.

This repo contains all the code, Jupyter notebooks, and datasets that support my posts about decision analysis methods,
including AHP, PROMETHEE, and more.

## About the Blog Series

In my [MCDA blog series on Medium](https://medium.com/@marciaolivetree), I break down complex decisions using practical, hands-on examples in Python.

Each method is introduced step-by-step and illustrated with relatable scenarios, so you can follow along or adapt the
code to your own projects.

My goal is to make MCDA more accesible, transparent, and applicable to your own decisions.

### Analytic Hierarchy Process (AHP):

- **What it is:** AHP is a classic MCDA method for structuring and solving decision problems that involve multiple, often conflicting
  criteria. It helps translate subjective preferences into a clear ranking of alternatives.
- **What you'll learn:** My post uses a realistic house-hunting example to walk through every AHP step: from defining
  criteria and comparing options, to checking consistency and making the final decision.
- **Reproducible:** All the calculations and tables in the blog post are backed by the Jupyter notebook
  `AHP_house_hunting.ipynb` included in this repository. You can open this notebook to follow along, experiment, or
  verify the results for yourself.

### PROMETHEE I & II:
- **What it is:** PROMETHEE is a family of outranking methods that help you compare options based on preferences, thresholds, and trade-offs, without forcing everything into a single scale. Unlike AHP, it doesn't assume your preferences are always proportional or linear.
- **What you'll learn:** My post uses a realistic job offer comparison to walk through every PROMETHEE I & II step: from defining criteria and preference functions, to setting thresholds and interpreting the final rankings.
- **Reproducible:** All the calculations and tables in the blog post are backed by the Jupyter notebook
  `PROMETHEE_job_offers.ipynb` included in this repository. You can open this notebook to follow along, experiment, or
  verify the results for yourself.

Other posts and code notebooks will be added as the series continues.


## Repository Contents

- Jupyter notebooks for each method covered in the blog series
- Example data files used in the blog examples (to be added)

## How to Use

1. Clone this repository:

```bash
git clone https://github.com/yourusername/mcda-blog.git
cd mcda-blog
```

2. Set up your environment:

It's recommended to use a virtual environment (e.g., `venv` or `conda`).
For example, with `venv`:

```bash
python -m venv .venv
source .venv/bin/activate    # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

3. Run the notebooks:

Open Jupyter Lab or Jupyter Notebook, and start exploring the code examples:

```nginx
jupyter lab
# or
jupyter notebook
```

## Stay Connected

- Read my [blog](https://medium.com/@marciaolivetree) for in-depth explanations and more MCDA methods.
- Contributions, questions, and suggestions are always welcome!
