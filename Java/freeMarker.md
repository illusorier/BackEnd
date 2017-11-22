        <html>
            <head>
              <title>Welcome!</title>
            </head>
            <body>
              <h1>Welcome ${user}!</h1>
              <p>Our latest product:
              <a href="${latestProduct.url}">${latestProduct.name}</a>!
            </body>
        </html>
        
The template is stored on the Web server, usually just like the static HTML page 

Templates are in fact programs you write in a language called **FTL** (for FreeMarker Template Language).

This is a quite simple programming language designed for writing templates and nothing else.

A template (=FTL program) is a mix of the following sections:

- **Text**: Text that will be printed to the output as is.

- **Interpolation**: These sections will be replaced with a calculated value in the output.

- **FTL tags**:

- **Comments**: