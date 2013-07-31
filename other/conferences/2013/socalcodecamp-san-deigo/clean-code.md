# Clean Code: Homicidal Maniacs Read Code, Too

## What Prevents Clean Code?

Number one reason:

"I'll clean it up later."

## The Truth About Clean Code

* Clean Code saves time.
* We can't take a short-term view of software.
* **We need to look at the lifespan of the application.**

## How Do You Write Clean Code?

* Rule of thumb:
  * "Imagine that the developer who comes after you is a homicidal maniac who
     knows where you love." - Unknown

## The Next Developer

![Json](assets/clean_code_json.jpg)

## The DRY Principle

* DRY = Don't Repeat Yourself
* copy/pasta = spaghetti code

## Comments

* Beware: comments lie
  * Code is updated or refectored to another module
* Comments do not make up for bad code
  * Explain yourself in code
  * If the code is that unclear, the code needs to be rewritten

## Good Comments

* Can be used to describe intent or clarifications
  * Example: // Sampel output: Apr 20, 2013 - 12:30 MST
* Can be used to give warnings or consequences
  * Example:

    // We do a deep copy of this colelction to make
    // sure that updates to one copy do not affect
    // the other

* Can be used for TODOs
  * Especially useful when the IDE supports it
  * These should be temporary; remove them when the task is completed

## Bad Comments

* Do not use "journaling" comments
  * Ex: // 04/20/2013 - jjc - Added tax calculation
  * This is what source control is for: Who, What, When
* Do not create "noise" comments
  * Ex: // Default constructor
  * Note: Some environments have comments systems to autogenerate
    documentation. Use this judiciously - make sure you aren't making the code
    harder to read.
* Do not comment out code
  * Code no longer in use should be deleted
  * If needed, you can always retrieve it from source control

## Functions and Methods

* Keep methods short
  * Rule of thumb: no longer than 10 lines

## Multiple Levels of Methods

* High level
  * Overview of functionality
* Mid-level
  * More details, but not too deep
* Detail
  * The "weeds" of the functionality

## Work in Small Chunks

* Test-Driven Development (TDD)
  * Encourages writing small pieces of code at a time

Remember:

**If you are not writing incremental code, you're writing excremental code.**

## Refactoring and Unit Testing

* If you don't have unit tests, you don't really know what your code does.
* If you don't know what your code does, you cannot safely refactor it.


## Be a Clean Code Advocate

* The Boy Scout rule.
  * Always leave the campground cleaner than you found it.
* The Clean Coder rule
  * Always leave the code cleaner than you found it.
