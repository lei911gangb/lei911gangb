### Hi there 👋


```julia
module main

aboutMe :: struct {
  pronouns :: string[];
  languages :: string[];
  hobbies :: string[];
  funFact :: string;
}

main :: func(): void {
  ethan :: aboutMe = {
    pronouns: ["He", "Him"],
    languages: ["C", "C#", "Java", "Python"],
    hobbies: ["Coding", "Gaming", "Talking"],
    funFact: "The first computer virus was created in 1983!"
  };

  println "Pronouns: ${ethan.pronouns}";
  println "Languages I Know: ${ethan.languages}";
  println "My Hobbies: ${ethan.hobbies}";
  println "Fun Fact: ${ethan.funFact}";
}
```
