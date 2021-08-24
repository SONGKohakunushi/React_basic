# jsx语法规则：
---------------------------------
1.  Define the virtual DOM without '' 
2.  variables in the Virtual DOM.
Using {} when mixing JS expressions in tags
    ```
    <h2 className="title" id={myId.toLowerCase()}>
    ```
3. specify a style name of class. Using className instead of class
   ```    
    <h2 className="title" >
   ```
						
4.  inline styles to be written in the form style={{key:value}}. 
    
    If it is fontSize:'20px' to use a small hump in the form of virtual DOM
    ```
    <span style={{color:'white',fontSize:'29px'}}>{myData.toLowerCase()}</span>

    ```
5. only one root tag, so wrap div tags in the outer
   
6. tags must be closed
   ``` <input type="text"/> ``` 

   cant 
   ``` <input type="text"> ```
7. Tag initials
* (1). If the tag starts with a lowercase letter, the tag is converted to an element of the same name in HTML,if there is no element of the same name corresponding to the tag in HTML, an error is reported 
  
* (2). If it starts with an uppercase letter, React will render component, if the component is not defined, reports an error 