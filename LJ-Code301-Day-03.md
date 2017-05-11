# LJ Code 301 - Day 2

  Main thing we learned on day 2 is how to manipulate the DOM through JQuery. Here are some examples of
the main commands we use:

**MANIPULATION**
 Using .clone() has the side-effect of producing elements with duplicate id attributes, which are supposed to be unique. Where possible, it is recommended to avoid cloning elements with this attribute or using class attributes as identifiers instead.
The syntax is as follow:

$( ".crazy" ).clone().appendTo( ".cool" );

**TRAVERSING**
 When a CSS selector string is passed to .filter(), text and comment nodes will always be removed from the resulting jQuery object during the filtering process. When a specific node or array of nodes are provided, a text or comment node will be included in the resulting jQuery object only if it matches one of the nodes in the filtering array.
The syntax is as follow:

$( "li" ).filter( ":even" ).css( "background-color", "red" );

(source: https://oscarotero.com/jquery/).

# LJ Code 301 - Day 3

  There are shorthand methods for some events such as .click() that can be used to attach or trigger
event handlers. The main method we did was .click().
  An important part of the events are the mouse vents, here is the most common used mouse events:

  **Mouse Events**
  .click()
  .contextMenu()
  .dblclick()
  .hover()
  .mousedown()
  .mouseenter()
  .mouseleave()
  .mousemove()
  .mouseout()
  .mouseover()
  .mouseup()

  The proper syntax to use and .on():

  $( "#dataTable tbody" ).on( "click", "tr", function() {
  console.log( $( this ).text() );
});
