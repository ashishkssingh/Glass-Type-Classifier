# Glass Type Classifier  

**Context**  
This is a Glass Identification Data Set from UCI. It contains 10 attributes including id. The response is glass type(discrete 7 values)  

**Content**  
Attribute Information:  

1. Id number: 1 to 214 (removed from CSV file)  
2. RI: refractive index  
3. Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)  
4. Mg: Magnesium  
5. Al: Aluminum  
6. Si: Silicon  
7. K: Potassium  
8. Ca: Calcium  
9. Ba: Barium  
10. Fe: Iron   
11. Type of glass: (class attribute) -- 1 building_windows_float_processed -- 2 building_windows_non_float_processed -- 3 vehicle_windows_float_processed -- 4 vehicle_windows_non_float_processed (none in this database) -- 5 containers -- 6 tableware -- 7 headlamps  


**Acknowledgements**  
Source:<a href = "https://archive.ics.uci.edu/ml/datasets/Glass+Identification"></a>  
Creator: B. German Central Research Establishment Home Office Forensic Science Service Aldermaston, Reading, Berkshire RG7 4PN
Donor: Vina Spiehler, Ph.D., DABFT Diagnostic Products Corporation (213) 776-0180 (ext 3014)      

**Inspiration**  
Data exploration of this dataset reveals two important characteristics :   
1) The variables are highly corelated with each other including the response variables: So which kind of ML algorithm is most suitable for this dataset Random Forest , KNN or other? Also since dataset is too small is there any chance of applying PCA or it should be completely avoided?  

2) Highly Skewed Data: Is scaling sufficient or are there any other techniques which should be applied to normalize data? Like BOX-COX Power transformation?  
