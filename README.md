# SchoolListIt

### Covid-19 has education at all levels in a tailspin
Many schools are not going back in a normal this fall, many are using a blended remote/in person model, and some still have not finalized thier plans. Fully in-person attendance may not be sustainable in areas with continued outbreak. Many families are uncomfortable sending thier children into such uncertainty, and are opting out of public school and into homeschooling. 

This creates a particularly tough challenge for many families including 
- students with fewer choices
- lower income students with poor internet access 
- students in rural areas with no internet service provider (many with little or no mobile coverage)
- dual income families
- single parent families

Parents need a solution that helps them oversee and monitor their students' performance.

Teachers need streamlined communications with families.

Students need help staying on track with a wider sphere of support.

Families new to Homeschooling need mentoring, attendance, testing, and transcripts.

## SchoolListIt
### What schoolwork is due and when, for any school, anywhere...

### No matter how you school

As a working mom, I built SchoolListIt out of necessity. I have two school aged children, a job, and a toddler. Like many others since Covid-19, I work from home. Daycare is either closed or not feasible, and fear of the virus prevents hiring in-home childcare. Successfully keeping my students on track with schoolwork became full time. It is confusing and frustrating for families like mine, but nearly impossible for single parent families.

Teachers rely on many learning apps, but for a mom with multiple children that quickly compounds. Each child has multiple teachers using multiple 'Apps' and each school has different systems and methods of communication. Many school districts have 'banded' grades so each child goes to a different school. This quickly turns into chaos. 

When remote learning began after Covid, **I scoured the web for an App that could organize the chaos, but unbelievable there is not an app for that.**  

### Instead of complaining, I created [SchoolListit](https://github.com/SchoolListit/SchoolListIt-App).

SchoolListIt pulls it all together into one easily discernable format that parents, grandparents, and guardians from a wider variety of backgrounds can understand. Whether fully in school, fully remote, blended, or homeschool - parents balancing work and life need 'at a glance' access to which school assignments are due and when - right on thier phones, organized by child, and checked off as complete - that is exactly what the SchoolListIt App does. 

SchoolListit is a free and open web application for parents, teachers, and anyone in a student’s support network. Instead of reinventing what teachers and schools are likely to use, **SchoolListIt is a React App** that can feed from any existing system's data via REST API, and programattically consolidate diverse learning tools in one place. It can **work offline** and **mimics a social media platform** so parents and grandparents are already accustomed to the navigation and features. 

[*follow this link to the README on the SchoolListIt App*](https://github.com/SchoolListit/SchoolListIt-App)

## The SchoolListIt Platform
The SchoolListit platform is much more than just one application. The possibilities are endless when you approach a problem from a new angle. I designed SchoolListIt considering education from outside the classroom and outside the boardroom. SchoolListIt pairs React with WordPress because even though we may not know exactly what we need today, **I’d bet there’s a plugin for that**. 

In other words the global open source developer community can create plugins, npm packages, and add ons to rapidly and cost effectively meet unexpected future needs of school systems. Private closed source proprietary solutions can never move as fast as a motivated open source community, and Covid-19 has shown us just how important is it for school systems to prepare for the unexpected. As an industry, we owe it to our children to facilitate and stimulate rapid development in this area lest we risk leaving children behind - **and that is unacceptable.**

### A fresh approach

I approached this problem with only three constraints:
- **Open Source:** the source code is made available for branching, forking, and modifying.
- **Accessibility:** careful attention to the user experience despite the user's physical or situational challenges
- **Extensible:** easily extended source code with clear standards for participating in an add-on marketplace

Pairing React with WordPress, we've set up a toolchain for integrating existing tools and making room for new solutions. During a global pandemic, it is ideal for local developers to build local solutions for local problems. WordPress brings with it one of the largest developer communites in the world, and REACT can integrate easily with any REST API. These are the tools that can **"bring it all together"** and provide a platform for rapid response to disruption in the education space.

### Architecture
<img src="https://github.com/megphillips91/schlistit/blob/master/Architecture-02.png" alt="schoolistit architecture" width="100%"/>

**Existing School Websites**
Many schools already have WordPress websites. The system is designed to include these existing websites as a "distributed backend" (i.e. each schools WordPress website would serve the data). In this way, we naturally impart performance, scalability, and security into the SchoolListIt App. 

**Existing School Systems**
Google Classroom and the Blackboard suite maintain REST APis, but both would need to grant api permissions to SchoolListit. Google has an existing and open api for this purpose and schools can easily grant permissions. I am not clear on whether Blackboard makes its REST API available to 3rd party solutions.

### Roadmap of Core Tools
**This is just the beginning, where can we go from here?**

The SchoolListIt platform provides a set of **core tools** that address central integrations, and provides documentation and developer resources so that those core tools can be easily and rapidly extended into specific use cases as needed. 

- [**SchoolListIt App:**](https://github.com/SchoolListit/SchoolListIt-App) Front end user interface for parents, teachers, and students. 
(Demo live at SchoolListIt.com)

- [**SchoolListIt REST API:**](https://github.com/SchoolListit/SchoolListIt-REST-Plugin) WordPress plugin that does the backend api work and serves data to the front end SchoolListIt Application. Free WordPress Plugin.
(Plugin live on SchoolListIt.com)

- [**SchoolListIt Website:**](https://schoolistit.com/) SchoolListIt.com is the front-end of the WordPress site which runs the backend plugin. It is the marketing site for the platform.
(Live at schoolListIt.com)

- [**SchoolListIt AI:**](https://github.com/SchoolListit/SchoolListIt-AI) WordPress <=> IBM Watson AI and ML integration.
(In development - see repo)

- [**SchoolListIt Live Instruction:**](https://github.com/SchoolListit/SchoolListIt-Live-Instruction) WooCommerce extension for pairing tutors with student and/or student groups. Fork of Charter Boat Bookings Pro with integrated WordPress <=> Zoom integration.
(In development - see repo)

- [**SchoolListIt Channel Changer:**](https://github.com/SchoolListit/SchoolListIt-Channel-Changer) Wordpress <=> Twilio integration. WordPress Plugin.
Streamlines communication for teachers and parents. 
(See Repo for details)

- **SchoolListIt App Marketplace:** For clarity, I've included this here, but we will use an existing Woocommerce Premium Extension maintained by Automattic to facilitate this marketplace. We can always customize it to our needs later if neccesary. 

- [**SchoolLIstIt Integrations:**](https://github.com/SchoolListit/SchoolListIt-Integrations) Starting with Google Classroom, it is our plan to build api integration with existing systems so that assignments and due dates can be pulled from API as part of Teacher verification. 

**Overcoming Integration Roadblocks**

The strategy to overcome potential roadblocks to integration is simple. As user adoption grows, any misinformation posted on SchoolListIt is going to cause a huge headache for teachers and schools. Just as businesses appreciate the opportunity to manage their Google Places profile, teachers will find it very useful to integrate directly with SchoolListIt rather than having parents manually disseminating information throughout the community. Imagine crowd sourced school assignment information, posts, comments, and Q&A. As soon as we gain traction and significant user adoption, schools will want to integrate.

# The Big Win

Even in normal school life, working parents have always struggled to help with schoolwork. SchoolListIt can give them a glimpse into the classroom they’ve just never had before, and with the largest community of developers in the world building into and outwardly from here -- 

## Together we can bring a new era of equal education. ##

# License
[MIT](https://choosealicense.com/licenses/mit/)
