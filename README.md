

```javascript

class AboutMe {
  constructor() {
    this.name = "Adhish";
    this.pronouns = ["he", "him"];
    this.profession = "Python Full Stack Intern @ Maitexa Technologies";
    this.preferredTechStack = ["HTML", "CSS", "javascript", "react", "python"];
    this.hasUsed = ["HTML", "CSS", "javascript", "GIT", "Github", "Vercel"];
  }

  introduce() {
    console.log(`Hi, I'm ${this.name}, a ${this.profession}.`);
    console.log(`My pronouns are ${this.pronouns.join("/")}.`);
    console.log(`Preferred tech stack: ${this.preferredTechStack.join(", ")}`);
    console.log(`I've also used: ${this.hasUsed.join(", ")}`);
  }
}

const me = new AboutMe();
me.introduce();




