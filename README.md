![](1.png)
![](2.png)
![](3.png)

## Issues in Javascript
1. Javascript is not strongly typed[no need to work with datatypes].

   ```js
        var name = "sachin";
        name = true;
    ```
        
2. Javascript is not strictly typed[no rules and regulations].
   ```
    2 + 3 = 5
    3 - 2 = 1
    ```
    ```
    "2" + 3 = 23
    "3" - 2 = 1
    ```
3. Javascript is not good in handling the data as it is not structured.
   ```
   {
    [
        "Name":"TV";
        "Cost":45000;
    ],
    [
        "Name":"Mobile";
        "Cost":35000;
    ]
   }
    ```
4. Javascript is not 100% OOPs language.
    - it does not support dynamic polymorphism.
    - it is not secured (deletes cache memory).
  ---
![](4.png)
![](5.png)

## Complete Overview of Page Rendering
![](6.png)

### FAQS
1. What is MIME type for script?
   
   ```
   1. <script type="text/javascript"></script>
   2. <script type="module"></script>
   ```

2. What is the difference between script in head and body?
   
    > In head section: It would be available in browser memory later it will be used while rendering.
    > 
    > In Body section: It would be a part of UI page directly.

3. How Javascript converts Static Dom into Dynamic Dom?
   
   > By linking Javascript code to html files.

4. What is strict mode in Javascript?
   > Javascript by default would not be in strict mode(no rules in declaration).
   >
   > In order to turn the strict mode "ON" we need to use "use strict";

   ```
   eg1: 
   <script type="text/javascript">
   a=10;
   console.log(a); //10
   </script>
   ```

   ```
   eg2: 
   <script type="text/javascript">
   "use strict";
   a=10;
   console.log(a); // uncaught refrence :a not defined
   </script>
   ```

   ```
   eg3: 
   <script type="text/javascript">
   "use strict";
   let a;
   a=10;
   console.log(a); // 10
   </script>
   ```

5. How to target Javascript for Legacy Browsers? [Old Version Browsers]
   
   How to target advanced features of CSS to work with all browsers?
    > Refer Image
    >
    > ![](7.png)

6. How to link external javascript file to html file?
   ```
   <script type = "text/javascript" src = "">
   ```

7. How Javascript take the control over the HTML elements?
   > We need to target the html elements and take control over the elements.

---
<br>

![](11.png)
<br><br>
![](8.png)
<br><br>
![](9.png)
<br><br>
![](10.png)
#### Note:- 
1.  In Javascript "Arrays are dynamic".
2. Acessing the elements using DOM heirarchy through index is not a good practice.
   > Solution: Access it with a name.

#### Using name attibute for HTML Elements
syntax: 
- name.property = value; //name is not a form element <br>
- formName.elementName.property = value; // if element is a form input
<img src="12.png" width="500" height="100">

syntax: arrayOfElements = document.getElementsByName("Name").<br>
arrayOfElements[index].property = value;

#### Limitation
a. In case of radio buttons, multiple elements will have same name, at that time javascript code would fail.




