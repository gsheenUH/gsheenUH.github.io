---
layout: essay
type: essay
title: "Essay on ESLint and Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2025-02-13
published: true
labels:
  - Coding
  - Typescript
---

## Introduction

Coding standards often seem trivial—focusing on details like indentation style or bracket placement—but they can have a significant impact on productivity and collaboration. By establishing a consistent set of rules, coding standards help keep code uniform, reduce confusion, and simplify reviews. After my first week using ESLint with Visual Studio Code, I’ve come to appreciate its strengths as well as its drawbacks

## My experience with ESLint

From the outset, my initial impression of ESLint has been that it is a very handy tool. It quickly spots and fixes formatting errors that I might otherwise overlook—typos, undeclared variables, and style inconsistencies among them. In many ways, these automated checks make me more confident in my code, as I know any glaring mistakes related to style or quick syntax issues will not go unnoticed. ESLint offers a standardized set of rules that help ensure one’s code meets a certain level of uniformity. This is especially useful when working in a team environment, because everyone can adhere to a common format, making it effortless to review each other’s work. There is less time spent discussing trivial style issues and more time devoted to solving real programming challenges.

However, while ESLint is useful, I find it most effective to apply its rules once I am finished implementing the primary logic of my program. When you’re deep in the coding process—fleshing out ideas, testing small snippets, or debugging errors—ESLint can become a double-edged sword. The constant highlighting of formatting mishaps or minor rule infractions can be distracting. At times, these notifications clutter the screen, making it harder to spot more significant issues like logical errors or forgotten edge cases. It can be frustrating to be repeatedly reminded to change a semicolon or a line break when you’re trying to figure out a more pressing bug in your code. Because of this, I now prefer to temporarily silence ESLint while I’m actively coding, then enable it at the end for a thorough, automated cleanup.

## What I don't like about coding standards

Another key consideration is that coding standards—particularly those designed by large communities or prominent style guides—may impose rules that feel arbitrary. In my case, I was initially confused by certain Airbnb TypeScript standards, specifically the rule mandating single quotes for all strings. To a newcomer, it can feel burdensome to conform to every stylistic decision, especially if you’re used to a different style or prefer double quotes. Adhering to these strict rules can slow you down in the short term, as you constantly adjust your habits to satisfy the linting tool.

## Value of coding standards

Still, my experience leads me to believe that the pros of coding standards far outweigh the cons. For instance, once your team settles on a set of rules—whether it is Airbnb, Google, or a custom configuration—everyone’s code starts to look and feel consistent. This uniformity lowers the learning curve for new team members and simplifies code reviews. Instead of getting bogged down in style discussions (“Should this line be indented two or four spaces?”), reviewers can focus on more important factors such as logic, performance, and design patterns. Over time, a strictly adhered-to style guide can help make your codebase more approachable and more robust.

Moreover, coding standards can actually serve as a great educational tool. When I first started using ESLint, I didn’t just learn about stylistic choices; I also became more aware of best practices. ESLint flags variables that aren’t used, suggests more secure ways to handle certain operations, and warns you when the code might behave in an unpredictable manner. This does more than tidy up your code—it teaches you how to write better code in the first place. In this sense, coding standards are not only for aesthetic consistency but also for reinforcing good coding habits.

This essay was created with the help of artificial intelligence to format and change the tone of this essay to be more professional.
