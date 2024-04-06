```js
class AboutMe {
  constructor() {
    this.info = {
      nome: "Victor Micco",
      area: "Software Engineer",
      trabalho: "Anjun Brasil",
      local: "São Paulo, SP - Brazil",
      email: "victor.oficial093@gmail.com",
      linkedin: "https://www.linkedin.com/in/victormicco",
      github: "https://github.com/victormicco-anjun",
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

class Background {
  constructor() {
    this.info = {
      inicio: 2020,
      experiencia: [
        "Metro de São Paulo - Mechatronics",
        "2Lt Engenharia - Frontend Developer",
        "Personal projects",
        "Freelance projects",
        "Current: Software Developer at Anjun Express"
      ],
    };
  }

  displayInfo() {
    console.log("===== Background =====");
    for (const [key, value] of Object.entries(this.info)) {
      if (Array.isArray(value)) {
        console.log(`${key}:`);
        value.forEach(item => console.log(`- ${item}`));
      } else {
        console.log(`${key}: ${value}`);
      }
    }
    console.log("======================");
  }
}

```
