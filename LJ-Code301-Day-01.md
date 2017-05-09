# LJ Code 301 - Day 1

  Today I learned about MVC. This stands for Model, View and Controller. View
is the presentation and assets code. The controller receives, interprets and
validates content. The model store data, integrity, consistency queries and
mutations. Is a diagram on the way the user interacts with the web page. He
gives information, it is received and interpreted by the controller, then
stored by the model. Then fro the model goes back to the controller and Then
viewed by the user and the user interacts also with what he views. This is a
cycle.

  Another subject we covered is the responsive web design. This is a certain
numbers of commands that are done when the web page has certain changes. One of
this changes is in the size of the body. If it goes smaller than a certain
of pixels, it triggers instructions in CSS. We do this through the model
query.

@media screen and (min-width: 480px) {
    body {
        background-color: black;
    }
}

  In this case when the screen gos smaller than 480px, the background-color of
the body changes to black. 
