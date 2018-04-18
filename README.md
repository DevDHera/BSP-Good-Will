# BSP - Good Will Hunting

>This is a another extension of BSP project. To empower the social entrepreneurship I have created the following social hangout for Visionaries. Share your vision BSP will provide you a donation pool. 



### System Overview

BSP lets its customers to make micro donations to a good vision through Good Will Hunting Project. 

Spread Good will you will heal the world!

### Technologies Used

* Node.js      
* Express.js
* Passport.js
* Google Auth
* MongoDB
* MaterializeCSS

### Steps To Run

1. Install the modules.
```bash
npm install
```
2. Simply Run the App.
```bash
npm start
```

### Sample Codings

Spreading Good Will through sharing codes. (Imagine It.. Execute It)

#### How to create a Helper for Handlebars.js

```javascript
module.exports = {
    truncate: function(str, len){
        if(str.length > len && str.length > 0){
            var new_str = str + " ";
            new_str = str.substr(0, len);
            new_str = str.substr(0, new_str.lastIndexOf(" "));
            new_str = (new_str.length > 0) ? new_str : str.substr(0, len);
            return new_str + '...';
        }
        return str;
    },
}
```

### Tasks To Achive

* [x] Google Auth
* [x] MLab Production
* [ ] Populate Stories  
