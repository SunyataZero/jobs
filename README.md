# [Jobs](http://opensourcedesign.net/jobs/)

The goal here is to create a proper **"job board"** that pairs open source people and projects in need design work with designers who can do those tasks.
It will be a mixture of *both gratis as well as paying work.*
A job can be relatively small task to an entire project.
I think the ideal balance would be a mixture of about:

* 25% small singular tasks
* 15% new or fork of an existing project
* 60% product / feature development on existing projects

*Note: this process is rough and a work in progress, please free to contribute ideas, approaches, and of course jobs :)*


### Submit a Job

Our job submission process is done **"in the open"** so if you work on an open source software project or community, feel free to submit a job to our job board. Just do the following:

**Easiest:**

1. [Click here to create a new file here on GitHub](https://github.com/opensourcedesign/jobs/new/gh-pages?filename=jobs/YYY-MM-DD-ChooseAJobTitle.md&value=---%0Alayout:%20jobs%0Atitle:%20Job%20Title%0Arole:%20Job%20Role%20%23%20Eg:%20Logo%20Designer,%20UX%20Designer%0Aorganization:%20Organization%20Name%0Agithub:%20github-username%0Acontact:%20email,%20github,%20irc%20channel,%20etc%0Acontributing_md:%20%28optional%29%20%0Acontributors_md:%20%28optional%29%20%0Aurl:%20http://organisation-website.com%0Atags:%20interface%20design,%20branding,%20logo%0Astatus:%20searching%20/%20%0Arate:%20gratis%20/%20$60%20hour%20/%20$1000%20total%20/%20etc...%0Adate_posted:%20yyyy-mm-dd%0A---%0AWrite%20the%20description%20of%20the%20job%20here.%20Keep%20each%20sentence%20on%20a%20new%20line,%20to%20make%20clean%20diff%20reviews.) (you need to be logged in to GitHub)
2. It will ask you to create a fork
3. Create a fork. Don't worry about what a fork is
4. Fill in the details of the form
5. Change the file name to something like `2015-03-12-sticker-design-for-fun.md`
5. Submit your pull request
6. Have a margarita or a hot chocolate

**Harder (this involves downloading the code on your computer):**

1. running `rake job title="Job Title" role="Role Name" org="Organization Name"`
2. Opening the file that got generated in `jobs` and filling it in.
3. Submit a pull request.
4. Have a margarita or a hot chocolate

**Hardest (a bit tedious):**

1. Fork the `jobs` repo
2. Copy `job-template.md` into the `jobs` folder and change the name
3. Name your copy something like `2015-03-12-sticker-design-for-fun.md` starting with date
4. Make sure there is a `.md` extension to the file you copied or it won't work
5. Fill out the fields inside the template you just copied
6. Submit a pull request
7. Have a margarita or hot chocolate

After those steps you will have submitted a job to the OSD job board, you rule ;)

### View OSD [job listings here](http://opensourcedesign.net/jobs/).

## "Meta" Tasks:

Anything related to improving OSD directly. Listed in order of attainability.

#### • Identity & Logo
OSD needs to craft an identity that is of the community and responds to the idea of open source in a clear, memorable way.
Maybe that means the logo is something that is continuously iterated on, maybe it is something that has a consistent form that responds to changes in the greater community/world.

#### • Project listing page
What projects are currently in need of completion?
The current solution has been to post each project as a github issue, which might be a good solution in the short term.
It might be better to have an ongoing list where designers can post and up-vote freely.

#### • A space on the web
http://opensourcedesign.net redirects to Github.
Would it meaningfully help the community to make a site with digests of all the repos?
