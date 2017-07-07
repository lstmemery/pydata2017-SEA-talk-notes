# Pandas Transformers (Very useful)

It sucks to write all the transformers out

```
pipeline = Pipeline([('imputer', Imputer())])
```

FunctionTransformer: turns any function into a transformer
Should be stateless

Or write custom transformer

```
class CustomTransformer(TransformerMixin)
```

Pandas DataFrames (many dtypes) vs. Scikit-learn Models (all numeric features)

Write custom Transformers that returns DataFrames

This is wonderful