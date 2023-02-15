# Polars vs. Pandas DataFrame - The Definitive Answer

Polars should probably replace Pandas in my opinion. At its current stage, it is beating Pandas in performance, in type safety, which also translates to development speed. In addition, since Polars is new, there is room for it to grow better and better. 

Well, I forgot to mention. Another advantage of PySpark is that it has mature ecosystem for ML. Tools like PySparkling, h2o, will allow you to run Auto ML on huge datasets. These tools are very annoying to work with sometimes (big sometimes.). But again, are the only available options out there.

## Small Fix

We should add as_index=False in ```df1_pd.groupby(["dma_code", "dma_name"], as_index=False)```, so that we don't convert the columns to indices. Polars doesn't have any indices. 



Datasets are not uploaded.