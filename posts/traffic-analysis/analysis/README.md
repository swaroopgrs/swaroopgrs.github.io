# Traffic Analysis

Analysis code and notebooks for the Bay Area traffic accident patterns blog post.

## Setup

```bash
pip install -r requirements.txt
```

## Data

Download data from [TIMS](https://tims.berkeley.edu/):
- Filter: Santa Clara County
- Routes: 101, 237
- Export as CSV

Place data files in `data/` folder (gitignored).

## Run Analysis

```bash
jupyter notebook analysis.ipynb
```

Charts are exported to `../charts/` for use in the blog post.
