<link rel="stylesheet" href="assets/css/styles.css">

<div class="image__contain">
<img src="assets/img/wallpaper.png" class="imagen__main"/>
</div>

## Hi humans and robots

Hi, I'm Moises  software architect and software enginner, I love writing 👨🏻‍💻 code and playing the guitar 🎸. This is my Github and my portfolio, here has my personal projects.

In my free time I maintain and create Open-Source projects for the community and Closed-Source for Companies. Take a look at my projects.

>Projects
<div class="row">
<div class="column__50">

```java
List<Project> projects = 
        projectRepository.getAllProjects;

return projects.stream()
    .filter(p -> p.getStatus().equals("Finalizado"))
    .filter(p -> p.getType().equals("Open-Source"))
    .collect(Collectors.toList());
```

</div>
<div class="column__50">

- [arron-edi](https://github.com/moisesarrona/arron-edi) - A package written `Java` to read and convert EDI x12 to JSON files etc.
- [arron-privacy](https://github.com/moisesarrona/OldWestBoots) - A package with UI written in `Java` to manage credentials with encryption.
- [OldWestBoots](https://github.com/moisesarrona/OldWestBoots) - An application written in `C#` to control sales and warehouse.
- [mini-app](https://github.com/moisesarrona/OldWestBoots) - Set of applications written in `Java` (`microservices`) and `Angular`to manage tasks, projects, etc.

</div>
</div>

>Experience
<div class="row">
<div class="column__50">

```TypeScript
const experiences: Experience[] = 
    this.experienceService.getAllExperience();

return experiences
  .filter(e => e.type === "Software")
  .sort((a, b) => b.id - a.id)
  .slice(0, 4);
```

</div>
<div class="column__50">

- **Personal Projects** - Software Engineer.
- **Grupo Flecha Amarilla** - Software Architect.
- **Grupo Castores** - Software Engineer.
- **Werkn** - Frontend Developer.

</div>
</div>

>Skills
<div class="row">
<div class="column__50">

```Sql
SELECT s.name, s.percentage, st.name
FROM skills AS s
INNER JOIN skill_tech AS st ON s.id = st.id_skill
WHERE s.status = 'activo' AND s.type = 'tech'
GROUP BY s.name, s.percen;
```

</div>
<div class="column__50 row">
<div>

- **Java** `90%`.
- **PHP** `80%`.
- **Python** `80%`.
- **C#** `85%`.
- **Sql** `90%`.

</div>
<div>

- **Git** `80%`.
- **CSS/HTML** `95%`.
- **Angular** `85%`.
- **React** `75%`.

</div>
</div>
</div>