# Airline Operations Analysis

This project analyzes two scenarios: Part A examines a large international airline's operations to calculate total costs and determine which aircraft type has the lowest cost per seat per kilometer flown. Part B focuses on a startup airline to find the best aircraft types for their planned city pairs, considering range, passenger demand, and costs.

## Part A: Airline Operations

1. **Calculate Total Cost by Aircraft Type**:
   - Using the "Operations" tab, extract the total hours flown for each aircraft type.
   - Using the "AC Characteristics" tab, obtain the cost per hour for each aircraft type.
   - Calculate the total cost for each aircraft type by multiplying the hours flown by the cost per hour.

2. **Determine Aircraft Type with Lowest Cost Per Seat Per Kilometer Flown**:
   - From the "Operations" tab, calculate the total kilometers flown for each aircraft type.
   - From the "AC Characteristics" tab, find the seating capacity for each aircraft type.
   - Calculate the cost per seat per kilometer by dividing the total cost by the product of the total kilometers flown and the seating capacity.
   - Identify the aircraft type with the lowest cost per seat per kilometer flown.

## Part B: Startup Airline

1. **Identify Best Aircraft Types for City Pairs**:
   - Using the "City Pairs" tab, determine the city pairs the airline plans to operate.
   - For each city pair, consider the following factors:
     - **Range**: The aircraft's range should be sufficient to cover the distance between the city pairs.
     - **Passenger Demand**: The aircraft's seating capacity should meet or exceed the daily demand.
     - **Cost**: Use the "AC Characteristics" tab to find the cost per hour and aim for the lowest possible cost.
   - Determine the best-suited aircraft type for each city pair based on these factors.
   - A single city pair may require multiple trips to meet daily demand, so consider the total number of trips an aircraft can make in a day.

## Implementation Considerations
- **Data Extraction and Calculation**: Consider using Python, R, or SQL to extract and manipulate data from the tabs and perform necessary calculations.
- **Optimization and Analysis**: For Part B, optimization involves balancing range, passenger demand, and cost. This might require more complex computations or iteration over possible aircraft types to find the best match.
- **Presentation of Results**: Ensure that the results are presented clearly, indicating the aircraft type with the lowest cost per seat per kilometer (Part A) and the most suitable aircraft for each city pair (Part B).

This README.md provides a concise guide to the project tasks, outlining the steps needed to calculate total costs, identify the best aircraft types, and ultimately recommend operational decisions for both airlines.
