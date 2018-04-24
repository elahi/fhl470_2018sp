---
layout: page
element: notes
title: DAV - challenges
---

#### INTRO TO R #####

### Challenge 1

## What are the values after each statement in the following?
mass <- 45            # mass?
age <- 120            # age?
mass <- mass * 2.0    # mass?
age <-age-20          # age?
mass_index <- mass/age # mass_index?


### Challenge 2

## We’ve seen that atomic vectors can be of type character, numeric (or double), integer, and logical. But what happens if we try to mix these types in a single vector?

## What will happen in each of these examples?
# hint(use class() to check the data type)
## Why do you think it happens?
num_char <- c(1, 2, 3, "a")
num_logical <- c(1, 2, 3, TRUE)
char_logical <- c("a", "b", "c", TRUE)
tricky <- c(1, 2, 3, "4")

## How many values in combined_logical are "TRUE" as a character in the following example?
num_logical <- c(1, 2, 3, TRUE)
char_logical <- c("a", "b", "c", TRUE)
combined_logical <- c(num_logical, char_logical)

## You’ve probably noticed that objects of different types get converted into a single, shared type within a vector. In R, we call converting objects from one class into another class coercion. These conversions happen according to a hierarchy, whereby some types get preferentially coerced into other types. Can you draw a diagram that represents the hierarchy of how these data types are coerced?


### Challenge 3

## Can you figure out why:
"four" >  "five" 


### Challenge 4 

## Using this vector of length measurements, create a new vector with the NAs removed.
lengths <- c(10, 24, NA, 18, NA, 20)

## Use the function median() to calculate the median of the lengths vector

#### STARTING WITH DATA #####