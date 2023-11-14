# issue

cannot run the default schematics project

## steps

- create a schematics project

  ```
  schematics blank --name=test
  ```

- run the schematics
  ```
   cd test
   schematics .:test
  ```

 ## expected behavior

 the schematic `test` to be executed

 ## actual behavior
 
  an error occurred
  ```
  Error: Cannot find module 'test/src/test/index'
  ```
