# How to set up a static website on GitHub
Setting up a static website in GitHub covers the following stages:
1.	Setup basic website configuration	
2.	Configure site-wide appearance using _Config.yml yaml file
3.	Setup the index.md file
4.	Create the first blog post using Markdown



**Explained below are the stages in detail:** 

**Setup basic website configuration**

1.	Log in to GitHub. 
![login](gameplayguru/assets/login.png)
 
5.	Click + and select **New repository**. 
![New repository](assets/images/newrepository.png)

 
6.	In the New repository page, enter the name of the new repository. 
![Repository name](./assets/images/repositoryname.png)
 
7.	If you want to make the new static website visible to all, select the Public radio button. 
8.	Scroll down the page and select the Add a README file check box. 
![Read me](./assets/images/publicreadme.png)
 
9.	Click Create repository. The new website appears. 
![New Website](./assets/images/new_static_website.png)
 
10.	To setup GitHub Pages, select the Settings tab. 
![Code go](./assets/images/code.png)
 
11.	In the left navigation pane of the Settings page, navigate to the Pages option.
![Pages go](./assets/images/pages.png)
 
12.	 In the Pages page, click the Branch drop-down menu and select the branch main.
![Main](./assets/images/branchmain.png)
 
13.	 In the next option, select the root folder. 
![Root](./assets/images/root.png)
 
14.	Click Save. At this page, the setup shows README. 
![New Website](./assets/images/newwebsitecreated.png)
 
15.	In the Pages page, you can find the website link.
![Code again](./assets/images/codeagain.png)
 
16.	In the tab bar, select <> Code. 
17.	Click the settings icon in the right pane. 
![Predescription](./assets/images/predescription.png)
 
18.	Enter Description and Website details.
![Description](./assets/images/description.png)
 
The details appear. 
![Post description](./assets/images/postdescription.png)
 


**Create and configure the _Config.yml file**
1.	To go to the new repository you created, select the new repository in the home page. 
![Home page all](./assets/images/all_in_one_homepage.png)
 
2.	In the new repository page, select the Plus icon and select Create new file. 
![Create New file](./assets/images/new_web_homepage.png)
 
3.	In the create new file page, enter _Config.yml in the box and then click outside the box. 
![Config yaml](./assets/images/configyml.png)
 
4.	Enter the configuration details. A sample is below:
> # Site settings
>title: A one stop shop for technical documentation
>author:
 > name: NAME
 > email: EMAIL ADDRESS
>description: Where action and documentation meet
> # Build setting
> remote_theme: jekyll/minima
![Updated Config yaml](./assets/images/updateconfigyml.png)
 
5.	Click Commit changes. 
6.	In the Commit changes window that appears, enter the following details:
a.	Commit message
b.	Extended description
c.	Commit directly to the main branch
7.	Click Commit changes. The details appear as below. 
![Repository name](./assets/images/repositoryname.png)
 

**Setup the index file**
1.	In the new repository home settings page, click +. 
2.	Select Create new file.
3.	In the new file page, enter the following details.
a.	In the file name field, enter index.md.
b.	In the content box, enter the following details:
> [---]  
> [layout: home]  
> [---]  
> [Welcome to the new blog!]  
> [Note: The welcome note is optional. You can choose whatever you want if > you want to have one.]  
![Index page layout](./assets/images/index_pg_lyout.png)
 
4.	Click Commit changes on the right. 
5.	In the Commit changes window, enter:
a.	Commit message 
b.	Description 
6.	Click Commit changes.
![Commit](./assets/images/commit1.png)
 
The details appear. 
![Post commit](./assets/images/post_commit.png)
  

**Create the first blog post using Markdown**
1.	In the new repository, click Add file.
2.	Click Create new file.
![Pre post](./assets/images/pre_post.png)

3.	In the file name field, enter _posts/. A new folder with the name _posts is created.   
![Post](./assets/images/posts.png)
 
4.	Enter the blog file name in the format: yyyy-mm-dd-filename.md
![Post draft](./assets/images/posts_draft1.png)
 
5.	Enter the blog details and content as shown below for instance.   
[---]   
[layout: post]   
[title: "My first blog"]   
[categories: misc]   
[---]   
Welcome to the world of technical documentation.
6.	Click Commit changes...
7.	Enter relevant details and click Commit changes. 
![Commit draft](./assets/images/commit_blog1.png)
 
8.	The blog is listed as shown below for instance. 
![Blog prepare](./assets/images/blogprepare.png)
 
9.	In the new repository home settings page, click the website link. 
![Blog ready](./assets/images/blogready.png)
 
