##This script allows you to copy, move or remove files matching certain pattern

###Usage

Move script file to your /usr/bin/ directory
and then it can be used the following way:
```ucp dir_from dir_to pattern command(cp, mv, rm)```

*For rm command dir_from and dir_to are supposed to be same and they must be specified*

###Example 
```ucp ./src ./resources "vs.*" mv```

All files with name containing vs. will be moved to resources directory
