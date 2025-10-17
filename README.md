```javascript

class AlexandreTortoza {
  constructor() {
    this.hello = "👋 Bem-vindo ao meu GitHub!";

    this.about = {
      name: "Alexandre Marques Tortoza Canoa",
      role: "Full-Stack & UI/UX Developer",
      location: "Curitiba - PR, Brasil 🇧🇷",
      focus: [
        "Vue 3 + Laravel",
        "Ruby, Python",
      ],
      studying: [
        "Inteligência Artificial e ML",
        "Arquitetura de Software",
        "Sistemas Distribuídos",
      ],
    };

    this.stack = [
      "Vue 3",
      "Laravel ",
      "TypeScript",
      "JavaScript",
      "PHP",
      "TailwindCSS",
      "Bootstrap",
      "Python",
      "Docker",
      "MySQL",
      "MongoDB",
      "Figma",
    ];

    this.featuredRepos = [
      {
        name: "portfolio",
        description:
          "Meu portfólio profissional — com Tailwind, animações e seções dinâmicas em Vue 3.",
        link: "https://github.com/Alexandre-Tortoza/portfolio",
      },
    ];

    this.links = {
      github: "https://github.com/Alexandre-Tortoza",
      linkedin: "https://www.linkedin.com/in/alexandre-tortoza",
      portfolio: "https://alexandre-tortoza.github.io/",
    };

    this.funFact =
      "Curioso por natureza!";
  }

  greet() {
    console.log(`${this.hello}\nSou ${this.about.name} — ${this.about.role}`);
  }
}

const alexandre = new AlexandreTortoza();
alexandre.greet();


```
