# holbertonschool-headphones
## Implement a design from scratch

-   Master
-   By:  Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School
-   Weight:  3

### Concepts

_For this project, we expect you to look at this concept:_

-   [Implement a design](https://intranet.hbtn.io/concepts/963)

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.

Here the final result:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=793e26260425d8afcfa4381f01c07e3b9cb9c9b215930f49b5da7eef64ad33f4)

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip "here")

### Requirements

-   you are not allowed to import external CSS framework (like Bootstrap)
-   you are not to use Javascript

## Tasks

### 0. Read and be familiar with Figma

mandatory

Create an account in  [Figma](https://intranet.hbtn.io/rltoken/y6_o1T-HtCyTAGuOJqdA_g "Figma")  and open this  [project](https://intranet.hbtn.io/rltoken/SpYRV14tPxTZJSjU2Eoh4A "project")  and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the  [Figma file](https://intranet.hbtn.io/rltoken/tWEPFyHyXyNO9Xfi2Er2EA "Figma file")

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b2844fd32a066c013624233355d21ce3a0cf5c193de774219fcde8b1d52a8ba2)

Important notes with Figma:

-   if your computer doesn’t have missing fonts, you can find them here:  [source-sans-pro](https://intranet.hbtn.io/rltoken/yvx4-XkjAQJgHlN6RAoKWQ "source-sans-pro")  and  [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Jw0FKYKB6l5_2Koto0duTA "Spin-Cycle-OT")
-   some values are in float - feel free to round them

For this task, please write an amazing  `README.md`

**Interactions note:**

-   the web page must switch to the mobile version when the screen width is 480px or less
-   links hover/active:  `#FF6565`
-   button hover/active:  `opacity: 0.9`
-   max width of the content: 1000px centered in the page

**Repo:**

-   GitHub repository:  `holbertonschool-headphones`
-   File:  `README.md`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2377#task-21818-carousel)

README is present and not empty

[](https://intranet.hbtn.io/projects/2377#task-21818-carousel)

Help

**0/1** pt

### 1. Header

mandatory

Building a web page the right way, is not easy - expect if you put in place strong foundations:

-   reset CSS styling
-   use variables
-   simple/“as generic as you can” CSS selectors
-   avoid using super specific CSS selectors as much as possible
-   simple HTML structure -  `div`  containers are your friend!

Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.

Now, your turn!

For this first task:  **create the header/hero piece**

Here an archive of all assets needed:  [images_.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=25a35c31d8b253d996c28974e81dbf0e256a5fb936736ce189389e1ab4e97b71 "images_.zip")

**Desktop:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a1c1b1cf29fb1bdda6c9d9207e83a2d2d7d48a801284fb455402b1c39369e6af)

**Mobile:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=845a0909f74d1fc18f8bf0a53479dc150e0d5f24aaa1e2a6a3304c4b0ff7987d)

**Repo:**

-   GitHub repository:  `holbertonschool-headphones`
-   File:  `0-index.html, 0-styles.css`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2377#task-21819-carousel)

Files exist

[](https://intranet.hbtn.io/projects/2377#task-21819-carousel)

Help

**0/25** pts

### 2. "What we do..." section

mandatory

Copy files from the previous task.

For this second task:  **create the “What we do…” section**

In this section, you will need custom font icons. Here the archive of it:  [holberton_school-icon.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=60d1964b61e9653efbf0a606ce0dcb7e56dc27b5b61e62c292a43479c2c67b2b "holberton_school-icon.zip")  Inside you will find demo page of how to use it.

**Important:**  try to build as generic as you can… you will probably need some components in next section.

**Repo:**

-   GitHub repository:  `holbertonschool-headphones`
-   File:  `1-index.html, 1-styles.css`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2377#task-21820-carousel)

Files exist

[](https://intranet.hbtn.io/projects/2377#task-21820-carousel)

Help

**0/26** pts

### 3. "Our results" section

mandatory

Copy files from the previous task.

For this third task:  **create the “Our results” section**

Now you can reuse components form the previous task!

**Repo:**

-   GitHub repository:  `holbertonschool-headphones`
-   File:  `2-index.html, 2-styles.css`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2377#task-21821-carousel)

Files exist

[](https://intranet.hbtn.io/projects/2377#task-21821-carousel)

Help

**0/25** pts

### 4. Contact us

mandatory

Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.

**Repo:**

-   GitHub repository:  `holbertonschool-headphones`
-   File:  `3-index.html, 3-styles.css`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2377#task-21822-carousel)

Files exist

[](https://intranet.hbtn.io/projects/2377#task-21822-carousel)

Help

**0/19** pts

### 5. Footer

mandatory

Copy files from the previous task.

Last piece of the page… the Footer!

When you are done, here the result:

**Desktop:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=de2d32a6a2bddf461701df2e833c885bdd6394fc5d8ec66721371d65126ef7fa)

**Mobile:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230406%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230406T065835Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=698fbd1c7dcb8b77dc3433d955e1d7228c1ee2c514038e3425722382c22f6f85)

And you are done!

**Good job!**
