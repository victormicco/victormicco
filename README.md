```js
class AboutMe {
  constructor() {
    this.info = {
      name: "Victor Micco",
      area: "Software Engineer",
      workinAt: "Anjun Brasil",
      local: "São Paulo, SP - Brazil",
      email: "victor.oficial093@gmail.com",
      phoneNumber: "+55 (11) 97885-3808",
      linkedin: "https://www.linkedin.com/in/victormicco",
    };
  }

  displayInfo() {
    console.log("===== About Me =====");
    for (const [key, value] of Object.entries(this.info)) {
      console.log(`${key}: ${value}`);
    }
    console.log("====================");
  }
}


```
