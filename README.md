```
/*
 * @author moisesarrona
 * @description about me in different programming languages
 */
```

```java
@Override
public LinkedHashMap<Object, String> getAllSkills() {
    LinkedHashMap<Object, String> mySkills = new LinkedHashMap<>();
    mySkills.put(Java.class.getName(), "90%");
    mySkills.put(Php.class.getName(), "80%");
    mySkills.put(CSharp.class.getName(), "50%");
    mySkills.put(Angular.class.getName(), "85%");
    mySkills.put(React.class.getName(), "50%");
    mySkills.put(Sql.class.getName(), "90%");
    mySkills.put(Git.class.getName(), "85%");
    mySkills.put(Python.class.getName(), "20%");
    return mySkills;
}
```

```typescript
public getAllProjects = (): ProjectI[] => {
    const project: ProjectI[]
    return project.push(
        { api_minitask: "Type in Java/SprintBoot, created to organize your tasks..." },
        { app_minitask: "Type in Angular, consume the api from api-minitask." },
        { OldWestBoots: "Type in CShap/WindowsForms, manage inputs and outputs of a warehouse." },
        { brisapp: "Type in Php/Laravel, web application, register users, entries..." },
    )
}
```

```python
def getAllExperience():
    return thisdict = {
        "Infinito Computación", "Analysis software and development of web and desktop applications.",
        "Werkn", "Software development and architecture proposals.",
        "Grupo Castores", "Software and migration of systems to microservices architecture.",
        "Personal Projects", "I have developed projects to solve my problems."
    }
```