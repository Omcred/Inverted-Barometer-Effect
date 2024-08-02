In addition:
* download GESLA3 observational data and meta files from online and adjust paths accordingly (you can unzip individual tidegauges if needed)
* download model_timeseries_odiv181.nc and model_timeseries_odiv2.nc for model without IB
* download model_timeseries_psl_odiv181.nc and model_timeseries_psl_odiv181.nc for pressure at sea level output
* these can also be referenced within someone else's workspace when connected to GFDL's system (I currently reference the pressure at sea level output)

Current Order of Operations:
* download UTIDE
* find a location in model first use example_usage load_N_closest to find closest loaction in observation data
* Preprocess Observational data and save as netcdf
* Use comparison_advanced to analyze model vs model w/IB vs obs
