# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
    ```javascript
    // write the syntax
    var wdi='course';
     ```
  * How to console.log the value of a variable: (code)
    ```javascript
    // write the syntax
    console.log(wdi);
     ```
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `write a definition `
       true == 1  //true
       '5' == 5  //true
       '7' == 8  //false
       '9' !== 9 //false
    * How to use the `"==="` operator
       `write a definition `
       7 === 7 //true
       '7' === 7 //false
       9 !=== '9' //false
       true !=== 1 //false
       
    * How to use the `">"` operator: 
        `write a definition `
        5 >= 5  //true
        6 <= 5 //false
        
   * ##### How to write an if Statements 
      ```javascript
        // write the syntax
        if(5>4){
        return true;
        }
        
       ```
 * ### functions:
    * How you declare a function: 
      ```javascript
        // write the syntax
        function adding(num){
        }
       ```
    * This is the other way to declare a function: 
      ```javascript
        // write the syntax
        var num= function (){
        }
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // write the syntax
        function(num){
        num+=4;
        return num;
        }
       ```
    * This is a function that capitalizes any word: 
        ```javascript
        // write the syntax
        function adding(num){
           num.toUpperCase();
           return num;
        }
        
       ```
       
    * We use functions because:
     `write a definition use :function for create something action with many variables  `
* ### datatypes:
  * ##### Strings
    * A string is:
        `write a definition   ` stores  characters like "course ";
        
        var character='A';
    * You can capitalize a string by: 
        ```javascript
        // write the syntax
        
        character.toUpperCase();
       ```
    * Concatentation is: 
        `write a definition ` + operator does string concatenation 
    * An example of concatenation:
         ```javascript
        // write the syntax
        "say hello evry" + 7 +"morning";
       ```
  * ##### Numbers:
    * The `%` operator is: 
       `write a definition the rest of result dividing by any number`
    * Here is an example of the `%` operator in use:
       ```javascript
        // write the syntax
        2 % 4 =0
        2 % 3 =1
        
       ```
  * ##### Arrays:
    * An index is: (nouber of position inside array)
    * You can access an element in an array like this: (array[0])
    * Map:
      * .map is an array method that: 
         `write a definition `
         
             The map() method creates a new array with the results of calling a provided function on every element in this                       array
      * An example of map is: 
        ```javascript
           // write the syntax
           var arr = [1, 2, 3, 4];
            var aarplus6 = [];
           for(var i = 0; i < arr.length; i++) {
            plus5[i] = arr[i] + 6;
                       }
                       with map
                      var nwearry= arr.map(function(arr1){
                       arr1[i]+=6;
                       return arr1;
                       })
                       
         ```
    * Filter:
      * .filter is an array method that: 
          `write a definition `
            filter is method to pass in each elements inside array then create new array by specific function
         
      * An example of filter is: 
        ```javascript
           // write the syntax
           var arr=[1,2,3,4];
           for(var i=0;i<=arr.length;i++){
             if(arr[i] % 2 ===0){
             return arr[i];}
             
             
           
           }
           with filter()
           var arr=[1,2,3,4];
           var newArr=arr.filter(function(num){
           return num%2==0;
           });
           
             
         ```
    * forEach:
      * .forEach is an array method that: 
         `write a definition `
         iterating over an array;
            
      *  An example of forEach is: 
         ```javascript
           // write the syntax
           var names["soso','rorro']
           names.forEach(function(nms){
           console.log(nms);});
           
         ```

   * ##### objects
     * How to access a property  
        ```javascript
           // write the syntax
           accessing the property of an object is
           ex: hamad.car;  //result = range rover
           
           
        ```
* ### loops
     *   how to make for loop 
         ```javascript
           // write the syntax
           for(var i=0;i<=20;i++)
          ```
* ### Querying the DOM
  ```javascript
   // write the syntax
   <script>
   var preper = document.querySelectorall("p");
  ```
* ### Creating a new element in the DOM
  ```javascript
   // write the syntax
   var newP = document.createTextNode("i am new.");
   
   
   
  ```
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
   preper.appendChild(newP);
  ```
* ### Updating the style properties
  ```javascript
   // write the syntax
   function myFu() {
    document.querySelectorall("p")[0].setAttribute("class", "democlass"); 
  ```
