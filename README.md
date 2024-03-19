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

const cristinaRamos = {
  personalInfo: {
    name: "Cristina",
    role: "Full Stack Developer",
    linkedIn: "https://www.linkedin.com/in/cristinaramospascual",
  },
  
  skills: {
    frontend: ["JavaScript", "HTML", "CSS", "MUI", "Bootstrap"],
    backend: ["NodeJS", "Express"],
    databases: ["MongoDB"],
    frameworks: ["React"],
    tools: ["Git", "GitHub", "VS Code", "npm", "Webpack"],
  },
  
  currentlyLearning: "TypeScript",
  
  introduceYourself: () => {
    console.log(`
      Hello! I'm ${cristinaRamos.personalInfo.name},a ${cristinaRamos.personalInfo.role}.
      If you want to know a bit more about me, visit my LinkedIn profile: ${cristinaRamos.personalInfo.linkedIn}
    `);
  },
};

cristinaRamos.introduceYourself();

console.log(`
  I have experience in a variety of technologies, including:

  Frontend: ${cristinaRamos.skills.frontend.join(', ')}
  Backend: ${cristinaRamos.skills.backend.join(', ')}
  Databases: ${cristinaRamos.skills.databases.join(', ')}
  Frameworks: ${cristinaRamos.skills.frameworks.join(', ')}
  Tools: ${cristinaRamos.skills.tools.join(', ')}
`);

console.log(`
  I have a passion for gaining new insights, rigth know I am learning ${cristinaRamos.currentlyLearning}.
`);
