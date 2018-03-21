# WRITE IN OWN WORDS





# Coding Standard

Coding standards are version-independent and "always-current". All new code should follow the current standards, regardless of (core) version. Existing code in older versions may be updated, but doesn't necessarily have to be. The coding standards applied for this particular project are similiar to those used by Drupal (Drupals coding standards).

# Indenting and Whitespace

The indentation in the project uses indentation when nesaccary to show what is a sub-set or sub-servant of what, this is particularly shown within the conditional statements and under the loops.

Moreover the new line function (\n) was used to avoid the verbose "\ No newline at end of file" patch warning, whilst also making the file easier to read as using the clear command for the command console was not practical or robust.

# Operators

All binary operators (operators that come between two values), such as +, -, =, !=, ==, >, etc.(should) have a space before and after the operator, for readability.

# Casting

Put a space between the (type) and the variable in a cast: (int) variablename.

# Control Structures

Control structures essentially relating to if, for, while, switch, etc. Here is a sample if statement with else used in the project and a do/while encasing the if statement (though not visible in the below screen shot since it evelopes the whole code not just the below snippet):

# Line Length and wrapping

The ideology was used whilst developing the project that conditions (conditional statements) should not be wrapped into multiple lines.

Whilst Lines containing longer function names, function/class definitions, variable declarations, etc were not allowed to exceed 80 characters. Though conditiona; statements may as long as its purpose is conveyed or portrayed clearly.Furthermore comments are allowed to exceed the limit, though must be moderated still to ensuring the code is not impossible to locate as it is overwritten and encased in comments.

# Function Calls

The functions in the project were called with no spaces between the function name, the opening parenthesis, and the first parameter; spaces between commas and each parameter, and no space between the last parameter, the closing parenthesis, and the semicolon. Here's an example in the project code:

# Quotes

There wasnt really a standard for the use of single quotes and double quotes though in the project (within each module) there was an attempt to keep a certain amount of consistency.

# Comments

There isnt a particular standard to commenting other than ensuring that the comments are clear and concise, the amount of characters a comment may exceed is not set though it is recommended and was attempted to keep the comments to either one or two lines.

# Naming Conventions

Functions should be named using lowercase, and words should be separated with an underscore. Functions should in addition have the grouping/module name as a prefix, to avoid name collisions between modules.

Variables should be named using lowercase, and words should be separated either with uppercase characters.
