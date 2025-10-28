# Data
-   **[Dataset]**: Description of the dataset 
This dataset contains 10,000 records of industrial equipment data.
Each row corresponds to a single machine and includes measurements such as temperature, torque, rotational speed, and tool wear, along with labels indicating whether a failure occurred.
# Codebook for [chosen] Dataset

## Variable Names and Descriptions:
-   
Variable	                    Descriptions
UDI	                            Unique identifier for each record
Product ID	                    Specific machine model
Type	                        Load type (L = Light, M = Medium, H = Heavy)
Air temperature                 [K]	Ambient air temperature near the equipment
Process temperature             [K]	Process fluid temperature
Rotational speed                [rpm]	Shaft rotation speed
Torque                          [Nm]	Rotational force applied
Tool wear                       [min]	Usage time of the tool in minutes
Machine failure	Target variable (1 = failure, 0 = normal)
TWF, HDF, PWF, OSF, RNF	        Specific failure categories: Tool Wear, Heat Dissipation, Power, Overstrain, and Random Failures

## Data Types:

-   **Column**: data type
UDI	                    int64
Product ID	            object (string)
Type	                object (string)
Air temperature 	    float64
Process temperature 	float64
Rotational speed        int64
Torque      	        float64
Tool wear   	        int64
Machine failure	        int64
TWF	                    int64
HDF	                    int64
PWF	                    int64
OSF	                    int64
RNF	                    int64