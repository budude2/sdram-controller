The SDRAM test structure ([taken from Micron](https://www.micron.com/products/dram/sdram/part-catalog/mt48lc16m16a2b4-6a)) has been modified in `sdr_parameters.vh`. Intel's simulation tool, ModelSim/Questa, did not like certain defines being on the same line as other preprocessor directives, so they've been moved.