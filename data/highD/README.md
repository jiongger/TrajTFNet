### Generate preprocessed highD mat files here.

##### MATLAB function preprocess(path, historical_length, future_length, number_of_agents, max_vertical_distance, extra_feature_index)
##### Params:
    - path: path to locate your dataset raw files (recommend: 'raw_data')
    - historical_length: length of observed track (in this paper: 75)
    - future_length: length of predicted track (in this paper: 125)
    - number_of_agents: maximum number of vehicles in each scene (recommend: 20)
    - max_vertical_distance: maximum vertical distance (feet) between ego and surrounding vehicles (in this paper: 90)
    - extra_feature_index: extra feature row index(es) in raw files (in this paper: [7, 8, 9, 10, 26])
This function do NOT have any returned values

### You may obtain the preprocessed dataset claimed in our paper via executing the following line in MATLAB console:
    preprocess('raw_data', 75, 125, 20, 90, [7, 8, 9, 10, 26])

 Make sure you have set the -v7.3 flag to store variables > 2GB
