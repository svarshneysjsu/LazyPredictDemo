# LazyPredictDemo
The notebook trains and evaluates several regression models on the provided dataset. It outputs a comparison of models based on the following metrics:

  - Adjusted R-Squared
  - R-Squared
  - RMSE (Root Mean Squared Error)
  - Time Taken

Example results:

| Model                          | Adjusted R-Squared | R-Squared | RMSE | Time Taken |
|------------------------------- |------------------- |-----------|------|------------|
| HistGradientBoostingRegressor  | 0.84               | 0.84      | 0.48 | 0.60       |
| XGBRegressor                   | 0.84               | 0.84      | 0.48 | 0.52       |
| LGBMRegressor                  | 0.83               | 0.83      | 0.48 | 0.35       |
| ExtraTreesRegressor            | 0.82               | 0.82      | 0.50 | 4.98       |
| RandomForestRegressor          | 0.82               | 0.82      | 0.50 | 15.40      |

(Note: The table above is a partial representation of the output. Please refer to the notebook for the full results.)
