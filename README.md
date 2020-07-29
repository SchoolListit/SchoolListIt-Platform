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

SchoolListIt is all about including more people.  Now, more than ever - It really does take a village. 

SchoolListit is a free and open platform for parents, teachers, and anyone in a student’s support sphere. Instead of reinventing what teachers and schools are likely to use, I chose to build a react app that can feed from any existing system's data via REST API. 

The possibilities are endless when you approach a problem from an entirely new angle. I built SchoolListIt considering education from outside the classroom and outside the boardroom SchoolListIt pairs react with WordPress. Because even though we may not know exactly what we need today, **I’d bet there’s a plugin for that**. 

## The Platform
### A fresh approach

I approached this problem from an entirely new angle beginning with only three constraints:
- Open Source
- Accesible
- Extensible

Pairing React with WordPress, we've set up a toolchain for integrating existing tools and making room for new solutions. During a global pandemic, it is ideal for local developers to build local solutions for local problems. WordPress brings with it one of the largest developer communites in the world, and REACT can integrate easily with any REST API. These are the exact right tools to "bring it all together".

**SchoolListIt is just the beginning, where can we go from here?**
### Architecture
<img src="https://github.com/megphillips91/schlistit/blob/master/Architecture-02.png" alt="schoolistit architecture" width="100%"/>

### Roadmap of Core Tools
The integrated core tools are the backbone keeping the platform aligned including:
- SchoolListIt App: 
Front end user interface for parents, teachers, and students. 
(Demo live at SchoolListIt.com)

- SchoolListIt REST API: 
WordPress plugin that does the backend api work and serves data to the front end SchoolListIt Application. Free WordPress Plugin.
(Plugin live on SchoolListIt.com)

- SchoolListIt Website: SchoolListIt.com is the front-end of the WordPress site which runs the backend plugin. It is the marketing site for the platform.
(Live at schoolListIt.com)

- SchoolListIt AI: 
WordPress - to - Watson AI and ML integration. WordPress Plugin.
(In development - see repo)

- SchoolListIt Live Instruction:
WordPress - to - Zoom integration WordPress Plugin.
(In development - see repo)

- SchoolListIt Channel Changer:
Wordpress - Twilio integration. Streamlines communication for teachers and parents. Teachers can send one comunication and reach parents where they are on the channel most comfortable for communication. Premium WordPress Plugin. This is a fork of other plugins I've built for marketing. I just neeed to pull it all together and rebrand.
(See Repo for details)

- SchoolListIt Tutor Marketplace
Fork of my Premium Charter Boat Bookings plugin - I just need to rebrand it as a tutor instead of a boat ;). A woocommerce extension which works in tandem with a set of Gutenberg blocks. The tutor would host the plugin and woocommerce on his/her site and exposes a functioning booking calendar to the REST API.
(See Repo for details)

- SchoolListIt Transcripts:
WordPress - Blockchain integration for transcripts and testing. 
(looking for the right integration)








Working parents have always struggled to help with schoolwork, but School-list-it can give them a glimpse into the classroom they’ve just never had before. 

**Who knows, maybe Covid-19 can bring in an era of equal education.**

SchoolListIt can facilitate equal education from outside the classroom during Covid-19 and after
because SchoolListit assumes the most challenging circumstances and degrades gracefully providing a consistent and understandable user experience that doesn’t have to change even with shifting circumstances.

In the worst connectivity scenario, our app can work offline and sync when connection is restored. We built the user experience for phones with an interface that mimics social media so that parents of all ages and aptitude can participate. 

Through SchoolListIt, we can push the effectiveness of in-home schooling regardless of Covid-19 and emerge as a society with better tools and better data to provide an equal education regardless of the circumstances children are living. 



**It takes a village**

Even in a normal school setting, we cannot ensure fair and equal education without including a student’s extended family and better understanding the challenges at home. In particular, single parent homes rely on a larger circle for help. However, only legal guardians have access to most student information systems. Our parents, friends, and neighbors cannot help if they cannot access what is due for schoolwork and when it is due.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)