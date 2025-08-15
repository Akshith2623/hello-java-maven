# Task 8 – Java Maven Build on Jenkins

## What I built
A simple Java app (`HelloWorld`) packaged with Maven and built in Jenkins.

## Steps I followed
1. Ran Jenkins in Docker (`jenkins/jenkins:lts`) on port 8080.
2. Installed Git inside the container.
3. Configured Maven in Jenkins (Manage Jenkins → Tools → Maven → Install automatically).
4. Pushed the Java project (`pom.xml`, `HelloWorld.java`) to GitHub.
5. Created a Freestyle job → SCM (Git) → Build step: `clean package`.
6. Triggered a build and verified **BUILD SUCCESS** in Console Output.

## Repo contents
- `src/main/java/HelloWorld.java`
- `pom.xml`

Screenshot of BUILD SUCCESS:
<img width="1916" height="1028" alt="Screenshot 2025-08-15 184109" src="https://github.com/user-attachments/assets/f6046546-6479-4bc3-b4ef-3f9f3a650ba9" />

