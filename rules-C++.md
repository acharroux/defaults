# Brief : rules for C++ coding

## USE-C++-17
When not specified, C++ 17 is the version to use for C++. All goodies and features of C++ must be used when possible.
Objective is to generate code with best qualities:
- short code: Use all expression power of C++-17
- solid code: use Standard C++ lib and best practices of C++ as much as possible
- efficient code: unless specified, consider code will be used in embedded devices where memory is sparse
- strongly typed: use all the power of static types and static checks provided by C++-17

## USE-SEVERAL-COMPILERS
For the same project, do a gcc build and a clang build

## ACTIVATE-ALL-CHECKS
when compiling, activate all warnings and consider a warning as an error unless explicit authorization.
Each relaxing of a warning has to be listed into a file named `relaxed-warnings.md`

## USE-LINTER
Apply linters when building and fix detected issues