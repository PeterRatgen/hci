---
title: Exam Questions
author: 
  - Peter Heilbo Ratgen
date: \today
numbersections: true
---
# Exam questions

## Questions
  - What is Human Computer Interaction?
  - What is a Design Sprint?
  - What is User Testing?
  - What is Usability Testing?
  - How do you design for Accessibility?
  - What is SEO and how do you do it?
  - How does the MVC design pattern work?
  - What is Composite UI?
  - What is a microservice?
  - What languages does a browser understand?
    - En browser forstår \underline{kun} HTML, CSS og Javascript. Hvis det er
      noget end disse, for at en browser skal kunne forstå det, skal der
      oversættes til disse tre. 
  - What is a persona?
  - What is a map?
  - What is a storyboard?
  - What is a prototype?
  - What is skeumorphism

## Explain
  - HTML
    - HTML står for Hyper Text Markup Language. HTML definerer strukturen på
      hjemmesiden, og binder CSS og Javascript sammen. Når HTML er loaded laver
      den the Document Object Model (DOM), dette er denne som Javascript kan
      manipulere emner i.  HTML starter og slutter med \texttt{html} tags, dette
      er rodelement i DOMen. Og \texttt{head} indeholder den usynlige data så
      som \texttt{meta}-tags og \texttt{style}-tags.  \texttt{body} indeholder
      det man kan se. Man skal deklarere \texttt{<script/>}.

      På enhver side skal der være en header \texttt{<h1></h1>}. Man
      laver links med \texttt{<a></a}. Man inkludere billeder med
      \texttt{<img/}, her bruger man \texttt{src} til at indsætte sit billede.
      Det er \underline{meget} vigtigt at have en \texttt{alt} attribut, således
      at skærmlæsere kan læse hvad der står på siden.
  
      Et \texttt{div} tag er en block, et \texttt{span} tag er inline. Det vil
      sige at \texttt{div} skubber resten af indholdet ned på næste linje.
      \texttt{span} bliver dog på linjen (dette kan vi bruge fx. til at farve
      tekst).

  - CSS
    - CSS står for Cascading Style Sheets. CSS står for at style den struktur der
      er givet i HTML. Vi importerer CSS i \texttt{<head>} i HTML, vi kan også
      lave et HTML element der definerer en style for det ene HTML dokument. Vi
      kan også sætte style med \texttt{style=""} i HTML dokumentet.
        
      - Vi vælger DOM elementer med fx \texttt{h1}.
      - Vi vælger klasser med \texttt{.class (dot class)}
      - Vi vælger id'er med \texttt{\#id}  

      Specificity er det pointssystem der bestemmer hvilke værdier der gælder
      for et bestemt element. Der gives point i denne rækkefølge:
      - Element
      - Class/Pseudo-class attribut
      - ID
      - HTML Style attribute
      - \texttt{!important}

  - JavaScript
  - jQuery
  - Bootstrap
  - Leaflet
  - Google Charts
  - Bitmaps and Vector

## Talk about 
  - Graphic Design
  - Design Guidelines and Design Systems
