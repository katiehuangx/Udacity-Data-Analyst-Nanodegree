# Project #1: Explore Weather Trends

## Table of Contents

## Summary

In this project, you will 
- analyze local and global temperature data, and 
- compare the temperature trends where you live to overall global temperature trends.

## Instructions

Your goal will be to 
- create a visualization, and 
- prepare a write up describing the similarities and differences between global temperature trends and temperature trends in the closest big city to where you live.

## Questions to Answer

- Are my selected cities (Kuala Lumpur, Bangkok, Kyoto, Melbourne and Seoul) hotter or cooler on average compared to the global average? Has the difference been consistent over time?
- How do the changes in my cities' temperatures over time compare to the changes in the global average?
- What does the overall trend look like? Is the world getting hotter or cooler? Has the trend been consistent over the last decade and few hundred years?

## Accessing Data with SQL

````sql
-- Extract city level's temperature data
SELECT *
FROM city_data
WHERE city IN ('Kuala Lumpur','Bangkok','Kyoto', 'Melbourne','Seoul');
````

````sql
-- Extract global temperature data
SELECT *
FROM global_data;
````
