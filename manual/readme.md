

# Using CSS with a User Interface

CSS is a simple pod and ID provider, it doesn't has an UI.

But it is possible to "plug" an UI to penny through the creation
of a "recipe"

A recipe design a configuration file for CSS profite from
CSS components.js extenssibility

To use it with a UI, two options are available:
 - create a custom "recipe" ( need def. ) with an integrated UI
 - use the UI as an external app


## external VS internal UI

- UI and CSS under same URL

- Doesn't work out of the box. Need to create a new "recipe" to integrate the UI to CSS 


### UI external app

A few app are available to explore the content:

![[edit](./assets/fig_0.jpg?edit)](./assets/fig_0.jpg)

  - Penny:
    - inspect data, modify, add and delet
    build as a developper tools for debuggin[https://forum.solidproject.org/t/new-developer-tool-app-penny/3837]
    but suitable for standard use

    https://gitlab.com/vincenttunru/penny
    https://penny.vincenttunru.com/


  - PodBrowser
    - inspect data, modify, add and delet
    - + contacts & bookmarks

    https://github.com/inrupt/pod-browser
    https://pod-browser.vercel.app/


   - solidos
    - inspect data, modify, add and delet
    - contacts
    - + task management
    - + chat
    - + public profile page
    - + host a static homepage
     NSS default front end
     lot's of UI issue raised in github
     currently rebuilding the UI

    https://github.com/solid/solidos
    https://solidos.solidcommunity.net/

   - oh-my-pod ( unmaintained since dec. 2020 )
    - inspect data, modify, add and delet
    - contact
    - profile page
    https://ohmypod.netlify.com/
    https://github.com/empathyco/solid-oh-my-pod

  - https://gitlab.com/angelo-v/pod-homepage

TODO: get ligne of code of each project

### Integrated UI

 - penny 
