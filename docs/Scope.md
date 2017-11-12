### Scope of Natalie 

- Able to create C project library using Cmake

- Generate object style C code module with new/free/get/set default methods

- Generate unit test template 

- Predefined error code. 

- Predefined macro to assist error handling. 

- Default doxygen style comments. 

- Kernel space support

  - Platform specifc header as such stdio.h has to be isolated
  - Memoly allocator has to be Macro
  - String manupulation/memory function as such strcpy has to be macro

- Object generation

  - Generated object should have object_type enum identify the type of object. 

- Generic set/get data type to cover all data types. 

- External and internal object can be distingushed. 

  - Only external object header goes to project header

- Quality system integration

  - Valgrind
  - Gcov
  - clang analysis

  ​

### Project use cases. 

1. Developer(D) creates new git repository to start project. 

2. D  creates  Project init file to specify the globa name spece prefix for the project. 

3. D calls create_project.py to generate new project template. 

   1. Creates src/include directory. 
      1. Include directory has project header, platform header, error header. 
      2. src has global library init/free function. 
      3. test has simple unit test calling init/free
   2. Creates Default Cmake projects with the library name.

4. D calls cmake to build library and run dummy unit tests to ensure that all runs.

5. D creates new API module

   1. Change directory to src. D calls create_module.py to create new API module
   2. ​

   ​



### Code generator requirements

| Requirements | Description | Status |
| ------------ | ----------- | ------ |
|              |             |        |
|              |             |        |
|              |             |        |
|              |             |        |
|              |             |        |
|              |             |        |
|              |             |        |
|              |             |        |
|              |             |        |



