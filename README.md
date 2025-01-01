# Ruby Instance Variable Modification Bug

This repository demonstrates a common Ruby bug related to directly modifying instance variables using `instance_variable_set` and `instance_variable_get`.  Direct manipulation can bypass access control and potentially cause inconsistencies.  The recommended approach is to always use accessor methods (getter and setter methods) to interact with instance variables. 

**Bug:** Direct manipulation of instance variables can lead to unforeseen issues, particularly in larger, more complex programs.