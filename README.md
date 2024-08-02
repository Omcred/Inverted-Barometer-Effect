In addition:
* download GESLA3 observational data and meta files from online and adjust paths accordingly (you can unzip individual tidegauges if needed)
* download model_timeseries_odiv181.nc and model_timeseries_odiv2.nc for model without IB
* download model_timeseries_psl_odiv181.nc and model_timeseries_psl_odiv181.nc for pressure at sea level output
* these can also be referenced within someone else's workspace when connected to GFDL's system ( for example "/work4/k2t/sealevel/data/model_timeseries_psl_odiv2.nc")
* this can be download usoing cp[path to file in system][path to save it as] (for example cp/work4/k2t/sealevel/data/model_timeseries_psl_odiv2.nc/vftmp/Olivia.Mcredmond/data/model_timeseries_psl_odiv2.nc)

Current Order of Operations:
* download UTIDE
* find a location in model
* use example_usage's load_N_closest method to find closest loaction in observational data
* Preprocess Observational data and save as netcdf
* Use comparison_advanced to analyze model vs model w/IB vs obs
