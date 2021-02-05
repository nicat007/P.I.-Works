[![+New User](images/image1)]()  [ ] **Hide Disabled User** &emsp;&emsp;&emsp;&emsp;[![Save User](images/image2)](some.link)

----

```html
<!--The screen below must be splitted vertically. Table - on the left side, New User registration - on the right side of the scree-->
```

|[![ID](images/image1)]() | [![User Name](images/image2)]()   | [![Email](images/image3)]()               | [![Enabled](images/image4)]() |
|:-- | ----------- | -----------          | ------- |
| 1 | AdminUser   | <admin@piworks.net>      | true    |
| 2 | Test User   | testuser@piworks.net | true    |



``````
New User
``````

```html
<!--The input boxes for Username, Display Name ... come after the relevant text not below it-->
```

Username: 
``` 

```

Display Name:
``` 

```
Phone: 
``` 

```
Email:
``` 

```
User Roles:

<div style="position:relative;width:900px;height:35px;border:1;padding:1;margin:1;">
  <select style="position:absolute;top:0px;left:0px;width:800px; height:35px;"
          onchange="document.getElementById('displayValue').value=this.options[this.selectedIndex].text; document.getElementById('idValue').value=this.options[this.selectedIndex].value;">
    <option></option>
    <option value="Guest">one</option>
    <option value="Admin">two</option>
    <option value="SuperAdmin">three</option>
  </select>
      <input type="text" name="displayValue" id="displayValue" 
         placeholder="Select user roles..." onfocus="this.select()"
         style="position:absolute;top:0px;left:0px;width:750px;width:100px\9;#width:90px;height:35px; height:21px\9;#height:18px;border:1px solid #556;"  >
  <input name="idValue" id="idValue" type="hidden">
</div>



 - [ ] Enabled
