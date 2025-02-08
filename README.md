# INTRODUCTION:
EJS (Embedded JavaScript) is a simple templating engine used in JavaScript applications, particularly with Node.js, to generate dynamic HTML content. It allows developers to embed JavaScript logic directly within HTML templates, making it easier to build dynamic web pages.

## Key Concepts:

Template Rendering: EJS enables server-side rendering of HTML views, where data from the server (e.g., from a Node.js backend) is injected into HTML templates before sending the final page to the client.

Dynamic Content: You can pass variables, data, and logic like loops and conditionals directly inside the HTML, making the pages interactive and tailored to the user's needs.


# WHAT THE PROJECT DOES:

This simple website generates different brand names using EJS. This website not only consists of a frontend but a backend aswell. Node is the backend for this project.

# EJS TAGS USED:

1. Outputs the value of a JavaScript expression 
    
       - <%= %>
2. Outputs the value without escaping it (use carefully to avoid security risks).

        - <%- %>

3. You can embed JavaScript code for conditionals, loops, etc.

        - <% if (user.isAdmin) { %>

          <p>Welcome, Admin!</p>

          <% } else { %>

          <p>Welcome, User!</p>

           <% } %>

5. You can reuse components like headers, footers, or other templates using the <%- include() %> syntax.

         -<%- include('header') %>

          <h1>Welcome to the homepage</h1>

          <%- include('footer') %>

# Advantages of EJS:
1. Ease of Use: Simple syntax for embedding JavaScript in HTML.
2. Efficiency: Automatically escapes HTML to prevent security vulnerabilities.
3. Flexibility: Allows dynamic data to be rendered with JavaScript logic directly in templates.
4. Integrates Easily: Works seamlessly with Express, a popular Node.js framework

# FINAL OUTPUT:

To view the output of our website we used a localhost port 3000, where we can host our website locally all using backend Node. We just need to generate names and it automatically generate a new name for you.

![local1](https://github.com/user-attachments/assets/45dc5f77-20ae-4640-a21a-32efd4c1b1f4) 

![local2](https://github.com/user-attachments/assets/ac3b8d61-256c-4162-af3b-8e3e396a13e5)

![local3](https://github.com/user-attachments/assets/51b23924-f02f-4264-8fa9-7bfa2202bc41)

![local4](https://github.com/user-attachments/assets/da121eb4-3de8-4d76-b994-e800c8b5a13e)






