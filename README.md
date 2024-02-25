```ts
class SoftwareEngineer {
  constructor() {
    this.name       = "Zain Shabbir"
    this.role       = "Software Engineer"
    this.portfolio  = "https://zainsci.dev"
    this.twitter    = "https://twitter.com/zainsci"
    this.languages  = ["TypeScript", "JavaScript", "Python"]
    this.frontend   = ["React", "NextJs", "Svelte", "SCSS", "TailwindCSS"]
    this.backend    = ["Express", "Flask", "NestJs"]
    this.interests  = ["Compilers", "UI Design", "Low Level Languages"]
  }

  sayHello() {
    console.log("Hello There ✋")
  }
}

const fullStackDev = new FullStackDev()
fullStackDev.sayHello()
```
