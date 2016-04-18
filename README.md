## Strengths and Weaknesses of C
Like any other programming language, C has strengths and weaknesses. Both stem from the language's original use (writing operating system and other systems software) and its underlying philosophy:

- **C is a low-level language.** To serve as a suitable language for systems programming, C provides access to machine-level concepts (bytes and addresses, for example) that other programming language try lo hide. C also provides operations that correspond closely to a computer's built-in instructions, so that programs can be fast. Since application programs rely on it for input/output, store management, and numerous other services, an operating system can't afford to be slow.
- **C is a small language.** C provides a more limited set of features than many languages. To keep the number of features small, C relies heavily on a "library" of standard functions.
-- **C is a permissive language.** C assumes that you know what you're doing, so it allows you a wider degree of latitude than many languages. Moreover, C doesn't mandate the detailed error-checking found in other languages.

### Strengths
C's strengths help explain why the language has become so popular:
- **Efficiency.** Efficiency has been one of C's advantages from the beginning. Because C was intended for applications where assembly language had traditionally been used, it was crucial that C programs could run quickly and in limited amounts of memory.
- **Portability.** Although program portability wasn't primary goal of C, it has turned out to be one of the language's strengths. When a program must run on computers ranging from PCs to supercomputers, it is often written in C. One reason for the portability of C programs is that -thanks to C's early association with UNIX and the later ANSI/ISO standards- the language hasn't splintered into incompatible dialects. Another is that C compilers are small and easily written, which has helped make them widely available. Finally, C itself has features that support portability (although there's nothing to prevent programmers from writing nonportable programs).
- **Power.** C's large collection of data types and operators help make it a powerful language. In C, it's often possible to accomplish quite a bit with just a few lines of code.
- **Flexibility.** Although C was originally designed for systems programming, it has no inherent restrictions that limit it to this arena. C is now used for applications of all kinds, from embedded systems to commercial data processing. Moreover, C imposes very few restrictions on the use of its features; operations that would be illegal in other languages are often permitted in C. For example, C allows a character to be an integer value (or, for that matter, a floating-point number). This flexibility can make processing easier, although it may allow some bugs to split through.
- **Standard library.** One of C's great strengths is its standard library, which contains hundreds of functions for input/output, string handling, storage allocation, and other useful operations.
- **Integration with UNIX** C is particularly powerful in combination con UNIX (including the popular variant known as Linux). In fact, some UNIX tools assume that the user knows C.

### Weaknesses
C's weaknesses arise from the same source as many of its strengths: C's closeness to the machine. Here are a few of C's most notorious problems:
- **C programs can be error-prone.** C's flexibility makes it an error-phone language. Programming mistakes that would be caught in many other languages can't be detected until the program is run. To make matter worse, C contains a number of pitfalls for the unwary.
- **C programs can be difficult to understand.** Although C is a small language by most measures, it has a number of features that aren't found in all programming languages (and that consequently are often misunderstood). These features can be combined in a great variety of ways, many of which --although obvious to the original author of a program-- can be hard for others to understand. Another problem is the terse nature of C programs. C was designed at a time when interactive communication with computers was tedious at best. As a result, C was purposefully kept terse to minimize the time required to enter and edit programs. C's flexibility can also be a negative factor; programmers who are too clever for their own good can make programs almost impossible to understand.
- **C programs can be difficult to modify** Large programs written in C can be hard to change if they haven't been designed with maintenance in mind. Modern programming languages usually provide features such as classes and packages that support the division of a large program into more manageable pieces. C, unfortunately, lacks such features.
