## First tasks

Test gradle with:

```bash
# Execute a task
gradle -q upper

# Execute default tasks
gradle -q
```

## Java Project

My simplex school project will be used as a java project.

Available commands:

```bash
# Compile + test + jar
gradle :simplex:build

# Clean
gradle :simplex:clean

# Compile + jar
gradle :simplex:assemble

# Compile + test
gradle :simplex:check

```

See [documentation](http://gradle.org/docs/current/userguide/tutorial_java_projects.html).

