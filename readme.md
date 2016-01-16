# Inspect an element's HTML

Make it possible to view the HTML for a given page element by simply adding 
the `inspect-html` attribute: 

    <div inspect-html>
      <div>reusable html component</div>
    </div>

Helps support code reuse and consistent formatting, making it ideal for theming 
and sample pages. 

Inspired by the [Bootswatch](http://bootswatch.com/) theming website.



# Install

Installing via bower:

    bower install torbensko/angular-inspect-html


## Development

Install

    npm install
    bower install

Build the CSS

    grunt

Run server

    node demo.js