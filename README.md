CMPUT404-assignment-ajax
==============================

CMPUT404-assignment-ajax

See requirements.org (plain-text) for a description of the project.

Make a shared state AJAX drawing program

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.
- Modifications by Yonael Bekele to original [found at https://github.com/abramhindle/CMPUT404-assignment-ajax] 
  - Completed unfinished functions in server.py 
  - Added javascript to index.html 
    - Changed colours and radius of objects 
    - Added a happy face with one eye so it looks like lasers are shooting out 
    - Use function (provided by original) JSONXMLHTTPRequest to send data to draw on next frame
    
Collaborators
========================
- Advice given to me by ahersi2
    
Resources
==============================
- https://stackoverflow.com/questions/7907596/json-dumps-vs-flask-jsonify
  - Answer by Kenneth Wilke helped explain what jsonify does and what it returns properly ( "flask.Response()") 
- https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/send
  - How to send POST through XMLHttpRequest 
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes#Moving_the_pen
  - How to Draw a Happy face
- https://owlcation.com/stem/HTML5-Tutorial-Drawing-Circles-and-Arcs
  - How to draw a PacMan face. (later abondoned idea but it is commented out in the code)
- http://webdocs.cs.ualberta.ca/~hindle1/2014/CMPUT404-AJAX-Slides/
  - As a resource suggested by Abram Hindle if we use XMLHttpRequests
