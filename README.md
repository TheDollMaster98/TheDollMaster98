<!-- <p align="center">
    <img alt="" src=https://img.shields.io/github/stars/xtekky?style=for-the-badge&?affiliations=OWNER%2CCOLLABORATOR />
    <img alt="" src=https://komarev.com/ghpvc/?username=xtekky&style=for-the-badge />
</p> -->

<h2 align="center">About Me </h2>

```typescript
interface AboutMe {
  email?: string;
  langs: string[];
  birthday: Date;
}

interface SkillCategory {
  Expert: string[];
  Intermediate?: string[];
  Learning?: string[];
}

class TheDollMaster98 {
  aboutMe: AboutMe = {
    langs: ["Italian", "English"],
    birthday: new Date(1998, 3, 27),
  };

  skills: Record<string, SkillCategory> = {
    Programming: {
      Expert: ["JavaScript", "TypeScript"],
      Intermediate: ["Dart", "GoLang"],
    },
    FrontEnd: {
      Expert: ["AngularTS", "Bootstrap 5", "Material Design", "TailwindCSS 3/4"],
      Intermediate: ["ReactTSX"],
    },
    BackEnd: {
      Expert: ["Firebase"],
      Intermediate: ["NodeJS", "ExpressJS", "MongoDB"],
    },
    Mobile: {
      Expert: ["Firebase"],
      Intermediate: ["Flutter"],
      Learning: ["Riverpod", "Bloc", "React Native"],
    },
    Hosting: {
      Expert: ["Firebase"],
      Intermediate: ["Heroku", "Vercel"],
    },
    Tools: {
      Expert: ["VSCode", "Android Studio"],
    },
  };
}

```

<h2 align="center">Skills </h2>

<p align="center">
	<a href="https://skillicons.dev">
	    <img src="https://skillicons.dev/icons?i=angular,react,js,ts,html,css,bootstrap,nodejs,express" />
		<br/>
	    <img src="https://skillicons.dev/icons?i=mongodb,firebase,heroku,dart,flutter,vscode,androidstudio" />
	  </a>
</p>

<p align="center">
  <img src="https://github.com/TheDollMaster98/TheDollMaster98/blob/main/assets/tate-no-yusha.gif" style="width: 20vw; height: auto;">
<p>
