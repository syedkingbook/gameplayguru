# How to setup a static website on GitHub
Setting up a static website in GitHub covers the following stages:
1.	Setup basic website configuration	
2.	Configure site-wide appearance using _Config.yml yaml file
3.	Setup the index.md file
4.	Create the first blog post using Markdown


**Explained below are the stages in detail:**

**Setup basic website configuration**

1.	Log in to GitHub. 
![login](./images/static_website/login.png)
 
5.	Click + and select **New repository**. 
![New repository](./images/static_website/newrepository.png)

 
6.	In the New repository page, enter the name of the new repository. 
![Repository name](./images/static_website/repositoryname.png)
 
7.	If you want to make the new static website visible to all, select the Public radio button. 
8.	Scroll down the page and select the Add a README file check box. 
![Read me](./images/static_website/publicreadme.png)
 
9.	Click Create repository. The new website appears. 
![New Website](./images/static_website/new_static_website.png)
 
10.	To setup GitHub Pages, select the Settings tab. 
![Code go](./images/static_website/code.png)
 
11.	In the left navigation pane of the Settings page, navigate to the Pages option.
![Pages go](./images/static_website/pages.png)
 
12.	 In the Pages page, click the Branch drop-down menu and select the branch main.
![Main](./images/static_website/branchmain.png)
 
13.	 In the next option, select the root folder. 
![Root](./images/static_website/root.png)
 
14.	Click Save. At this page, the setup shows README. 
![New Website](./images/static_website/newwebsitecreated.png)
 
15.	In the Pages page, you can find the website link.
![Code again](./images/static_website/codeagain.png)
 
16.	In the tab bar, select <> Code. 
17.	Click the settings icon in the right pane. 
![Predescription](./images/static_website/predescription.png)
 
18.	Enter Description and Website details.
![Description](./images/static_website/description.png)
 
The details appear. 
![Post description](./images/static_website/postdescription.png)
 


**Create and configure the _Config.yml file**
1.	To go to the new repository you created, select the new repository in the home page. 
![Home page all](./images/static_website/all_in_one_homepage.png)
 
2.	In the new repository page, select the Plus icon and select Create new file. 
![Create New file](./images/static_website/new_web_homepage.png)
 
3.	In the create new file page, enter _Config.yml in the box and then click outside the box. 
![Config yaml](./images/static_website/configyml.png)
 
4.	Enter the configuration details. A sample is below:
> # Site settings
>title: A one stop shop for technical documentation
>author:
 > name: NAME
 > email: EMAIL ADDRESS
>description: Where action and documentation meet
> # Build setting
> remote_theme: jekyll/minima
![Updated Config yaml](./images/static_website/updateconfigyml.png)
 
5.	Click Commit changes. 
6.	In the Commit changes window that appears, enter the following details:
a.	Commit message
b.	Extended description
c.	Commit directly to the main branch
7.	Click Commit changes. The details appear as below. 
![Repository name](./images/static_website/repositoryname.png)
 

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
![Index page layout](./images/static_website/index_pg_lyout.png)
 
4.	Click Commit changes on the right. 
5.	In the Commit changes window, enter:
a.	Commit message 
b.	Description 
6.	Click Commit changes.
![Commit](./images/static_website/commit1.png)
 
The details appear. 
![Post commit](./images/static_website/post_commit.png)
  

**Create the first blog post using Markdown**
1.	In the new repository, click Add file.
2.	Click Create new file.
![Pre post](./images/static_website/pre_post.png)

3.	In the file name field, enter _posts/. A new folder with the name _posts is created.   
![Post](./images/static_website/posts.png)
 
4.	Enter the blog file name in the format: yyyy-mm-dd-filename.md
![Post draft](./images/static_website/posts_draft1.png)
 
5.	Enter the blog details and content as shown below for instance.   
[---]   
[layout: post]   
[title: "My first blog"]   
[categories: misc]   
[---]   
Welcome to the world of technical documentation.
6.	Click Commit changes...
7.	Enter relevant details and click Commit changes. 
![Commit draft](./images/static_website/commit_blog1.png)
 
8.	The blog is listed as shown below for instance. 
![Blog prepare](./images/static_website/blogprepare.png)
 
9.	In the new repository home settings page, click the website link. 
![Blog ready](./images/static_website/blogready.png)
 