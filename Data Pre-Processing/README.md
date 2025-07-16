# Machine Learning Data Pre-Processing Tools

This repository provides a set of tools for preparing datasets for machine learning pipelines. It focuses on modular, repeatable preprocessing techniques suitable for supervised learning tasks.

The main goal of this project is to offer reusable, well-commented preprocessing blocks for:
- Cleaning
- Encoding
- Normalization
- Splitting

All workflows are built using Python and popular libraries in the ML ecosystem.

## Techniques Used

The notebook implements and demonstrates the following core techniques:

- **Label Encoding** and **One-Hot Encoding** with [`sklearn.preprocessing`](https://scikit-learn.org/stable/modules/preprocessing.html)
- **Train-Test Split** using [`train_test_split`](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)
- **Feature Scaling** with [`StandardScaler`](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
- **Handling missing values** using pandas’ [`fillna`](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.fillna.html)
- **Column-wise operations** with pandas `apply` functions
- **Chained pipeline logic** for step-wise transformation

## Technologies and Libraries

Professional developers will recognize familiar tools and workflows, including:

- [Pandas](https://pandas.pydata.org) — used for structured data manipulation
- [scikit-learn](https://scikit-learn.org) — for transformations and splitting
- [NumPy](https://numpy.org) — for numerical operations

These tools are well integrated and form a solid base for production-grade preprocessing logic.

No third-party or obscure libraries are used. No web fonts or UI-specific tools are required for this release.

## Project Structure

```
.
├── README.md
├── data_preprocessing_tools.ipynb
└── Data Pre-Processing/
```

- `data_preprocessing_tools.ipynb`: Main notebook demonstrating all preprocessing steps.
- `Data Pre-Processing/`: Placeholder for future script/module expansion or dataset samples.

## Next Steps

Future versions may include:
- Wrapping functionality into a pipeline class
- Handling categorical interactions
- Feature importance filtering pre-modeling
