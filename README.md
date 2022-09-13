```javascript
class Quentin {
  constructor() {
    this.interest = [];
  }
  
  get school() {
    return {
      name : "Efrei",
      link : "https://www.efrei.fr/",
      logoPath : "https://www.efrei.fr/wp-content/themes/efrei/images/logo-efrei.svg"
    }
  }
  
  get job() {
    return {
      name : "Sellzone",
      link : "https://www.sellzone.fr",
      logoPath : "https://sellzone.fr/assets/img/sellzone-white.svg"
    }
  }
  
  get technos() {
    return {
      web : ["PHP", "Html", "Css", "Javascript", "NodeJs", "VueJs"],
      other : ["MySql", "Java"]
    }
  }
    
  get softwareUsed() {
    return ["Google Stuff", "JetBrains Stuff", "SourceTree", "Figma"];
  }
    
  addInterest(interest) {
     return this.interest.push(interest);
  }   
}


let qF = new Quentin();
qF.addInterest("Open Source");
qF.addInterest("Crypto");
```
