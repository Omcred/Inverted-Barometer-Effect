In addition:
* download GESLA3 observational data and meta files from online and adjust paths accordingly
* download model_timeseries_odiv181.nc and model_timeseries_odiv2.nc for model without IB
* download model_timeseries_psl_odiv181.nc and model_timeseries_psl_odiv181.nc for model with IB

Current Order of Operations:
* download UTIDE
* find a location in model first use example_usage load_N_closest to find closest loaction in observation data
* Preprocess Observational data and export as cdf
* Use comparison_advanced to analyze model vs. obs
