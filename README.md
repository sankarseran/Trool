# Trool
## The TypeScript Rule Engine

- Manage rules in a business spreadsheet format
- Get your rules out of your code so non-engineers can make updates over time 
- Heavily inspired by Java's KnowledgeBase Library

https://github.com/CacheControl/json-rules-engine

// mention that strict format is enforced readability purposes.
// mention values provided must be null, boolean, number, string, or be a property on an import
// mention that if a spreadsheet import and code import have the same name. The spreadsheet will override
the code import
// mention that it's not a good practice to set strings in directly to the spreadsheet and should
// use a constants class. This prevents Product Owners from inputing bad values into the spreadsheet.
// a fact must have a getter and a setter to be modified

// Object passed for fact "fact name" does not have the attribute or method "attribute or method" name
// iterate through each cell in Rule row, check the value in that cell using the condition at that index. 
// Set value at that cell to true and false. Break if hits false
// empty cell will just be set to true
// dont execute Action where blank
