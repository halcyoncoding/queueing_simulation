Capacity planning for call centers can be a huge challenge. 

Here is a jupyter notebook with a custom tool using the discrete event simulation library CIW to ingest historical time data, call types, and users to create a simulation of your call center. It provides graphs of concurrency, wait time distributions, TPx performance, missed calls, and a visualization of all wait times and calls across a given time period.

Using this, you can not only visualize your historical call center performance, but experiment with alternative scenarios. Using historical arrival and service time distributions, you can change your staffing levels and see the expected results.
This can be particularly helpful when trying to build inputs for timeseries forecasting. Because missed calls, or calls which wait a long time effect actual concurrency, they need to be accounted for. You can run a "perfect" scenario with 100, 1000, 10000 agents to see what call patterns would have been like if you had been staffed appropriately through simulation.

Addionally, taking generalized distributions from historical data will let you test staffing forecasts.

At the bottom of the notebook you'll find some examples of how this can be used, but there are many, many more options not illustrated
