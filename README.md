# [Symfony Live - London 2013](http://london2013.live.symfony.com/) talks

- All talks are in **english**.
- Comment and rate talks on [joind.in](https://joind.in/event/Symfony-Live-London)

## Avoiding the mud

<dl>
  <dt>Description</dt>
  <dd>It’s easy to get started on an application with Symfony2 and its ecosystem creating bundle and mapping entities to forms and to a database to create a prototype. The problem is growing it beyond this to create a maintainable application. With simple entity mapping exposing the data it contains business logic quickly ends up spread around the application. We can end up with a tangle of business logic and a large tangle of related entities. We may have multiple bundles but they are often dependent on each other. Code which may be useful in other applications becomes tangled up with the application specific code.</dd>
</dl>

[Slides](https://speakerdeck.com/richardmiller/avoiding-the-mud-symfony-live-london)  
~~Video~~

By [Richard Miller](https://connect.sensiolabs.com/profile/mr_r_miller)  
![github](icon/github.png) [@richardmiller](https://github.com/richardmiller)  
![twitter](icon/twitter.png) [@mr_r_miller](https://twitter.com/mr_r_miller)

---

## Build your first Symfony2 application

<dl>
  <dt>Description</dt>
  <dd>During this tutorial, you will get started with the Symfony2 framework, and build your first web application using the framework. We'll cover installation, configuration, bundles, controllers, working with the database and forms during this tutorial, and if we have some time left, we can go beyond those basic topics as well.</dd>
</dl>

[Slides](https://speakerdeck.com/skoop/build-your-first-symfony2-application-symfony-live-london-2013)  
[Video](https://youtu.be/OdtvmcNJIH4)

By [Stefan Koopmanschap](https://connect.sensiolabs.com/profile/skoop)  
![github](icon/github.png) [@skoop](https://github.com/skoop)  
![twitter](icon/twitter.png) [@skoop](https://twitter.com/skoop)

---

## The HttpKernelInterface is a lie

<dl>
  <dt>Description</dt>
  <dd>You thought that you need to rewrite your whole application to use HttpFoundation in order to benefit from HttpKernelInterface functional testing? This talk will explore the evolution of HTTP abstractions. We will take a look at inetd at the TCP level, CGI and FCGI at the HTTP level, language level abstractions like Rack for Ruby and WSGI for Python. Finally we will arrive at the Symfony2 HttpKernelInterface. The PHP community can take many ideas from Rack. We should be building composable stacks of re-usable middlewares. Which opportunities are lurking in the HttpKernelInterface? Is it really a lie?</dd>
</dl>

[Slides](https://speakerdeck.com/igorw/the-httpkernelinterface-is-a-lie-london)  
[Video](https://youtu.be/QY8mL6WARIE)

By [Igor Wiedler](https://connect.sensiolabs.com/profile/igorw)  
![github](icon/github.png) [@igorw](https://github.com/igorw)  
![twitter](icon/twitter.png) [@igorwhilefalse](https://twitter.com/igorwhilefalse)

---

## A year with Symfony2

<dl>
  <dt>Description</dt>
  <dd>In the autumn 2012 Powwownow decided to adopt Symfony2 as their framework of choice. This talk describes why we made that choice, the experience we had learning and adopting the framework, the challenges we overcame and the practices we have adopted. If you have recently started using Symfony2 or are considering adopting it, this talk should help you clear a path through the forest of newness.</dd>
</dl>

[Slides](https://speakerdeck.com/fazy/a-year-with-symfony-2)  
[Video](https://youtu.be/KynEyVuAg0c)

By [Lars Janssen](https://connect.sensiolabs.com/profile/lars)  
![github](icon/github.png) [@fazy](https://github.com/fazy)  
![twitter](icon/twitter.png) [@fazy](https://twitter.com/fazy)

---

## Integrating Drupal 8 into Symfony2

<dl>
  <dt>Description</dt>
  <dd>Drupal 8 is now introducing more and more Symfony2 components into its architecture. This will make it possible to use Symfony2 paradigms when building custom modules in Drupal 8. But what if you want to go further and include a standard Drupal 8 inside a Symfony2 project? This presentation shows how to do it in a step-by-step approach and gives more generic advice on how to wrap php application inside a Symfony2 application.</dd>
</dl>

[Slides](http://slideshare.net/fabrice.bernhard/integrating-drupal-8-into-symfony-2)  
~~Video~~

By [Fabrice Bernhard](https://connect.sensiolabs.com/profile/fabriceb)  
![github](icon/github.png) [@fabriceb](https://github.com/fabriceb)  
![twitter](icon/twitter.png) [@fabriceb](https://twitter.com/fabriceb)

---

## Using PhpSpec to build quality into a Symfony app

<dl>
  <dt>Description</dt>
  <dd>SpecBDD is the inner loop of Behavior Driven Development. Working on the code level, it's the Test Driven Development redefined. PhpSpec, being a SpecBDD tool, aims on ensuring the internal quality of an application. It makes the test-first approach a lot easier by supporting the developer at every step, almost suggesting next actions to take. Its revolutionary approach makes that once you triedPhpSpec, there's no way back. During the talk I will introduce you to PhpSpec and show how to use it to drive the design and improve the quality of a Symfony application.</dd>
</dl>

[Slides](https://speakerdeck.com/jakzal/using-phpspec-to-build-quality-into-a-symfony-app)  
[Video](https://youtu.be/zSrwu0uQ1VQ)

By [Jakub Zalas](https://connect.sensiolabs.com/profile/jakubzalas)  
![github](icon/github.png) [@jakzal](https://github.com/jakzal)  
![twitter](icon/twitter.png) [@jakub_zalas](https://twitter.com/jakub_zalas)

---

## The Framework as an implementation detail

<dl>
  <dt>Description</dt>
  <dd>What would your application look like if it were written by the people who write the testing frameworks? If unit tests make classes more modular, by forcing you to test it in isolation, then what is the effect of expanding this to a less granular level, the acceptance and functional test. The more modern application architecture evolves, the more we hear the very old patterns being rediscovered and re-adopted. 1979 Trygve's MVC is a classic example, so are the SOLID principles. In this talk we will look on how Symfony allows for a really decoupled, easy to test application, by following on the footsteps of Alistair Cockburn's hexagonal architecture.</dd>
</dl>

[Slides](http://slideshare.net/marcello.duarte/the-framework-as-an-implementation-detail)  
[Video](https://youtu.be/0L_9NutiJlc)

By [Marcello Duarte](https://connect.sensiolabs.com/profile/md)  
![github](icon/github.png) [@MarcelloDuarte](https://github.com/MarcelloDuarte)  
![twitter](icon/twitter.png) [@_md](https://twitter.com/_md)

And [Konstantin Kudryashov](https://connect.sensiolabs.com/profile/everzet)  
![github](icon/github.png) [@everzet](https://github.com/everzet)  
![twitter](icon/twitter.png) [@everzet](https://twitter.com/everzet)

---

## Transforming a legacy PHP application using Symfony2 and Varnish

<dl>
  <dt>Description</dt>
  <dd>The careerswales.com platform manages the education and professional progression of millions of people in Wales. When challenged with upgrading its ageing application stack to suit modern standards, we devised a solution with Symfony2 at its core. In this talk I'll discuss how the new stack was implemented, focussing on how we took advantage of Symfony2's first-class support for reverse-proxy Varnish to phase the deployment of the new system and improve performance by a significant amount. I'll also talk about the API we created to bridge its SQL Server / MySQL database platforms, and how Symfony2 was used to provide a single-sign-on solution across all of its web applications.</dd>
</dl>

[Slides](http://slideshare.net/craigmarvelley/transforming-legacy-php-applications-with-symfony2-and-varnish)  
[Video](https://youtu.be/g2f_BzKrpaU)

By [Craig Marvelley](https://connect.sensiolabs.com/profile/craigmarvelley)  
![github](icon/github.png) [@craigmarvelley](https://github.com/craigmarvelley)  
![twitter](icon/twitter.png) [@craigmarvelley](https://twitter.com/craigmarvelley)

---

## Building Better Developers

<dl>
  <dt>Description</dt>
  <dd>Nothing stands still in this industry: new language features in your weapon of choice, nginx gaining ground on Apache, yet another standard you should be adhering to, cloud hosting services making deployment as easy as "git push"… the list goes on. What can you do to make sure that you're keeping up with all these changes without cloning yourself and only sleeping 3 hours a week? It's not just about improving your coding skill, it's understanding how to make all your abilities and those of your peers work together to keep you ahead of the game. We'll look at a combination of human hacks and hard work to help fine tune the most important machine you own.</dd>
</dl>

[Slides](https://speakerdeck.com/rowan_m/building-better-developers-1)  
[Video](https://youtu.be/WTLqfIjJFEI)

By [Rowan Merewood](https://connect.sensiolabs.com/profile/rowan_m)  
![github](icon/github.png) [@rowan-m](https://github.com/rowan-m)  
![twitter](icon/twitter.png) [@rowan_m](https://twitter.com/rowan_m)

---

## Extract till you drop

<dl>
  <dt>Description</dt>
  <dd>We’ve all seen them: applications that got out of control. Under the pressure of deadlines and endless change requests, with the weight of years of legacy, the code has become unmaintainable. Adding features is a slow hit and miss process. Everybody knows something needs to be done, but nobody knows how. To change the code safely, you need tests, but to make it testable, you need to change it. Rebuilding the system from scratch is not an option. There’s good news: With the right tools, techniques, and mindset, any codebase can be brought under test, and be refactored towards a better architecture. All without affecting the behavior of the system, and allowing the business to continue. This presentation is not for the weak of heart. We’ll skip the theory and dive straight into the spaghetti code. Dependencies will be broken; designs will be messed up before they get better; fat controllers will mercilessly be put on a diet. It’s live coding, and it may fail. But it will change how you approach legacy code forever.</dd>
</dl>

[Slides](http://verraes.net/2013/09/extract-till-you-drop/)  
[Video](https://youtu.be/DCvDF0lbCbc)

By [Mathias Verraes](https://connect.sensiolabs.com/profile/mathiasverraes)  
![github](icon/github.png) [@mathiasverraes](https://github.com/mathiasverraes)  
![twitter](icon/twitter.png) [@mathiasverraes](https://twitter.com/mathiasverraes)

---

## Silex: From micro to full-stack

<dl>
  <dt>Description</dt>
  <dd>Silex is a micro framework for PHP. Join this session for an introduction to Silex and ﬁnd out how to leverage Silex for your next application. We will start with the basics of a Silex application and explore how Silex can be evolved into a full-stack framework for advanced applications. Not sure about when to use components, Silex, or Symfony? Join this session and ﬁnd out!</dd>
</dl>

[Slides](http://slideshare.net/dustin.whittle/silex-from-micro-to-full-stack)  
[Video](https://youtu.be/6U6RmtHxV9g)

By [Dustin Whittle](https://connect.sensiolabs.com/profile/dustinwhittle)  
![github](icon/github.png) [@dustinwhittle](https://github.com/dustinwhittle)  
![twitter](icon/twitter.png) [@dustinwhittle](https://twitter.com/dustinwhittle)

---

## Xdebug for Symfony Developers

<dl>
  <dt>Description</dt>
  <dd>He has contributed in a number of ways to the PHP project, including the Xdebug debugging tool, and various extensions and additions. He's a frequent lecturer at conferences, the author of php|architect's Guide to Date and Time Programming, and the co-author of PHP 5 Power Programming. He is now working at 10gen to work on the PHP driver for MongoDB. This session teaches you how to detect and debug Symfony based applications with the free open source tool Xdebug, which is an extension to PHP. The first part will quickly show how to get started with Xdebug. The second part of the session will cover detecting problems in your application by showing how Xdebug provides debugging aides in the form of stack/function traces, dumps of variables, and modified PHP functions. In the last part I will show the remote debugger capabilities of Xdebug with different IDEs, where you can: set breakpoints on functions, methods and file/line combinations and evaluating error messages. On top of this you will also see how you can use Xdebug's profiler to find bottlenecks in your applications. All using a Symfony application as example.</dd>
</dl>

~~Slides~~  
[Video](https://youtu.be/SUHYPt0hANE)

By [Derick Rethans](https://connect.sensiolabs.com/profile/derickr)  
![github](icon/github.png) [@derickr](https://github.com/derickr)  
![twitter](icon/twitter.png) [@derickr](https://twitter.com/derickr)

---

## Integrating Drupal 8 into Symfony2

<dl>
  <dt>Description</dt>
  <dd>Drupal 8 is now introducing more and more Symfony2 components into its architecture. This will make it possible to use Symfony2 paradigms when building custom modules in Drupal 8. But what if you want to go further and include a standard Drupal 8 inside a Symfony2 project? This presentation shows how to do it in a step-by-step approach and gives more generic advice on how to wrap php application inside a Symfony2 application.</dd>
</dl>

[Slides](http://slideshare.net/fabrice.bernhard/integrating-drupal-8-into-symfony-2)  
[Video](https://youtu.be/o7_PX3PkVb8)

By [Fabrice Bernhard](https://connect.sensiolabs.com/profile/fabriceb)  
![github](icon/github.png) [@fabriceb](https://github.com/fabriceb)  
![twitter](icon/twitter.png) [@fabriceb](https://twitter.com/fabriceb)

---

## Expression Language in Symfony 2.4

<dl>
  <dt>Description</dt>
  <dd>In my mind, Symfony 2.4 was a transition release, where our focus would be on stabilizing and polishing existing features. And that's what we did during the first 3 months. But unexpectedly, it turned out that Symfony 2.4 is going to have a major new feature that is going to be a game changer as it is going to enhance the developer experience on so many levels. What is it? An Expression Language. Come and learn everything about this new component and its integration into the service container, the security layer, the routing system, and the validation component.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.sensiolabs.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

---

---

### They wrote about the talks

- on [deeson.co.uk](https://www.deeson.co.uk/blog/symfony-live-london-%E2%80%93-september-20th-2013) by [Annika Clarke](https://connect.sensiolabs.com/profile/annikaclarke)
- on [studio24.net](http://www.studio24.net/blog/symfony-live-london/) by [Simon R Jones](https://connect.sensiolabs.com/profile/simonrjones)
