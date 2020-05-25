# Note for data wrangling. #

## Assess unclean data ##

* Dirty vs Messy
  * Dirty:duplicate, mistyping, etc. *quality issue*
    * Quality dimensions:
      * Completeness: missing records, etc.
      * Validity: do not conform a defined schema, real-world constraints or table-specific constrants
      * Accuracy: invalid data, e.g. weight is 5 lbs.
      * Consistency: inconsistent representations on same data. e.g. New York and NY.
  * Messy: untidy, structural issue, different type of data in the same table. *tidiness issue*
    * Typical problems:
      * Column headers are values, not variable names,
      * Multiple variables are stored in one column
      * Variables are stored in both rows and columns
      * Multiple types of observational units are stored in the same table
      * A single observational unit is scotred in multiple tables.
  * Rules:
    * Each variable forms a column
    * Each observation forms a row
    * Each type of observational unit forms a table

    
    

* Assessment:
  * Visual vs Programmatic
  * Document observations
  * Do not need to write how to fix the issue yet.

## Clean data ##
* Three steps:
  * Define: describe each issue, and define the steps to solve the issue
  * Code: Codes to solve the issue
  * Test: Test the data after cleaning codes.