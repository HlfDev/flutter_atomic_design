# **Design System with Atomic Design in Flutter**

Nowadays, one of the most popular ways to organize and maintain components and modules used by design teams is Atomic Design, a file structure methodology that breaks down all the elements of a page. In this article, I briefly show how to structure a design system using the Atomic Design methodology in a Flutter project.

## What is a Design System?

![Design System](https://cdn-images-1.medium.com/max/2400/0*Ulv6WrzC80NrSydn)

A Design System is a collection of reusable components standardized for a specific product, website, or system. Unlike a style guide, a design system goes beyond aesthetics: it unifies the language of a product.

Think of the design system not as a project but as an internal product of the company, requiring people to update it as they develop new solutions, new components, and new style guides—from rounded buttons and code snippets to brand application concepts and text tone of voice.

## What is Atomic Design?

![Atomic Design Concept](https://cdn-images-1.medium.com/max/2400/0*fKAp5Ca1nwMDuH2f.jpg)

> "Atomic design is a methodology that helps us think about the user interface hierarchically and reinforces the importance of effective pattern libraries, presenting techniques to optimize the workflow of design and development teams. Atomic design also details what happens during the creation and maintenance of design systems, allowing UIs to be implemented with greater consistency and quality." — **Brad Frost**

## Advantages of Using Atomic Design in a Design System

![Advantages](https://cdn-images-1.medium.com/max/2000/0*wOqiD_0Lyn5oyXGC)

- **Reusable Components** — By creating your own library, you have the necessary elements for any design challenge. You can also mix and match components very easily.

- **Easily Understandable and Maintainable Layout** — The code of an atomically designed application is generally much easier to read than one created using traditional methods. This holds true not only during development but also in the future when reviewing the application for reference or making minor adjustments.

- **Fewer Overall Components** — If a developer has a predefined list of atoms, molecules, and organisms before starting an application, they are more likely to use existing components rather than create new ones for small variations.

## The Atomic Design Methodology by Brad Frost

![Atomic Design Levels](https://cdn-images-1.medium.com/max/2000/1*eZPt94azWW8dWa0gtHA-QQ.png)

Atomic Design is inspired by the concept of atoms and molecules from chemistry and consists of five distinct levels:

### Atoms

In chemistry, atoms are the fundamental building blocks of matter. Think of an atom as a LEGO piece: they are considered the basic components of interfaces that do not require other elements to exist. Buttons, labels, and checkboxes are examples of atoms.

![Atoms](https://cdn-images-1.medium.com/max/2000/1*3gl7xaspVntN-f9BttIXVw.png)

### Molecules

When two or more atoms, whether identical or different, combine, they form molecules with new properties. In our context, molecules in UI development represent the combination of basic interface components to create more tangible elements.

![Molecules](https://cdn-images-1.medium.com/max/2000/1*DuruBJPJ-zTizR3C0HhRrQ.png)

### Organisms

Atoms and molecules together form an organized and complex structure. Just as organisms exist in biology and chemistry, in UI design, this structure consists of the combination of atoms and molecules, forming more complex components that guide navigation within a layout.

![Organisms](https://cdn-images-1.medium.com/max/2000/1*e_Cce0q54AH3vab6Ez_jHg.png)

### Templates

The chemistry analogy does not extend to the next phases. Formed by the union of organisms, templates aim to display the structure of a layout in a simplified way. The key at this stage is to understand how components will interact with each other and whether the composition makes sense.

![Templates](https://cdn-images-1.medium.com/max/2000/1*ZHy9XgkweqCYvoeR3pybhA.png)

### Pages

With organisms, molecules, and atoms working harmoniously together, templates evolve into pages, where real content is added. This final stage is the most concrete part of Atomic Design, as it represents the layout that users will actually interact with in the application.

![Pages](https://cdn-images-1.medium.com/max/2000/1*k2yPHb7Wl3p3bQH9zcjzvQ.png)
