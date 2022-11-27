
- Point of sales data from Dillard's department stores
    - More than 161 Million lines of data from 5 tables
    - Joined tables with each other and external data to conducted feature engineering 
        - Created variables like seasonality, region, average percent discount, purchase / return ratio, brand prestige
    - Using final dataset to conduct clustering analysis
        - Cluster items based on features such as color, region, seasonality (feature selection underway, will probably use PCA)
        - Will try various clustering algorithms (kmeans, DBSCAN. researching more atm)
        - Produce basic recommendation system (e.g. if a customer buys say a red shirt, we might recommend something in the same cluster, like red pants)
    
- Developing use cases for NU's REFIT at NU's CDL
    - Obtained Divvy bikes data from 2013-2019 with time stamps
    - Building a model to predict the number of trips at a certain station in the next hour
    - Simulate the streaming of this data into REFIT as well as AWS
        - the same way data would be ingested in an IoT system
    - Conduct feature engineering and make predictions using our model
    - store the output and model

- FitX
    - Combine fitness and AI
        - I am building a exercise form tracker using Python and its various deep learning libraries, such as openCV, pytorch, OpenPose, and so on
        - The program tracks body keypoints such as joints and limbs in either live video or recorded videos, and checks if the exercise is performed within tolerance.
        - The tolerances are first measured based on an array of training videos, then are continously updated basedon the individual user's body anatomy.
        - I also built a feedback system that gives recommendations on how to improve the exercise based onframe by frame performance.
    - Now, a webapp based version has been created as an MVP and we will be pitching the product to our president / investor.

    - Biggest difficulty
        - Sourcing good data
        - Although there are many videos of people training in the gym, many of them vary in angle, lighting, quality, and direction. 
        - It was very difficult to find videos of people filming straight on with at least decent lighting or video quality.
        - This significantly slowed the tolerance range computation, and my team and I are working on a new algorithm that uses the pattern of the movement of keypoints to determine if an exercise is done correctly. I can't go into detail because we are filing a patent, but it is quite exciting!
