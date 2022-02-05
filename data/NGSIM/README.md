### Generate preprocessed NGSIM mat files here.  

##### MATLAB function preprocess(path, historical_length, future_length, number_of_agents, max_vertical_distance, extra_feature_index)  
##### Params:  
    - path: path to locate your dataset raw files (recommend: 'raw_data')  
    - historical_length: length of observed track (in this paper: 30)  
    - future_length: length of predicted track (in this paper: 50)  
    - number_of_agents: maximum number of vehicles in each scene (recommend: 20)  
    - max_vertical_distance: maximum vertical distance (feet) between ego and surrounding vehicles (in this paper: 90)  
    - extra_feature_index: extra feature row index(es) in raw files (in this paper: [11, 12, 13])  
This function do NOT have any returned values  

### You may obtain the preprocessed dataset claimed in our paper via executing the following line in MATLAB console:  
    preprocess('raw_data', 30, 50, 20, 90, [11, 12, 13])

