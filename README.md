# Food.com Recipe Recommender

Recommends recipes using:
- Content-based retrieval (TF-IDF over ingredients)
- (Planned) Collaborative filtering for implicit feedback

## Repo structure
- src/: library code
- experiments/: notebooks / exploration only
- data/raw/: raw datasets (ignored by git)
- data/processed/: cleaned datasets (ignored by git)

## Data

This project pulls the dataset directly from Kaggle via `kagglehub`:

- Dataset: `shuyangli94/food-com-recipes-and-user-interactions`

### Kaggle authentication (required)

`kagglehub` can authenticate using environment variables:

```bash
export KAGGLE_USERNAME="YOUR_KAGGLE_USERNAME"
export KAGGLE_KEY="YOUR_KAGGLE_API_KEY"


