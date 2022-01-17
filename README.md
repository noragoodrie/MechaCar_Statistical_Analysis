# MechaCar_Statistical_Analysis

**DELIVERABLE 1: LINEAR REGRESSION TO PREDICT MPG**

<img width="576" alt="Screen Shot 2022-01-16 at 11 56 15 AM" src="https://user-images.githubusercontent.com/91299616/149684889-46a40434-f4ee-48f7-8419-6652a67e97bc.png">


- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

According to the above summary output we recieved we can see that the vehicle length and the vehicle ground clearance are most likely to give us non-random amounts of variance. The vehicle length and clearances will take a toll on the MPG of the vehicle.

- Is the slope of the linear model considered to be zero? Why or why not?

The linear model is NOT considered zero! Our P-VALURE IS 5.35e-11 which we can see is smaller than the significance of 0.05%.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

We can somewhat say that yess, this linear regression model deos predict mpg for the MechaCar prototyles effectively because when we look at our R squared value it shows us to be .7149 which is considered 71%. That 71% is used for the mpg predictions.


**DELIVERABLE 2: SUMMARY STATISTICS ON SUSPENSION COILS**

TOTAL SUMMARY DF


<img width="585" alt="Screen Shot 2022-01-16 at 12 11 39 PM" src="https://user-images.githubusercontent.com/91299616/149685407-d1cd1ca4-5cd5-48a8-92ac-90c476a46994.png">


LOT SUMMARY DF

<img width="578" alt="Screen Shot 2022-01-16 at 12 16 47 PM" src="https://user-images.githubusercontent.com/91299616/149685428-b8f4566f-8690-4cd2-96b4-787f20437d6c.png">


- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The requirement at large is 100 pounds per square inch. When we look at our Total Summary DF we can see that the variances PSI is 62.29 which is below the 100 pounds per square inch by 37.71.

When we look at each lot individually we can see that both lot 1 and 2 are within the requirements, but lot 3 comes out to be 170.28 which is over the requirement by aproximentaly 70 pounds.

**DELIVERABLE 3: T-TESTS ON SUSPENSION COILS

SUSPENSION COIL PSI T-TEST RESULTS

<img width="568" alt="Screen Shot 2022-01-16 at 5 05 06 PM" src="https://user-images.githubusercontent.com/91299616/149685860-59bfe326-9774-4d32-848a-4cf1331367b2.png">

INDIVIDUAL LOTS T-TEST RESULTS

<img width="563" alt="Screen Shot 2022-01-16 at 5 04 50 PM" src="https://user-images.githubusercontent.com/91299616/149685960-0ab26605-4932-4d0f-80ba-3183a6e78636.png">



