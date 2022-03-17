#### 👽 Hi, I’m Mariana Moraes, web development student at Trybe. 

  <a href="https://github.com/m-moraes">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=m-moraes&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true"/>
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=m-moraes&layout=compact&langs_count=7&theme=github_dark"/>
</div>
<div>
  <a href = "mailto:mari_a.s.p@hotmail.com"><img src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" target="_blank"></a>
  <a href = "mailto:mmoraes.asp@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/mariana-moraes-87394920a/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://wa.me/qr/LFPWVI47ZAQ4E1" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>  
</div>

/*
  p5.js is a JavaScript library to make coding accessible
  for artists, designers, educators, and beginners.

  Read the docs at https://p5js.org/reference/
  Check out examples at https://p5js.org/examples/

  octocat.js is a JavaScript library to make octocats.
  Read the docs at https://github.com/octocademy/octocat.js
*/
import p5 from "p5.js";
import Octocat from "octocat.js";

let octocat;

p5.setup = () => {
  createCanvas(300, 300);
  octocat = new Octocat();

  // Put your cursor below the arrows to start editing
  // then click on an octocat setting to insert it
  // in your code. When you make changes, your octocat
  // will automatically update!
  //
  // ⬇️️️️️️️️️️️️️️️️️️️️️️️️⬇️⬇️⬇️⬇️

  octocat.setBodyColor({ primary: "#4F6AB0", underside: "#89B7CC", suctions: "#694E61" })
  octocat.setEyes("Mascara Open")
  octocat.setEyeColor("#503B37")
  octocat.setMouth("Happy Open")
  octocat.setHair("Curly Long")
  octocat.setHair("Afro Side Part")
  octocat.setHair("Pixie")
  octocat.setHair("Curly Short")
  octocat.setHairColor("#000000")
  octocat.setTop("French Top")
  octocat.setBottom("Ripped Jeans")
  octocat.setFootwear("French Shoes")
  octocat.setFootwear("Converse Shoes")
  octocat.setProp("Tea Cup Mug")
};

// ♻️ The draw method gets called repeatedly
// you can make changes here to animate!
p5.draw = () => {
  background("white");
  octocat.draw();
};
