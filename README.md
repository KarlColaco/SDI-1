# Updates
Post Updates to the code here
# Contribution Guide
# Contributing

When contributing to the repository please ensure you announce you are using the repo via whatsapp to the rest of the group
and what it is in reference to as to avoid merge conflicts and keep everyone up to date. 

Please familiarise yourselves with the guides below before coding.

## Pull Request Process

 - Please make sure you only upload code files, do not upload big QT files etc...
 
 - Update the README.md file with detailed changes or any notes to add during every push.
 
 - When merging, do not delete code without letting someone know.
 
# Coding Style Guide
 
 For the reference manual we will be using DOXYGEN, this is a program that auto generates documentation from your code.
 If everyone follows the guidelines i have set out below then it will make documenting the program nice and simple.

## Classes and Functions
- When creating a new class, provide a brief description above the declaration with a triple slash "///"

- This will also need to be done for the functions too, you MUST provide a brief description for the functions and it is optional to provide descriptions for the parameters/returns however if a detailed description is required see and follow the template below.

- Please make sure you put the documentation in the header file where the classes are declared.

            /// This is a brief description of the class this will be showed as a preview for the class when going through the doxygen doc
            /// 
            /// Detailed description of the class
              class classname{
                  /// Brief function desc
                  /// 
                  /// Detailed function desc
                  @param a - description of the a parameter
                  @param b - description fo the b parameter
                  @returns - description of what is returned
                  @see - anotherMemberFunction() - links this function to another functions 
                  @attention - creates a side note to grab the users attention
                  int memberfunction(int a, int b);


                  void anotherMemberFunction();
                }
- If anything requires you to highlight a specific piece of code in your description please put
    /// ###Example
    /// ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~.cpp
    /// int a = 16;
    /// ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~.cpp




## Header files
Please create seperate header files to declare classes.

The advantage of having a seperate header file for the class is that it makes it very simple to make changes, scrolling through hundreds of lines of code trying to find the right class to edit is tedious and inefficient.

- Header files must be used to declare classes given an appropriate name for the class used.


 

