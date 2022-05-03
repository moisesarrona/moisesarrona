```java
package com.moisesarrona.me;

import java.util.LinkedHashMap;

/*
 * @author moisesarrona
 * @description About me!
 */
public class About extends Me implements Skill {

    @Override
    public LinkedHashMap<Object, String> getAllSkills() {
        LinkedHashMap<Object, String> mySkills =
                new LinkedHashMap<>();

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

    @Override
    public LinkedHashMap<String, String> getAllProjects() {
        LinkedHashMap<String, String> myProjects =
                new LinkedHashMap<>();

        myProjects.put("api-minitask", "Type in Java/SprintBoot, created to organize your tasks...");
        myProjects.put("app-minitask", "Type in Angular, consume the api from api-minitask.");
        myProjects.put("OldWestBoots", "Type in CShap/WindowsForms, manage inputs and outputs of a warehouse.");
        myProjects.put("brisapp", "Type in Php/Laravel, web application, register users, entries...");
        myProjects.put("innova-back", "in construction");

        return myProjects;
    }

    @Override
    public LinkedHashMap<String, String> getAllExperience() {
        LinkedHashMap<String, String> myExperience =
                new LinkedHashMap<>();

        myExperience.put("Infinito Computación", "Software analysis and development (web applications, desktop applications)");
        myExperience.put("Werkn", "Software development and software architecture proposals");
        myExperience.put("Grupo Castores", "Software analysis and development and migration of systems to microservices architecture");
        myExperience.put("Personal Projects", "I have developed projects to solve my problems.");

        return myExperience;
    }
}

```
