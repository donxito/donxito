# Hi there 👋 I'm Miguel

<!--
**donxito/donxito** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```javascript
const miguelChito = {
  personalInfo: {
    name: "Miguel",
    role: "Full Stack Developer",
    linkedIn: "[https://www.linkedin.com/in/miguelchito-reactdeveloper]",
  },
  
  skills: {
    frontend: ["JavaScript", "HTML", "CSS", "MUI", "Bootstrap"],
    backend: ["NodeJS", "Express"],
    databases: ["MongoDB"],
    frameworks: ["React"],
    tools: ["Git", "GitHub", "VS Code", "npm", "Webpack"],
  },
  
  
  introduceYourself: () => {
    console.log(`
      Hello! I'm ${miguelChito.personalInfo.name}, a ${miguelChito.personalInfo.role}.
      If you want to know a bit more about me, visit my LinkedIn profile: ${miguelChito.personalInfo.linkedIn}
    `);
  },
};

miguelChito.introduceYourself();

console.log(`
  I have experience in a variety of technologies, including:

  Frontend: ${miguelChito.skills.frontend.join(', ')}
  Backend: ${miguelChito.skills.backend.join(', ')}
  Databases: ${miguelChito.skills.databases.join(', ')}
  Frameworks: ${miguelChito.skills.frameworks.join(', ')}
  Tools: ${miguelChito.skills.tools.join(', ')}
`);
