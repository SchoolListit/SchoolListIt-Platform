# SchoolListIt

### Covid-19 has education at all levels in a tailspin
Many schools are not going back in a normal this fall, many are using a blended remote/in person model, and some still have not finalized thier plans. Fully in-person attendance may not be sustainable in areas with continued outbreak. Many families are uncomfortable sending thier children into such uncertainty, and are opting out of public school and into homeschooling. 

This creates a particularly tough challenge for many families including 
- students with fewer choices
- lower income students with poor internet access 
- students in rural areas with poor internet access (many with little or no mobile coverage)
- dual income families
- single parent families

Parents need a solution that helps them oversee and monitor their students' performance.

Teachers need streamlined communications with families.

Students need help staying on track with a wider sphere of support.

Families new to Homeschooling need attendance, testing, and transcripts.

## SchoolListIt
### What (School Assignments) are due and when, for any school, anywhere, no matter how you school

As a working mom and I built SchoolListIt out of necessity. I have two school aged children, a job, and a baby. Like many now, I work from home. Daycare is either closed or not feasible, and fear of the virus prevents hiring in-home childcare. Successfully keeping my students on track with schoolwork is overwhelming. Maintaining and improving Education in this new Reality is of utmost importance. 

Teachers rely on so many learning apps, but for a mom with multiple children that quickly compounds. Each child has multiple teachers using multiple 'Apps' and each school has different systems. This quickly turns into chaos. When remote learning began after Covid, I scoured the web for an 'App' that could organize it all for me, but **there just isn't an app for that.**  

### Instead of complaining, I created [SchoolListit](https://github.com/SchoolListit/SchoolListIt-App).

SchoolListIt pulls it all together into one easily discernable format that parents, grandparents, and guardians from a wider variety of backgrounds can understand. Parents balancing work and life need 'at a glance' access to which school assignments are due and when - right on thier phones, organized by child, and checked off as complete - that is exactly what the SchoolListIt App does. [*follow this link to the README on the SchoolListIt App*](https://github.com/SchoolListit/SchoolListIt-App)

SchoolListit is currently a free and open platform for parents, teachers, and anyone in a student’s support network. Instead of reinventing what teachers and schools are likely to use, SchoolListIt is a React App that can feed from any existing system's data via REST API, and programattically consolidate diverse learning tools in one place. 

The possibilities are endless when you approach a problem from a new angle. I designed SchoolListIt considering education from outside the classroom and outside the boardroom. SchoolListIt pairs React with WordPress. Because even though we may not know exactly what we need today, **I’d bet there’s a plugin for that**. 

In other words the global open source developer community can rapidly create plugins, npm packages, and add ons to more rapidly and more cost effectively meet unexpected future needs of school systems. Private closed source proprietary solutions can never move as fast as a motivated open source community, and Covid-19 has shown us just how important is it for school systems to prepare for the unexpected. As an industry, we owe it to our children to facilitate and stimulate rapid development in this area lest we risk leaving children behind - And that is unacceptable.

## The Platform
### A fresh approach

I approached this problem with only three constraints:
- **Open Source:** the source code is made available for branching, forking, and modifying.
- **Accesible:** careful attention to the user experience regardless of the user's physical or situational challenges
- **Extensible:** easily extended source code with well documented standards for adding features

Pairing React with WordPress, we've set up a toolchain for integrating existing tools and making room for new solutions. During a global pandemic, it is ideal for local developers to build local solutions for local problems. WordPress brings with it one of the largest developer communites in the world, and REACT can integrate easily with any REST API. These are the tools that can **"bring it all together"** and provide a platform for rapid response to disruption in the education space.

### Architecture
<img src="https://github.com/megphillips91/schlistit/blob/master/Architecture-02.png" alt="schoolistit architecture" width="100%"/>

**Existing School Websites**
Many schools already have WordPress websites. The system is designed with the consideration of using these existing websites as a "distributed backend" (i.e. each schools WordPress website would serve the data) This is a way that we naturally impart performance, scalability, and security into the front end user experience. 

**Existing School Systems**
Google Classroom: the googleapis provides api access to all the data needed for the SchoolListIt app. Each GSuite for Ed would need to grant api permissions to SchoolListit.

### Roadmap of Core Tools
**This is just the beginning, where can we go from here?**

The principle of this platform is to provide a set of core tools to address the central integrations, and then provide documentation and developer resources so that those core tools can be easily and rapidly extended into specific use cases as needed. Many school websites worldwide are already built on WordPress.

- **SchoolListIt App:** Front end user interface for parents, teachers, and students. 
(Demo live at SchoolListIt.com)

- **SchoolListIt REST API:** WordPress plugin that does the backend api work and serves data to the front end SchoolListIt Application. Free WordPress Plugin.
(Plugin live on SchoolListIt.com)

- **SchoolListIt Website:** SchoolListIt.com is the front-end of the WordPress site which runs the backend plugin. It is the marketing site for the platform.
(Live at schoolListIt.com)

- **SchoolListIt AI:** WordPress <=> IBM Watson AI and ML integration.
(In development - see repo)

- **SchoolListIt Live Instruction:** WooCommerce extension. Fork of Charter Boat Bookings Pro with integrated WordPress <=> Zoom integration.
(In development - see repo)

- **SchoolListIt Channel Changer:** Wordpress <=> Twilio integration. WordPress Plugin.
Streamlines communication for teachers and parents. 
(See Repo for details)

- **SchoolListIt App Marketplace:** For clarity, I've included this here, but we will be using an existing Woocommerce Premium Extension which is maintained by Automattic to facilitate this marketplace. If we find need for additional features we can always customize it to our needs. 

- **SchoolLIstIt Integrations Plugin:** Starting with Google Classroom, it is our plan to build api integration with existing systems so that assignments and due dates can be pulled from API as part of Teacher verification. There are other systems which also use REST API including the seven Blackboard Bundled apps, and while these REST API exist, we would need permission to access before programmatic integration is possible. The strategy to overcome this potential roadblock is simple - teachers will demand integration - even

# The Big Win

Even in normal school life, working parents have always struggled to help with schoolwork. SchoolListIt can give them a glimpse into the classroom they’ve just never had before, and with the largest community of developers in the world building into and outwardly from here, **maybe Covid-19 can bring a new era of equal education.**

## License
[MIT](https://choosealicense.com/licenses/mit/)
