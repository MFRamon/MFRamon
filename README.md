```typescript
class MFRamon extends Person {
  name: string = "Ramon";
  work: string[] = [];
  age: number = 28;
  education: string[] = ["Software and Systems Engineering in La Salle Bajio"];

  languages() {
    return {
      human: ["Spanish (Native)", "English (C1)", "German (A1.2)"],
      programming: ["Javascript", "Typescript", "Ruby", "Java"],
    };
  }

  frameworks() {
    return ["React.js", "Vue.js", "Node", "Express", "Next.js", "Nest.js"];
  }

  miscellaneous() {
    return [
      "Material UI",
      "Fluent UI",
      "Bootstrap",
      "Tailwind CSS",
      "Vite",
      "Jenkins",
      "Git",
      "Perforce",
      "Vite",
    ];
  }

  observability() {
    return ["Splunk", "Appdynamics"];
  }

  databases() {
    return ["MongoDB", "MySQL", "MSSQL"];
  }

  ai() {
    return ["Github Copilot", "Claude AI", "Cursor"];
  }

  currently() {
    return {
      learning: ["Amazon Cloud Practioner"],
    };
  }
}
```

#### Reach me out at:

[Linkedin](https://www.linkedin.com/in/mframon/) <br/>
[Send me an email](mailto:ramon.manfig@gmail.com)
