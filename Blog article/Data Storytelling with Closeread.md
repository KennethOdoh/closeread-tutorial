## Introduction (150–300 words)
---
### What is Scrollytelling?
Scrollytelling is a dynamic, interactive storytelling technique often used in web-based formats, that reveals insights, visuals, and narrative elements as the user scrolls down the page. It allows data stories to unfold gradually, guiding the reader through a structured narrative in a way that feels both natural and engaging.

### Why Scrollytelling Is Effective for Data Communication
Scrollytelling is a powerful way to communicate data because it helps reduce information overload, boosts user engagement, and makes insights easier to digest. Rather than overwhelming users with dense dashboards or complex visuals all at once, it guides them through your story step by step—just by scrolling.

As a dynamic and flexible technique, scrollytelling supports various content formats such as text, charts, maps, GIFs, and images. It empowers you, the author, to control the pacing and structure of your narrative while keeping readers engaged through suspense and sequential reveals. This method not only presents data but also wraps it in meaningful context, helping readers connect the dots without confusion. There's no guesswork—no need to click, swipe, or explore aimlessly. Just scroll, and the story unfolds. Compared to traditional dashboards, which often present too much information at once, scrollytelling offers a smoother, more intuitive experience—especially for readers who need guidance or aren't data-savvy.

### The Challenge
Despite its many advantages, scrollytelling has traditionally required web development skills—something many data analysts and scientists don’t typically have. In the past, even large media houses with dedicated teams would spend significant time and effort building a scrollytelling project. The tradeoffs were high, making it a less viable option for time-sensitive or resource-constrained projects.

For smaller teams or solo practitioners, this barrier has often made web-based storytelling feel out of reach. But that changes today. Thanks to the many developer communities, the barriers have been so significantly lowered that you can put up your scrollytelling project in a few hours, many of the times, without even needing to code! 

What You’ll Learn in This Tutorial
By the end of this tutorial, you’ll be able to build and deploy a fully functional data scrollytelling project—taking your insights beyond dashboards and onto the web!

**Here’s what you’ll learn:**
- How to set up your environment and craft your data story using the scrollytelling technique
- How to build your project locally and deploy it to the web for free using GitHub and Vercel

Don’t worry if this sounds new—we’ll walk through everything step by step, from scratch. Whether you're an absolute beginner or looking to sharpen your skills, you'll end up with a real, portfolio-ready project you can proudly share.

## Tools We’ll Be Using (50–100 words)
---
For this project, we’ll use the Closeread library to create our data scrollytelling experience. Closeread is a Quarto extension designed specifically for building interactive, scroll-based narratives. To use Closeread, you’ll need two key tools:
1. Quarto – an open-source publishing system that supports Python, R, Julia, and ObservableJS. It allows you to create dynamic, multi-format documents using Markdown, Jupyter Notebooks, or your preferred editor. Since Closeread is built on top of Quarto, installing Quarto is a necessary first step.
2. A Code Editor – This is where you’ll write and manage your project files. We’ll be using Visual Studio Code (VS Code) in this tutorial, but feel free to use alternatives like RStudio, Atom, or any editor that supports Quarto projects.

To get started, install Quarto from the official [Quarto website](https://quarto.org/docs/download/). Follow the standard installation process for your operating system. We'll also be using GitHub for version control and Vercel to deploy the final project to the web. Don’t worry—we’ll walk through setting up both platforms when the time comes.

Once you’ve installed Quarto, you’re ready to install the Closeread extension. We’ll cover that in the next section.