# LAB09
Lab 09: LINQ in Manhattan - Explanation

The "LINQ in Manhattan" project is a C# console application that reads data from an external JSON file containing location information for properties in Manhattan. The goal is to use LINQ queries and Lambda expressions to filter and manipulate the data and answer specific questions about the neighborhoods in Manhattan.

Program Specifications:

Data.json File: The project includes a data.json file in the solution root folder. This JSON file contains a dataset with location information for properties in Manhattan.

Reading and Filtering Data: The program reads the data from the data.json file and applies LINQ queries and Lambda expressions to filter and manipulate the data.



Output All Neighborhoods: The program outputs all the neighborhoods in the data list. The total count of neighborhoods is 147.

Filter Out Neighborhoods Without Names: The program filters out all the neighborhoods that do not have any names and outputs the filtered neighborhoods. The total count of neighborhoods after this filter is 143.

Remove Duplicates: The program removes duplicate neighborhoods from the data and outputs the distinct neighborhoods. After removing duplicates, the total count of neighborhoods becomes 39.

Consolidated Query: The program consolidates all the previous queries into a single LINQ query to achieve the same results.

Opposing Method: The program rewrites one of the previous questions using the opposing method. For example, if the initial question was answered using LINQ query statements, it is now rewritten using LINQ method calls, or vice versa.


The project utilizes the NewtonSoftJson NuGet package to work with JSON data. It uses JsonConvert.DeserializeObject<T> method to deserialize the JSON data into appropriate classes.

To read the JSON file, the application reads the content of the data.json file and deserializes it into appropriate classes that represent the dataset.

The application then uses LINQ queries and Lambda expressions to answer the specific questions about the neighborhoods in Manhattan. The queries are used to filter, manipulate, and consolidate the data as required by each question.

The project may require breaking up the JSON data into different classes based on the structure of the JSON file and converting them into appropriate objects to work with LINQ.
