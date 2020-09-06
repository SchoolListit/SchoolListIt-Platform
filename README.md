# SchoolListIt
[![SchoolListIt Platform](https://github.com/SchoolListit/SchoolListIt-Platform/blob/master/ToolChain.png)](https://www.youtube.com/watch?v=J5X4Rf9wys0)


(https://youtu.be/J5X4Rf9wys0)

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
<img src="https://github.com/SchoolListit/SchoolListIt-App/blob/master/Architecture-02.png" width="100%"/>
The SchoolListit platform is much more than just one application. The possibilities are endless when you approach a problem from a new angle. I designed SchoolListIt considering education from outside the classroom and outside the boardroom. SchoolListIt pairs React with WordPress because even though we may not know exactly what we need today, **I’d bet there’s a plugin for that**. 

In other words the global open source developer community can create plugins, npm packages, and add ons to rapidly and cost effectively meet the unexpected future needs of school systems. Private closed source proprietary solutions can never move as fast as a motivated open source community, and Covid-19 has shown us just how important is it for school systems to prepare for the unexpected. As an industry, we owe it to our children to facilitate and stimulate rapid development in this area lest we risk leaving children behind - **and that is unacceptable.**

### A fresh approach

I approached this problem with only three constraints:
- **Open Source:** the source code is made available for branching, forking, and modifying.
- **Accessibility:** careful attention to the user experience despite the user's physical or situational challenges
- **Extensible:** easily extended source code with clear standards for participating in an add-on marketplace

Pairing React with WordPress, we've set up a toolchain for integrating existing tools and making room for new solutions. During a global pandemic, it is ideal for local developers to build local solutions for local problems. WordPress brings with it one of the largest developer communites in the world, and REACT can integrate easily with any REST API. These are the tools that can **"bring it all together"** and provide a platform for rapid response to disruption in the education space.

### Roadmap
<img src="https://github.com/SchoolListit/SchoolListIt-Platform/blob/master/Roadmap.png" width="100%"/>

**Existing School Websites**
Many schools already have WordPress websites. The system is designed to include these existing websites as a "distributed backend" (i.e. each school's WordPress website could serve data). In this way, we naturally impart performance, scalability, and security into the SchoolListIt App. 

**Existing School Systems**
Google Classroom and the Blackboard suite maintain REST APis. Google has an existing and open api for this purpose and schools can easily grant access. I am not clear on whether Blackboard makes its REST API available to 3rd party solutions.

### Roadmap of Core Tools
**This is just the beginning, where can we go from here?**

The SchoolListIt platform provides a set of **core tools** that address central integrations, and provides documentation and developer resources so that those core tools can be easily and rapidly extended into specific use cases as needed. 

- [**SchoolListIt App:**](https://github.com/SchoolListit/SchoolListIt-App) Front end user interface for parents, teachers, and students. 
(Demo live at SchoolListIt.com)

- [**SchoolListIt REST API:**](https://github.com/SchoolListit/SchoolListIt-REST-Plugin) WordPress plugin that does the backend api work and serves data to the front end SchoolListIt Application. Free WordPress Plugin.
(Plugin live on SchoolListIt.com)

- [**SchoolListIt Website:**](https://schoolistit.com/) SchoolListIt.com is the front-end of the WordPress site which runs the backend plugin. It is the marketing site for the platform.
(Live at schoolListIt.com)

- [**SchoolListIt AI:**](https://github.com/SchoolListit/SchoolListIt-AI) WordPress <=> IBM Watson AI and ML integration. It reads aloud to students.
(In development - see repo)

- [**SchoolListIt Transcripts:**](https://github.com/SchoolListit/SchoolListIt-Transcripts) WordPress Plugin purpose built to maintain student transcripts secured with blockchain. Please follow the link to the ReadMe.  
(In development - see repo)

- **SchoolListIt Live Instruction:** WooCommerce extension for pairing tutors with student and/or student groups. Fork of Charter Boat Bookings Pro with integrated WordPress <=> Zoom integration. *This is not fresh code so I have not linked to that from here. Please dont disqualify me. I just want to give a whole picture of the roadmap...and how quickly this can come together.* 

- [**SchoolListIt Channel Changer:**](https://github.com/SchoolListit/SchoolListIt-Channel-Changer) Wordpress <=> Twilio integration. WordPress Plugin.
Streamlines communication for teachers and parents. 
(In development - See Repo for details)

- **SchoolListIt App Marketplace:** For clarity, I've included this here, but we will use an existing Woocommerce Premium Extension maintained by Automattic to facilitate this marketplace. We can always customize it to our needs later if neccesary. 

- **SchoolLIstIt Integrations:** Starting with Google Classroom, it is our plan to build api integration with existing systems so that assignments and due dates can be pulled from API as part of Teacher verification.

**Overcoming Integration Roadblocks**

The strategy to overcome potential roadblocks to integration is simple. As user adoption grows, any misinformation posted on SchoolListIt is going to cause a huge headache for teachers and schools. Just as businesses appreciate the opportunity to manage their Google Places profile, teachers will find it very useful to integrate directly with SchoolListIt rather than having parents manually disseminating information throughout the community. Imagine crowd sourced school assignment information, posts, comments, and Q&A. As soon as we gain traction and significant user adoption, schools will want to integrate.

**Self Hosting**

SchoolListit can be used either as part of the SchoolListit.com community or by self hosting. If you choose to self host, you will need to host a WordPress Site on your maindomain. Then, set up a subdomain for the React App. 

Depending on your hosting, you may need to manage other records such as an .htaccess file to redirect for the router to work properly and you will need to go into the react app and change the endpoints to your top level domain istead of schoollistit.com. If you are implementing, please feel free to reach out to [megphillips91](https://github.com/megphillips91) with questions.

# The Big Win

Even in normal school life, working parents have always struggled to help with schoolwork. SchoolListIt can give them a glimpse into the classroom they’ve just never had before, and with the largest community of developers in the world building into and outwardly from here -- 

## Together we can bring a new era of equal education. ##

# Monetization Strategies
Since there are different user scopes within SchoolListit, we consider monetization strategies on several levels. 
- School Administration
- Teachers
- Parents

Within each of the user scopes, we follow the same monetization strategy and approved ecosystem developers can publish premium plugins for each user scope. The key strategy lies within how we implement the "premium" features. After careful consideration, it becomes clear that premium features are best serviced inside of a instance of a customized and very limited version of the WP Admin Dashboard. This can be easily accomplished by creating a custom user role and capabilities for each of the three user types. 

### Here is how that will work:
SchoolListit App will offer these premium features within the proper user scope. A user can initiate a premium account by requesting access to any of the premium features at which time a few things will happen:
1. User will be offered a selection of domains, and will be redirected to SchoolListit.com with a few url parameters
2. SchoolListit.com will add the product to the cart and redirect the user to the checkout page
3. If the user does not already have a SchoolListIt Website on record, a cloud instance of WP will be instantiated with the SchoolListit Core stack of Theme + plugins using the domain selected.
4. Once created, the premium plugin will be installed, activated, and the license key will be stored within the wp_options table and the premum plugin will be activated programatically. 
5. User will be redirected to the premium plugin admin menu and placed on the "how to" page which will have a video welcoming the user to thier new SchoolListit website and showing them how to use the new feature they purchased. 
6. The suite of plugins will be stacked on top of the core plugins as "add ons" which require the suite of core plugins to function. 

# License
[MIT](https://choosealicense.com/licenses/mit/)
