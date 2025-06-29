# Used Car Prices Analysis
This project uses this dataset [https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset]

# Dataset Cleaning
- Replacing or removing null values
- Dropping irrelevant features
- Removing records with null values
- Feature filtering using a variance threshold
- Filtering features on frequency

# Models
- Linear regression model
- Decision Tree

# Model Use 
- model is trained on only select manufactures 
  - Audi
  - Ford
  - Volkswagen
  - Honda
  - Toyota

# Features Needed
    - back_legroom (in inches)
	- bed [0, 'Short', 'Long', 'Regular']
	- bed_height (in inches)
	- bed_length (in inches)
	- body_type ['Sedan', 'SUV / Crossover', 'Pickup Truck', 'Minivan', 'Coupe', 'Hatchback', 'Convertible', 'Wagon', 'Van']
	- cabin [0, 'Crew Cab', 'Extended Cab', 'Large Crew Cab', 'Regular Cab']
	- city 
	- city_fuel_economy - float
	- engine_cylinders ['I4', 'V6', 'V8', 'V8 Flex Fuel Vehicle', 'V6 Flex Fuel Vehicle', 'I4 Hybrid', 'I3', 'I4 Flex Fuel Vehicle', 'H6', 'V12', 'I6', 'I4 Diesel', 'V6 Hybrid', 'V6 Diesel', 'H4', 'V6 Biodiesel', 'I6 Diesel', 'I5']
	- engine_displacement - int
	- engine_type ['I4', 'V6', 'V8', 'V8 Flex Fuel Vehicle', 'V6 Flex Fuel Vehicle', 'I4 Hybrid', 'I3', 'I4 Flex Fuel Vehicle', 'H6', 'V12', 'I6', 'I4 Diesel', 'V6 Hybrid', 'V6 Diesel', 'H4', 'V6 Biodiesel', 'I6 Diesel', 'I5']
	- exterior_color
	- frame_damaged - [False, True]
	- front_legroom (in inches)
	- fuel_tank_volume - float
	- fuel_type - ['Gasoline', 'Flex Fuel Vehicle', 'Hybrid', 'Diesel', 'Biodiesel']
	- has_accidents - [False, True]
	- height (in inches)
	- highway_fuel_economy - float
	- horsepower - float
	- is_cpo - [False, True]
	- is_oemcpo - [False, True]
	- listing_color
	- make_name - ['Chevrolet', 'Jeep', 'Cadillac', 'Chrysler', 'Dodge', 'GMC', 'Kia', 'RAM', 'Hyundai', 'Ford', 'Toyota', 'Lincoln', 'Lexus', 'Buick', 'Volvo', 'Honda', 'Nissan', 'Acura', 'INFINITI', 'Porsche', 'Ferrari', 'Land Rover', 'Jaguar', 'Aston Martin', 'FIAT', 'Maserati', 'Scion']
	- maximum_seating - int
	- mileage - float
	- model_name
	- owner_count - int
	- price - float
	- salvage - [False, True]
	- transmission - ['A', 'M', 'Dual Clutch', 'CVT']
	- wheel_system - ['FWD', 'AWD', '4WD', 'RWD', '4X2']
	- wheelbase - float
	- width width
	- year - int
