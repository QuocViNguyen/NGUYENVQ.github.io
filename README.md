# How to Host Your Resume on GitHub Pages
---
### **Intention**
The purpose of creating this instruction file is to help people who have very little or some experience with GitHub, to host their resume online using a **markdown editor**, **Jekyll** and a built-in GitHub's feature - **GitHub Pages**. To do so, a provided instruction set of the process of making it will be shown step by step in below sections. This instruction is most suitable for people who have limited experience in hosting/formatting resumes online. In this instruction file, I will also explain my choices are Jekyll, Markdown and GitHub Pages using Andrew Etter’s word in his book: **Modern Technical Writing**. To be more specific, I will use a Jekyll template with theme completely supported by GitHub Pages.

---
### **Prerequisites**
Before stepping into this tutorial, there several requirements:
* A complete, up-to-date resume (online or hard copy)
* A GitHub account. If you don't have one, simply create it by [Join GitHub](https://github.com/join)
* Basic knowledge of markdown language ( GitHub Flavoured Markdown(GFM) preffered) If you are new to markdown language, then check out this [GitHub markdown guide](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown).
* A markdown editor: [dillinger.io](https://dillinger.io/) and [Visual Studio Code](https://code.visualstudio.com/) are great choices.
* Basic knowledge of Jekyll. For more information, check out [Jekyll Tutorial](https://www.youtube.com/watch?v=T1itpPvFWHI&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)

---
### **Choices Jekyll provides**
With Jekyll, we have 3 basic options:
* Build a website from scratch like the tutorial in the given link above
* Use GitHub Pages's [existing Jekyll themes](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-with-the-theme-chooser#adding-a-theme-with-the-theme-chooser) (very simple and limited).
* Fork a completely template supported by GitHub Pages and then modify it

In this instruction file, I will show you how to get it done with the third option since it is a not-much-more complex but much more interesting approach to using Jekyll.

---
### **Demo**
![demo](https://github.com/QuocViNguyen/quocvinguyen.github.io/blob/master/images/demo.png) 

---
### **Hosting Resume on GitHub Pages (Using supported template by GitHub Pages)**
#### 1. Locate a Jekyll template with theme completely supported by GitHub Pages
Search for templates with theme completely supported by GitHub Pages, then select favourite template, and locate it on GitHub. In this case, I will use [James Grant's template](https://github.com/sproogen/modern-resume-theme). 
![Locate Theme](https://github.com/QuocViNguyen/quocvinguyen.github.io/blob/master/my_gifs/locate_theme.gif)

#### 2. Fork the template's repository
Fork the repository by clicking on the <mark>Fork</mark> option on the upper right hand side of the page. 

![Fork Click](https://raw.githubusercontent.com/LearnFrontEnd/fork-me/master/img/fork_click.gif)

#### 3. Rename the forked repository 
Rename it by clicking on Settings --> the firstt option should be Repository Name
![Rename](https://github.com/QuocViNguyen/quocvinguyen.github.io/blob/master/my_gifs/rename.gif)

#### 4. Modify yml file to add resume content
Step in and modify the front matter and add your resume content. In the repository, locate to <mark>_data</mark> folder. In there, you will see 3 exisiting files: **education.yml, experience.yml, projects.yml**. Click on education.yml to open it for editing. 

In education.yml file, edit your resume content follows the format given. My recommendation is to copy that sample code block, paste it, then comment out the sample block, then modify the pasted block. Continue doing so for experience.yml & projects.yml to modify your experience and project sections.

![edit data](https://github.com/QuocViNguyen/quocvinguyen.github.io/blob/master/my_gifs/edit_data.gif)

#### 5. Edit Personal Info and About Me section
In the main directory of the repo, locate to the file named **_config.yml**. Follow the instruction and sample code block to add your Personal Info and About Me section data.
![config](https://github.com/QuocViNguyen/quocvinguyen.github.io/blob/master/images/congif.png)

---
#### 6. Access your hosted (by GitHub Pages) website
Go to your repository in GitHub --> Settings --> Scroll down to near-bottom --> GitHub Pages section. You should see your site have been successfully hosted by GitHub Pages at 
<mark>yourusername.github.io</mark>

![](https://github.com/QuocViNguyen/quocvinguyen.github.io/blob/master/images/hosted.png)

---

### Author and Acknowledgements :black_nib::black_nib::black_nib:
Author: Quoc Vi Nguyen

Acknowledgements: 
* Christina Penner for:
   * Recommends this approach on how to host a resume online
   * Provided a list popular Markdown editors
   * Introduces me to Andrew Etter and his awesome book: Morden Technical Writing
* Andrew Etter's book for:
   * Introduces me to static website generator and its advantages



---
### FAQs :question::question::question:
**1. Is there any easier way to build a Jekyll website beside forking supported templates?**

* Yes, there is. As stated in "Choices Jekyll provides" section, you can use GitHub Page's existing Jekyll themes, which is very simple. You only need to manipulate config.yml and index.md files only.

**2. Why should I use Markdown? Isn't only for documentation?**

* Markdown is very simple and have the following advantages in the table below, and it is famous for being use in online documentation, but Jekyll has amazingly integrated markdown into static web development. Now, you can easily create a website using mostly Markdown, isn't it great? 

   |              Advantage             |               Drawback                |
   |------------------------------------|---------------------------------------|
   | Easy to understand                 | No standard format                    |
   | Support easy formatting            | Not a HTML/XML replacement            |
   | the syntax is clean                | Not extensible and limited            |









