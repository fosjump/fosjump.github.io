### This is the very simple **FOS Jump** Generator

##### Why *FOS Jump* ?
Because findig how to be helpful in the Free/OpenSource comunity is still not straight forward.


##### Why the generator? 
Because other static web generators are too complex for need of the project.

### How to contribute to **FOS Jump** ?

Anyone can propose links to:

* FOS Projects with **good how-to-contribute readings**;
* Website that help finding projects FOS Projects to participate to;
* Videos about the subject;
* Or propose any other idea for improving this platform.

There are three main ways to proceed:

#### 1. Making a pull request ([github project]()).
The structure of the project is really simple:
* One python program to generate the website (in the *output* folder) using [jinja2](http://jinja.pocoo.org/) templating. 
* Jinja2 templates are in the *template* folder
* The *Data* folder contains the files you might want to eddit (please follow their simple format):
	* *projects.yml*: contains all the project links. Note that, if you add a project, you need to add an image for it.

		```yaml
			"ProjectName":
			    text: "that explains what the project is about"
			    linkName: "The button to clic"
			    linkURL: https://how.tojoin.the/project
			    image: imagename.jpg
		```	

	* *other.yml*: contains the other links and videos

		```yaml
			videos:
				"video name":
					link: http://the.link.to/it
			....
			interesting:
	    			"a Name": 
					text: " This link is supposed to help finding other Open Source projects to contribute to"
					link: https://the.actual.link/

		```
	* *contribute.md*: markdown content of contrib.html
		


#### 2. Via github issues: 
* Adding links by commenting to [newProjectLink issue](http://github.com/fos-contrib/fos-contrib.github.io/issues/projectLinks) or [otherLinks issue](https://github.com/SamyMe/FOSS-contrib/issues/2)
* Proposing a modification or something else by [creating a new issue](http://github.com/fos-contrib/fos-contrib.github.io/issues)

####3. Or sending an email to fosjump@tutanota.com (if you don't have a github account)


#### **IMPORTANT**: 
Only links to FOS projects that are new-commers-friendly are accepted in *the main list*. 

Any type of contribution is welcomed.

