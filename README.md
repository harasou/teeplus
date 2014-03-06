teeplus
=======
The teeplus, It is a thing able to add a time to the output of the tee command.

1. Install

   ```
   git clone git@github.com:harasou/teeplus.git
   cd teeplus
   make tee
   ```

2. Usage

   ```
   usage: tee [-ai] [-t [date_format]] [file ...]
   ```

   ```
   $ cat README.md | ./tee -t test.log
   $ head test.log
   teeplus
   [2014/03/07 05:22:30] =======
   [2014/03/07 05:22:30] The teeplus, It is a thing able to add a time to the output of the tee command.
   [2014/03/07 05:22:30]
   [2014/03/07 05:22:30] 1. Install
   [2014/03/07 05:22:30]
   [2014/03/07 05:22:30]    ```
   [2014/03/07 05:22:30]    git clone git@github.com:harasou/teeplus.git
   [2014/03/07 05:22:30]    cd teeplus
   [2014/03/07 05:22:30]    make tee
   ```
