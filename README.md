# SchoolListIt

### Covid-19 has put education at all levels into a tailspin
Many schools are not going back in a normal fashion this fall, many are using a blended remote/in person model, and some still have not finalized thier plans. Fully in-person attendance may not be sustainable in areas with continued outbreak. Many families are uncomfortable sending thier children into such uncertainty, and are opting out of public school and into homeschooling. 

This creates a particularly tough challenge for many families including 
- students with fewer choices
- lower income students with poor internet access 
- students in rural areas with poor internet access (many with little or no mobile coverage)
- dual income families
- single parent families

Parents need a solution that helps them oversee and monitor thier students' performance.

Teachers need streamlined communications with families.

Students need help staying on track with a wider sphere of support.

Newly homeschooling families need attendance, testing, and transcripts.

## SchoolListIt
### What is due and when for any school, anywhere no matter how you school

I am a working mom and I built SchoolListIt out of necessity. I have two school aged children and a job and a baby. I work from home. The daycare has closed, and fear of the virus prevents me hiring in-home childcare. Even with all this, I still need to help my students stay on track with schoolwork. This is not only my reality. I share this reality with much of America. 

Teachers rely on so many learning apps, but for a mom with multiple children that quickly compounds. Each child has multiple teachers with multiple apps and each school has different systems. It quickly turns into chaos. When remote learning began after Covid, I scoured the web for an app that could organize it all for me, but **there just isn't an app for that.**

### Instead of complaining, I went to work. SchoolListit is the result.

SchoolListIt is all about pulling it all togehter into one easily discernable format that parents, grandparents, and guardians from a wider variety of backgrounds can understand. 

SchoolListit is a free and open platform for parents, teachers, and anyone in a student’s support sphere. Instead of reinventing what teachers and schools are likely to use, I chose to build a react app that can feed from any existing system's data via REST API. 

The possibilities are endless when you approach a problem from an entirely new angle. I built SchoolListIt considering education from outside the classroom and outside the boardroom SchoolListIt pairs react with WordPress. Because even though we may not know exactly what we need today, **I’d bet there’s a plugin for that**. 

## The Platform
### A fresh approach

I approached this problem with only three constraints:
- Open Source
- Accesible
- Extensible

Pairing React with WordPress, we've set up a toolchain for integrating existing tools and making room for new solutions. During a global pandemic, it is ideal for local developers to build local solutions for local problems. WordPress brings with it one of the largest developer communites in the world, and REACT can integrate easily with any REST API. These are the exact right tools to **"bring it all together"**.

### Architecture
<img src="https://github.com/megphillips91/schlistit/blob/master/Architecture-02.png" alt="schoolistit architecture" width="100%"/>
__**this is just the beginning, where can we go from here?**__

### Roadmap of Core Tools
The principle of this platform is to provide a set of core tools to address the central common problems, and then provide documentation and developer resources so that those core tools can be easily and rapidly extended into specific use cases as needed.  

- SchoolListIt App: 
Front end user interface for parents, teachers, and students. 
(Demo live at SchoolListIt.com)

- SchoolListIt REST API: 
WordPress plugin that does the backend api work and serves data to the front end SchoolListIt Application. Free WordPress Plugin.
(Plugin live on SchoolListIt.com)

- SchoolListIt Website: SchoolListIt.com is the front-end of the WordPress site which runs the backend plugin. It is the marketing site for the platform.
(Live at schoolListIt.com)

- SchoolListIt AI: 
WordPress <=> IBM Watson AI and ML integration.
(In development - see repo)

- SchoolListIt Live Instruction:
WordPress <=> Zoom integration WordPress Plugin.
(In development - see repo)

- SchoolListIt Channel Changer:
Wordpress <=> Twilio integration. WordPress Plugin.
Streamlines communication for teachers and parents. 
(See Repo for details)

- SchoolListIt Tutor Marketplace
WooCommerce extension. Fork of Charter Boat Bookings Pro.
(See Repo for details)

# The Big Win

Even in normal school life, working parents have always struggled to help with schoolwork. SchoolListIt can give them a glimpse into the classroom they’ve just never had before, and with the largest community of developers in the world building into and outwardly from here, maybe Covid-19 can bring in an era of equal education.**

## License
[MIT](https://choosealicense.com/licenses/mit/)