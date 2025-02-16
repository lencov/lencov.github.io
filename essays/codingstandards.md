---
layout: essay
type: essay
title: "Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2025-02-16
published: true
labels:
  - Software Engineering
  - Learning
---



Coding standards are important. They keep code clean, maintainable, and consistent across a team. Some people think of them as just formatting rules—tabs vs. spaces, brace placement—but they go beyond that. A good set of coding standards helps prevent bugs, makes reviewing code easier, and ensures that a project doesn’t turn into a mess over time.

I’ve been using ESLint at work for almost a year now, and I don’t have many issues with it. It catches mistakes early and enforces good practices. However, the VS Code ESLint extension has been annoying. It sometimes shows errors that don’t actually exist when you run the ESLint command manually. This leads to wasted time trying to fix things that aren’t real problems.

One issue I run into is forgetting to check for lint errors after making last-minute changes. I’ll fix everything, push my code, and then the build fails because of a lint error I missed. It’s not a huge deal—I just have to push another fix—but it’s just slightly annoying.



Used AI to help write this
