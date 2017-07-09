# TestDrivingVim
Developping some common patterns in VimL, Test Driven.

# Prerequisist

Installation of the vim plugin [Lab42VimBaseTools](https://github.com/RobertDober/Lab42VimBaseTools)  

# TDD of Opaque objects

Let us create a first test

```vim
function! TestTheTestTool()
  call lab42#test#assertEq(1, 1)
endfunction

```

In order to run the tests we create a tiny shell script in this repro [vimtest](vimtest)  

and by running it we shall see output like [that](assets/images/first_test_run.png)  

# Copyright and LICENSE

© 2017 Robert Dober robert&lt;dot>dober&lt;at>gmail... 

Licensed under the conditions of the Apache 2.0 license specified in [LICENSE](./LICENSE)
