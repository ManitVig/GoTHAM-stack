## GoTHAM-stack

A tech stack for creating modern web applications in the simplest way possible. 

## What is GoTHAM?

GoTHAM stands for Go, Tailwind, HTMX, AlpineJS and MySQL/MariaDB/MongoDB. It is a tech stack designed to build modern, performant and scalable web applications using the principle of K.I.S.S (Keep It Simple, Stupid). It combines technologies which are easy to learn, implement and integrate together while also being performant enough for most web development needs, thus providing both an enjoy-able developer experience and an admirable user experience.

## Why GoTHAM?

It is my personal opinion that web development has gotten a lot more complicated than it needs to be. The current status quo of using frameworks/libraries like React/NextJS, Angular, Vue, Sveltekit etc. and all the complexities that those bring along, might be necessary and thus worth it for some applications, but I feel for most web apps I feel that the original notion of server rendered multipage applications was right, though I would agree providing an user experience expected of web apps in the modern age (Post-React) would require some additions and tweaks to the original MPA paradigm. Hence, for all the developers that agree with me, I present my solution: GoTHAM.

1. **Go** (https://go.dev/): I chose Go or Golang (if you prefer),  as the foundation general purpose language for my tech stack because -


- **Speed and Performance:**  Go compiles directly to machine code, making it fast and efficient. This is especially beneficial for building high-performance backend applications.
    
-   **Concurrency Made Easy:** Go excels at handling concurrent tasks. Features like goroutines (lightweight threads) and channels facilitate communication between these tasks, simplifying the development of scalable applications.
    
-   **Readability and Simplicity:** Go prioritizes code clarity. Its syntax is clean and straightforward, making it easier to learn and maintain codebases compared to more complex languages.
    
-   **Open-Source and Community:** Go is open-source with a thriving community. This translates to readily available libraries, helpful forums, and a growing pool of Golang developers.
    
-   **Growing Demand:** Go's popularity is on the rise. It's becoming a sought-after skill for programmers, potentially leading to better job prospects.

- **Best Standard Library:** Go's standard library is absolutely legendary, it provides almost common functionalities and then some. For many projects, including http webservers I think the packages provided by the go standard library are more than enough for a good developer experience and performance.

2. **Tailwind** (https://tailwindcss.com/): In one sentence, TailwindCSS is the simplest method for styling web pages and components, which is also tried and tested. But if you need more than one sentence or are not familiar with tailwindcss -

- **Speedy Development:**   Tailwind's core concept is utility-first. It provides a massive collection of pre-defined CSS classes for styling elements. This eliminates the need to write a lot of custom CSS, significantly accelerating the development process.
    
-   **Enhanced Maintainability:** Since everyone on a project uses the same pre-defined utility classes, enforcing a consistent style throughout the codebase becomes easier. This improves code readability and maintainability in the long run.
    
-   **Highly Customizable:** Don't be fooled by the utility-first approach. Tailwind allows extensive customization. You can configure the framework through a configuration file to tailor colors, spacing, fonts, and more to your specific design needs.
    
-   **Reduced CSS Bloat:** Traditional CSS can become cluttered with unused styles over time. Tailwind has a feature called "purge unused styles" that automatically removes unnecessary styles from the final CSS file, keeping your codebase clean and lean.
    
-   **Responsive Design Made Easy:** Tailwind offers a comprehensive set of utility classes specifically designed for responsive web design. You can easily control the look and feel of your website across different screen sizes.
    
-   **Works Seamlessly with Other Tools:** Tailwind integrates well with popular front-end frameworks like React, Vue.js, and vanilla JavaScript. This flexibility allows you to use it alongside your preferred development tools.
    
-   **Active Community and Support:** Tailwind boasts a large and active community of developers. There's a wealth of resources available online, including extensive documentation and tutorials, for learning and troubleshooting.

3. **HTMX** (https://htmx.org/): if you haven't heard of HTMX, it is a new approach to adding server-client interactivity to web apps without having to write a single line of JS. It is a JS library that allows web elements to communicate with the servers and update the DOM using a HTML-first approach i.e. the communication and update logic is all based on special HTML attributes and thus there is minimal to no need of JS. Here's a simple rundown of what it offers - 


-  **Focus on HTML:** Htmx leverages the power of HTML for rendering and leverages attributes to define how and where to fetch new content from the server. This approach reduces the need for extensive JavaScript for basic interactions.
    
-   **Partial Updates:** Htmx excels at updating portions of a webpage dynamically, in response to user actions. This avoids full page reloads, resulting in smoother and faster user experiences.
    
-   **Minimal Code:** Compared to traditional JavaScript-heavy frameworks, Htmx requires less code to achieve similar interactive features. This can simplify development and maintenance.
    
-   **AJAX with Ease:** Htmx provides attributes for making AJAX requests directly from HTML elements. You can specify the HTTP verb (GET, POST, etc.) and the URL for fetching data, simplifying communication with the server.
    
-   **CSS Transitions:** Htmx integrates with CSS transitions to add animations during content updates. This enhances the visual appeal and user experience of your web application.
    
-   **Beyond Basic Interactions:** While Htmx focuses on simplifying common interactions, it also offers features like WebSockets and Server Sent Events for more advanced real-time communication.

4. AlpineJS (https://alpinejs.dev/) - Modern web applications not only rely on server-client interactivity but also have a lot of client  side only interactive parts. AlpineJS is a minimal JS library which provides the simplest way to bring your web apps to life on the client side - 

- **Reduced Bundle Size:** Unlike some larger frameworks, AlpineJS doesn't require a complex build process or transpilation. This translates to a smaller bundle size, leading to faster page load times.
    
-   **Focus on HTML:** Similar to Htmx, AlpineJS leverages HTML as the primary structure for your web pages. Directives enhance HTML elements with dynamic behavior, promoting clean and readable code.
    
-   **Reactive By Design:** AlpineJS incorporates a built-in reactivity system. This means that changes in your data are automatically reflected in the UI, simplifying the development process.
    
-   **Event Handling:** AlpineJS provides directives for handling various user interactions like clicks, form submissions, and more. This allows you to add dynamic behavior to your web pages without writing extensive JavaScript code.
    
-   **Data Binding:** AlpineJS directives enable two-way data binding between your data and HTML elements. This simplifies keeping your UI and data in sync.
    
-   **Conditional Rendering:** You can use directives to conditionally show or hide content based on your data or user interactions. This allows for creating dynamic and responsive user interfaces.
    
-   **Community and Ecosystem:** While AlpineJS itself is small, it benefits from a growing community and ecosystem. There are various community-built components and libraries available to extend its functionality.

5. **MySQL/MariaDB/MongoDB**: I wanted to have some flexibility in the options for choosing a database for the GoTHAM stack as I believe the use-case of the app determines what kind of database would be optimal and these three are all tried and tested options. 

## Who is GoTHAM for?

Anyone who wants to build a web app whether you are  beginner who is just starting and looking for a simple entry-point before moving on to more complex parts of web dev or a industry expert who justs wants a simpler life free of all JS framework shenanigans. Though, before beginning with the GoTHAM stack it would be recommended (though not necessary) to have some knowledge and little experience of working with the Go programming language.

## Example Apps/Resources for Getting Started

Currently there are no specific resources for getting started with the GoTHAM stack. For the time being the best option is to research about and learn the individual components separately from resources available for them on youtube, their respective webpages or elsewhere on the internet.

I have some stuff in the works related to GoTHAM stack and I will add link them here when they are ready to be public. Community input is also highly encouraged if anyone has some projects based on the technologies of GoTHAM and would like them to featured here please raise an issue on this github repo and I'll be sure to respond.
