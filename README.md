```js
class AboutMe {
  constructor() {
    this.info = {
      name: "Victor Micco",
      age: 20,
      area: "Fullstack Developer",
      workinAt: "Comhub",
      previousExperience: [
        {
          company: "Anjun Express",
          role: "Software Engineer",
          period: "2023 - 2024 | 8 months",
        },
        {
          company: "Nitro",
          role: "Infrastructure Analyst",
          period: "2023 - 2023 | 6 months",
        },
        {
          company: "Metrô de São Paulo",
          role: "Mechatronical Technician",
          period: "2022 - 2023 | 1,3 years",
        },
        {
          company: "2LT Engenharia",
          role: "Frontend Developer",
          period: "2020 - 2022 | 2,2 years",
        },
      ],
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
