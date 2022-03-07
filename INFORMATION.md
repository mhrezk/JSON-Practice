# JSON Tutorial

## Description

JavaScript Object Notation, or `JSON`, is a format utilized in files that are independent of any programming language. The ratiocination behind the nomenclature is the similarity of `name-value` pairs in JavaScript objects; however, the syntax of JSON files differs slightly. The syntax will be covered below, but it is incredibly important to remember that a JSON file is referred to as an object.

## Purpose

`JSON` files are quite common with regards to requests between users or APIs, due to its simple and understandable syntax. As such, it is not considered a programming language, for it is frequently used for its syntactical advantage.

## Value Data Types

Though the object of JSON, or a JSON file, is a collection of `name-value` pairs, the `name` attribute is limited to one data type, which is `String`. However, the `value` attribute assigned to each `name` for the formation of the pair can be from the following datat types:

- String: A series of alphanumerical entries that are normally surrounded by double quotes (`""`).
- Number: Any integers or floating-point numbers and exponents are within this category.
- Boolean: Binary choices between `true` and `false` keywords. The letters within either words MUST be lowercase letters.
- Null: A name without a value is nullified using the `null` keyword. The letters within the word MUST be lowercase letters.
- Object: A collection of various `name-value` pairs that are assigned to ONE `name` attribute.
- Array: A collection of `value` attributes that are assigned to ONE `name` attribute.

## Syntax

Since `JSON` files __do not permit comments__, the syntax that illustrates the different forms will be shown within this section. The actual `JSON` file will be supplied separately within the remote repository.

### Formatting

The following are rules pertaining to the format of a `JSON` file:

- The `JSON` file, or object is surrounded by curly braces (`{}`).
- Each `name` attribute is separated from the `value` attribute within a SINGLE pair through the colon (`:`).
- Each `name-value` pair is separated from one another via the comma (`,`).
- If a `name` attribute has an object for a `value`, then the object must be encompassed in curly braces (`{}`).
- String `name` and `value` attributes must be enclosed in double quotes (`""`).
- Numerical, boolean and nullable `value` attributes are written without any punctuation.
- If a `name` attribute has an array for a `value`, then the array must be encompassed in square brackets (`[]`), as is the circumstance in programming languages.
- Different `value` attributes of an array, commonly known as elements in programming languages, are separated by the comma (`,`).
- Though an array is not limited to `value` attributes of the same datat type - to create associative arrays - it is recommended for portability and interchangeability.
- The __last__ `name-value` pair never precedes a comma (`,`), as the end of the `JSON` file does not warrant the presence of a comma (`,`).

### Example

{ _//Beginning of `JSON` file, or `JSON` object_

    "name" : "Mohammad", _//String data type_
    "age" : 40, _//Numerical data type_
    "isMan" : true, _//Boolean data type_
    "student" : null, _//Nullable data type_
    "hair" : _//Object data type_
    { 
        "colour" : "black",
        "height" : "short"
    },
    "grades" : _//Array data type_
    [ _//Array of objects
        {
            "Math" : 5
        },
        {
            "Biology" : 5
        },
        {
            "English" : 7
        },
        100 _//Numerical data type 
    ]
} _//Ending of `JSON` file, or `JSON` object_

## Format Validation

Below are various websites that assist in confirming the validity of the syntax utilized within a `JSON` file:

- [JSON Editor Online](https://jsoneditoronline.org/)
- [JSONLint: The JSON Validator](https://jsonlint.com/)
- [JSON Formatter](https://jsonformatter.curiousconcept.com/)

## Usage

The repository is openly available to whomever wishes to clone and improve upon it. I would kindly ask if you could submit pull requests for your improvements so that everyone can access such enhancements.
