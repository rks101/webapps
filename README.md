# webapps
This repository is a compilation of useful information related to Web applications or Web development.   

* [webapps](#webapps)
    * [Know Elements](#know-elements) 
    * [HTML](#html) 
    * [CSS](#css) 
    * [JavaScript](#javascript) 
    * [Database](#database) 
    * [APIs](#apis)  
    * [Troubleshooting](#troubleshooting) 
    * [Security](#security) 
    * [Online Editors and Playgrounds](#online-editors-playgrounds) 
    * [Tools](#tools)
    * [Progressive Web Apps (PWA)](#Progressive-Web-Apps)
    * [Flavio Copes](#flavio-copes) 
    * [Free Code Camp](#free-code-camp) 
    * [Resources](#resources)
    * [Cool websites and apps](#cool-websites-and-apps)
    * [Lessons from Online Payment Gateways](#lessons-from-online-payment-gateways) 

## Know Elements 

[Understand boxes](https://every-layout.dev/rudiments/boxes/) where everything is a box on a web page. To confirm this, open a web page in a browser and then try to [inspect the elements](https://blog.hubspot.com/website/how-to-inspect) of the web page. Here is another link to [inspect the elements](https://www.elegantthemes.com/blog/wordpress/browsers-inspect-element-tool) for understanding CSS details or using device emulation to visualize content on different devices.     

----

## HTML    

[HTML tutorial on W3Schools](https://www.w3schools.com/html/)   

[CodePen](https://codepen.io/) and [JSFiddle](https://jsfiddle.net/) online playground for HTML.   

----

## CSS 

[Tailwind playground for CSS, try this](https://play.tailwindcss.com/) and [docs](https://tailwindcss.com/docs/)   

[Sample product/tool page](https://stupendous-lollipop-54242c.netlify.app/) uses HTML, Tailwind, Astro, Netlify-build, and GitHub repo.    

[CSS Specifications](https://www.w3.org/Style/CSS/specs.en.html)    

----

## JavaScript

[RunJS playground for JavaScript](https://runjs.app/) to check syntax and basic testing of the script.   

[Codepen](https://codepen.io/pen/) for side-by-side HTML, CSS, and Javascript editor windows to visualize code for web apps.   

JavaScript-based websites and web apps leverage JavaScript frameworks and some popular technology stacks. JavaScript frameworks do change pretty fast, and there is a new name very often!    
e.g., Node.js, Angular, Vue.js, Next.js, React, Svelte, etc. Because of these changes, stack shifts MEAN, MEVN, MERN, and others.      

### JavaScript frameworks 

[Next.js v/s React](https://snipcart.com/blog/next-js-vs-react)   

[JavaScript frameworks](https://snipcart.com/blog/javascript-frameworks)   

[Front End Javascript Framework - React, Angular or Vue](https://www.freecodecamp.org/news/front-end-javascript-development-react-angular-vue-compared/)   

----

## Database

[DB Playground to try some queries](https://www.db-fiddle.com/)   

[Railway.app](https://railway.app/) - simple to start PostgreSQL/MySQL/MongoDB instance in cloud in minutes.    

[PostGreSQL](https://pigsty.io/)    

----

## APIs

It has become imperative for developers to understand and design APIs to connect or integrate with so many other software or services.    

Here is an online book on [API-first world](https://api-first-world.com/) to emphasize API-first initiatives to produce and consume software and services. The way we consume APIs for bank payment gateways, online payments (UPI, stripe, etc.), and user messaging (SMS, Telegram, WhatsApp, etc.), for large software to survive with rapid changes in technologies, designers, and developers should pay attention to API-first approach if the software/service is online.    

[OpenAPI specification for RESTful APIs](https://swagger.io/resources/open-api/)    


----

## Troubleshooting 

[Can I use](https://caniuse.com/) - to see browser support for front-end web technologies. For example, look for [querySelector](https://caniuse.com/?search=querySelector)   

[Update node js version](https://phoenixnap.com/kb/update-node-js-version)  

[SSR web frameworks](https://simply-how.com/server-side-rendering-web-frameworks), [SSR with React](https://blog.openreplay.com/server-side-rendering-ssr-with-react), another [example](https://frontend.blog/building-an-ssr-framework-using-vite-prisma/)     

[Browser permissions](https://permission.site/) to simulate how the browser asks certain permissions courtesy to [Felt](https://adrifelt.github.io/demos/).   

----

## Security  

Pay attention to security aspects while you develop portals. Security of web applications should not be an afterthought or left to other teams. Utilize free tools and websites for OSINT or Web Intelligence (WebINT). These steps could improve the ranking of your websites/portals.     

Check your website's [HTTP response headers](https://securityheaders.com/), [TLS certificates (X.509)](https://censys.io/cert-hygiene-and-website-availability/), (vulnerable) libraries used, consider VAPT, etc.    

----

## Online Editors Playgrounds 

[Scratch](https://scratch.mit.edu/) - this should be encouraged before any programming   

[Tailwind playground for CSS](https://play.tailwindcss.com/)   

[RunJS playground for JavaScript](https://runjs.app/)   

[CodePen for HTML/CSS/JavaScript](https://codepen.io/pen/)   



[DB-Fiddle playground](https://www.db-fiddle.com/)   

[railway.app for DB in the cloud](https://railway.app/) - now it's paid   

[Online GDB](https://www.onlinegdb.com/) - good for C/C++    

[cplayground.com](https://cplayground.com/) - for C/C++, uses clang compiler front-end from LLVm project.   

[awesome online IDEs](https://github.com/styfle/awesome-online-ide)   


----

## Tools 

Learning multiple tools (like the Swiss Army Knife) is essential for web developers. They can improve productivity during the development.    

Some great tools I have come across recently:   

[Astro](https://astro.build/)    

[Open Source Form Builder Framework for Vue JS](https://vueform.com/)     

[VS Code for Code Editing](https://code.visualstudio.com/)   

[Netlify to deploy](https://www.netlify.com/) after pushing code from [github](https://github.com)    

[What technology is the website built with?](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/website-technology-checker-built-with-wappalyzer-lookup-identify-extension-chrome)     

----

## Progressive Web Apps (PWA)

[Progressive Web Apps examples](https://onilab.com/blog/20-progressive-web-apps-examples)    

----

## Virtual Hosts   

Web application servers can host multiple websites with different domain or sub-domain names. For this, they use virtual hosts. The web server checks the hostname requested from the HTTP headers and matches that against its virtual hosts. [Virtual hosts are just text-based configuration files](https://httpd.apache.org/docs/2.4/vhosts/examples.html). If it finds a match, the correct website will be provided. If no match is found, the default website will be provided instead.    

Note: Creating virtual host configurations on a web server does not create DNS entries for those host names. You must have or create the Address/CNAME records in DNS server resolving to the required IP address, or nobody else will be able to see your website.    

Virtual Hosts can have their root directory mapped to different locations on the server hard drive. For example, eg.com is mapped to /var/www/eg, egdev.com is mapped to /var/www/egdev and egsec.com is mapped to /var/www/egsec directory (for [Apache](https://httpd.apache.org/docs/2.4/vhosts/examples.html)/Nginx server). Several combinations are possible with IP, ports, name-based hosts, and URL redirects.     

There is no limit to the number of websites you can host on a web server.    

----

## Flavio Copes 

[Flavio Copes' website and online books](https://flaviocopes.com/)   

[Great Bootcamp for Full-Stack Web Developer](https://bootcamp.dev/)   

[The Valley of Code](https://thevalleyofcode.com/)     

----

## Free Code Camp

[Quincy Larsen's website](https://www.freecodecamp.org/) and check this out on [Responsive Web Design](https://www.freecodecamp.org/learn/responsive-web-design/)   

----

## Resources 

[The Missing Link - Web development and programming](https://milnepublishing.geneseo.edu/themissinglink/)    

[Some links on Low code, No code](https://github.com/zenitysec/awesome-low-code)   

[Examples of login forms](https://designmodo.com/login-forms-websites-apps/)    

----

## Cool Websites and Apps   

[We Present - Plastic Free](https://wepresent.wetransfer.com/stories/manifesto-plastic-free) or [how to publish a book](https://wepresent.wetransfer.com/stories/stuff-they-dont-tell-you-how-to-publish-a-book) - an elegant design with pictures and scroll. Zoom in a picture and play the slide show :)     

[Layoffs.fyi](https://layoffs.fyi) - see the airtable in action.    

[Simplify internship portal](https://simplify.jobs/l/Top-Fall-Internships) - a different grid/tiles for internships.     

[IGNCA website](https://ignca.gov.in/) - a trove of information for art lovers.   

[Cotton Bee](https://ctnbee.com/blog/en/) - notice the design elements in the slider, sidebars, highlight headings on hover, footer, etc.     

[Amazon dogs - liked the template page](https://www.aboutamazon.com/news/workplace/how-much-does-amazon-love-dogs-just-ask-one-of-the-8-000-pups-that-work-here)     

[Bathroom & Plumbing Glossary](https://www.qssupplies.co.uk/bathroom_help_center.asp) - I loved the simplicity of the glossary and the classified listing of items with a picture that anyone can understand.    

[Professor GEORGE PALLIS personal web page](http://www.cs.ucy.ac.cy/~gpallis/?section=1)    

[Jai Hind Project to celebrate Heros](https://jaihindproject.in/)    

----

## Lessons from Online Payment Gateways   


[Integrating bank payment gateway](https://subbuswaroop.com/integrate-icici-eazypay-payment-gateway-using-php/) and [PG kit page 7--13](https://bimtech.ac.in/Uploads/files/341Docverify1EazyPay_and_PG_Merchant_Integration_v4.3.pdf)    

[Stripe - integrate PG into website](https://stripe.com/in/resources/more/how-to-integrate-a-payment-gateway-into-a-website)    
