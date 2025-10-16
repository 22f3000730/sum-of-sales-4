# Sales Summary Application

This single-page web application fetches sales data from a CSV file, calculates the total sales, and displays the result.

## Features

- Fetches and processes CSV data client-side
- Calculates the sum of sales from the "sales" column
- Displays the total sales amount
- Uses Bootstrap 5 for styling
- Dynamically sets the page title

## How It Works

1. On page load, the application fetches a CSV file from a data URI
2. The CSV is parsed to extract sales values
3. Sales values are summed to calculate a total
4. The total is displayed in the `#total-sales` element
5. The page title is updated to include the full encoded title string

## Technical Details

- Built with vanilla JavaScript
- Uses Bootstrap 5 from jsDelivr CDN
- Handles CSV parsing manually without external libraries
- Implements error handling for data fetching and processing

## Data Structure

The CSV data contains:
- Item names
- Sales values

Example:
```
item,sales
Apples,120.50
Bananas,85.75
Oranges,150.25
Grapes,99.00
Mangoes,130.40
```

## Expected Total

The sum of all sales values should be 585.90.