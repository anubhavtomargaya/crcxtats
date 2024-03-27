# crcxtats
cricxstats: cricket-stats | Exploration to build way to analyse real world cricket statistics. Later use the data for predictive analytics.
Steps.
1. explore existing ways to get data for cricket analysts (library, API, Applications etc)
2. make a list of all the types of charts and data showed in a cricket match
3. build a schema to store the `olap` data required to aggregate the above charts
4. build a schema to store the `oltp` data required to aggregate the above denormalised tables.
5. finalise a way to get the data from real world -> after # 1 is done either we use the existing way or build a way. To build will come later.
  ```
  A. Using existing ways
  B. Building own data ingestion API +  Transformation pipelines 
  Validation and Loading Layer + Access Layer will be same for both. Depending on the schema of # 3 (or #4 if storing directly for charts)
  ```
