---
layout: post
title: 'Projects Portfolio: Blancarré Watches virtual shop'
date: 2018-03-25
excerpt: "development of a tailormade 360° & VR ready interactive shop for a Swiss watchmaker"
feaure: https://cdn-images-1.medium.com/max/1800/1*SCNnf1S4CI19sUAd5dG-4A.png
project: true
tags: [english, digital, 360, VR, portfolio]
---

# Projects portfolio
## Blancarré Watches
#### Role: Project manager - Period: 07.2017 – 03.2018

Blancarré is a young Swiss made watches manufacturer founded by Nicolas Mertenat, former lead designer at Omega and other watchmakers (see [founder's interview](https://www.youtube.com/watch?time_continue=1&v=FhHxM7p89N8) and [press coverage](http://blancarre.com/shop/content/11-presse)).  

*This article was first drafted as a project wrap up after project handover in March 2018 and was also [published on Medium](https://medium.com/@Romain_Marchand/projects-portfolio-blancarr%C3%A9-virtual-shop-9875abc69832) in a much detailed and imaged version.*

#### Context
Founder's vision is to use the most of newest digital technologies to leverage his product presence and corporate identity and stand out from other watchmakers.  

An external digital agency was initially contracted to design a tailormade interactive shop featuring watches products range as interactive elements and embedded videos of receptionnist and watchmaker at work to make the user feel just like in a traditional shop through a unique user experience. 
After several months of development between 2015 and 2016, their former supplier went extinct and left the project with unfinished materials and elements and a heavy code database with multiple errors. Overall, a broken prototype. 

Then came my mission to take over everything from scratch, analyse the feasibility and cost to put the project back on track, deliver a properly streamlined database and a working prototype, and *de facto* save my customer's initial consquent investment. The integration into [Blancarré's website](http://www.blancarre.com/landing/fr/index.html) would later on be made in collaboration with Blancarré's renowned digital agency [Openroom](https://www.openroom.ch/home).

![watch model render before 360 plugin](https://cdn-images-1.medium.com/max/720/1*_zpMcRQrjiQq9SfkTVisgA.png)   
*Example of a watch model elements before 360° slider process*

#### Hands-on: approach & main achievements:

This project was very different from the 360° interactive virtual tours I usually create ([such as this](https://www.tourmake.it/de/tour/f41a67a2761ed41b84806b991b31431e)), since instead of shooting actual DSLR pictures, stitching them into 360x180 panos (process I detailed [in this article](https://medium.com/@Romain_Marchand/publication-google-street-view-trusted-que-se-passe-til-apr%C3%A8s-le-shooting-8b5417ce0307)) and then develop interactive content based on the existing Google Streetview tour through an external platform, here the Blancarré shop physically doesn't exist at all. Hence everything has been digitally created from scratch. The shop is a 3D modelled room with product displays and reception desk, later on colourised and completed with 360° elements and embedded video content.

- **Think out of the box**: 
instead of first going to a developer, since database was sent to me "as is", I started by studying the project and the data for dozen of hours to deeply understand the conception model
- **Technical analysis**: 
I executed a local prototype and sort of performed *reverse-engineering* to analyse the database and lying underground technologies (WebGL, HTML5, JS, KRpano) and relevant plugins (e.g. 360 slider JS, mobile/desktop compatibility, etc)
- **Customer requirements & specifications writing**: 
identify and list all corrections to bring, submit them to the customer and translate them in specifications for the developer (...)
- **Specialist sourcing**: 
(...) then identify and source the relevant developer able to work with both web & VR/3D technologies 
- **Improved communication**: 
setup a permanent and open communication channel between the customer, the developer and myself, to improve productivity and issue response time and speed up integration and development through fast integration of customer feedbacks
- **Quality & Customer satisfaction**: 
delivered a working project, with an error-free code and a smoother database radically lightened from 7.4Go to 960Mo. Overall self-satisfaction to come out of this technically challenging project (at least for me) with honours.

![blender view virtual shop structure](https://cdn-images-1.medium.com/max/900/1*EamYQTMdmkp5ZvNF_E6V6w.png)
*Shop structure view in Blender*

#### Technical environment and methodologies:

- **web technologies**: WebGL, HTML5, CSS, jQuery libraries, JS plugins (such as [ThreeSixty slider](https://github.com/creativeaura/threesixty-slider)), WebM, etc
- **multiple softwares**: Blender (3D design), Photoshop, KRpano / Panotour Pro (virtual tour development), Hugin (panoramic image assembler), develope mode web browser
- Sort of **Agile XP methodology** (Extreme Programming)-like product management: with customer implication and cost reduction in mind, and code review > test > continuous conception and simplicity phases

![inside blancarré shop embed video](https://cdn-images-1.medium.com/max/900/1*ONDRAdlr4Gj0NCJBnMvhIQ.png)
*Both the receptionist and the watchmaker behind are distinct videos frames shot separately, then embedded into the final rendering*

