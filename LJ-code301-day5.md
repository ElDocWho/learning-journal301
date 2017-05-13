# LJ Code 301 - Day 4

  This day we learned about HandlebarsJS. Handlebars are considered a logic-less
templating engine that has the capacity of dynamically generate an HTML page.

This is the way we load them into the browser:

         <script src="/path/to/handlebars.min.js"></script>

**Templates** can be written both in the HTML file or separately. In the first case, they appear inside the <script> tag with a type="text/x-handlebars-template" attribute and an ID. The variables are written in double curly braces {{}} and are known as expressions.
Here is an example:

  <script id="handlebars-demo" type="text/x-handlebars-template">
    <div>
      My name is {{name}}. I am a {{occupation}}.
    </div>
  </script>

source: https://www.sitepoint.com/a-beginners-guide-to-handlebars/

# LJ Code 301 - Day 5

  Today we learned how to apply handlebars to forms. The make it easier to send
the information that is collected from a form to the DOM easier.
