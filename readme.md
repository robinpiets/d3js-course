#Fireball Boilerplate


##New Project Setup
1. **Decipher:** Make a new project - MASTER. Duplicate project for – SCRIPTING & – STAGING.
2. **Decipher:** Change url. Menu > Project Settings. XXXXXX_staging XXXXXX_scripting.
3. **Slack:** Make group, add project url URL_staging, add Fireballers.
4. **Github:** Make repository. Add link at fireball organization page.
5. **Github:** Go to the your projects DIR and do:
```
git copy https://github.com/fireball-conversation-design/fireball-boilerplate-v2 https://github.com/fireball-conversation-design/XXXXXXXXX
git clone https://github.com/fireball-conversation-design/XXXXXXXXX
```
will only work if you did: `sudo gem install git-copy`
more info: https://github.com/cybertk/git-copy

6. **Terminal:** `cd XXXX-XXXXX` // new folder with the new repo

7. **Editor:** Edit project.json ⚠️⚠️⚠️
8. **Editor:** Edit Jenkinsfile ⚠️⚠️⚠️
9. **Decipher:** Get scripting.xml
10. **Editor:** Edit survey.xml
    * change project name
    * check sections: development settings, language settings, continue buttons (should be after sample sources)
    * check sections: rotate device & evaluation
11. **Terminal:**: Jenkins sync at jenkins.fireball.amsterdam    
12. **Terminal:**
    * `npm install`
    * `git add .`  
    * `git commit`   
    * `git push`
13. **Github:** Remove all default labels & branches    
14. **Terminal:** git labelmaker

15. **Github:** Add issue with links, template:
``` 
**Test links**
YES hidden screens
http://survey.epiphany-rbc.com/survey/selfserve/53c/161216?
NO hidden screens
http://survey.epiphany-rbc.com/survey/selfserve/53c/161216?list=2

**Developer links**
YES hidden screens
http://survey.epiphany-rbc.com/survey/selfserve/53c/161216_staging?
NO hidden screens
http://survey.epiphany-rbc.com/survey/selfserve/53c/161216_staging?list=2
```

##Boilerplate Installation
- `npm install`
- `gulp`

#TODO:

- add list of all gulp commands
