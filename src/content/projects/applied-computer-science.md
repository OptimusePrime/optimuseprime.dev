---
title: 'Applied Computer Science'
description: 'A CS web development curriculum for high schools'
image:
    url: '/GitHub.webp'
    alt: 'GitHub wallpaper'
platform: Web
stack: TypeScript, Svelte, Node.js, SQLite
website: https://informatika.petagimnazija.hr/
github: https://github.com/Erasmus-Project-V/
---

Applied Computer Science (ACS) is a curriculum focused on application development using web technologies tailored to Croatian high schools.
Although, it could be easily adapted for use in a university setting.
ACS was a brain child of my colleagues at The Fifth Gymnasium and me.
It's currently being developed under the supervision and support of Dr. Predrag Brođanac and other CS teachers at the school.
Accompanying the curriculum will be a full suite of educational materials and resources for both students and teachers alike.
Various elements of ACS were heavily inspired and adapted from Harvard's CS50 course. 
Even though the curriculum content is different, the vision is the same: to teach newcomers to CS how to develop software and solve problems using programming.

## The Textbook

The most useful material provided will be a textbook written from scratch in Croatian, and freely released online under the CC BY-NC-SA license on the curriculum website.
The textbook is in digital form using mdBook, a Markdown book generator written in Rust.
This allows us to embed a suite of interactive materials within the text itself, including quizzes and interactive code examples powered by Codapi, Codepen, and StackBlitz.
These interactive materials increase student engagement since students aren't just passively reading the text, but are actively interacting with the material as they read about it.
It also decreases friction required to start applying newly learned concepts: the tools are right in front of them.

## The Content

Students will start by learning HTML and basic CSS, later moving on to more advanced CSS concepts (e.g., flexbox, grid, box model).
Having learned how to create static websites, they'll begin learning JavaScript, quickly transitioning to TypeScript because we want to give students the feel of a statically-typed language (In Croatian schools, particularly those focused on science and math, as is mine, Python is taught in regular, mandatory CSS classes).
At some point, every web developer needs to learn a JS framework (e.g., React, Vue, Angular), we've chosen Svelte.
We feel it is one of the simplest, yet equally powerful, of the offerings.
Once the students have learned HTML/CSS/JS, learning Svelte won't bring a steep learning curve since, at least for the basic material they'll learn, there isn't a lot of complex concepts to cover.

Transitioning from frontend to backend development, they'll program, again in TypeScript, using Node.js and Express.js, and learn how to develop REST APIs, CLIs, and other sever-side apps.
Once the basics are covered, they'll be introduced to basic SQL using SQLite.
Following will be an introduction to web security and authentication.

As I've hinted at the beginning, the students won't just learn how to create web apps.
A web developer can actually create an application for almost any platform, including desktop and mobile.
The students will at the end of the course be introduced to Capacitor.js (and Electron.js), showing them a wider perspective on software development.

For the end of the course, they'll be required to develop a final project (a web, mobile or desktop app) in groups of 2-3 students.

## The Pedagogy

The class will be taught, since it's designed for high schools, in groups of about 20 students, allowing for an active learning environment.
Inspired by CS50, the students will at the very beginning of the course be introduced to a standardized development environment.
For this, we're leveraging existing CS50 infrastructure, which is quite well adapted to our goals, [cs50.dev](https://cs50.dev]).
Like CS50, we'll encourage students to use AI tools (CS50's DDB and ChatGPT) in an academically honest and productive way.

