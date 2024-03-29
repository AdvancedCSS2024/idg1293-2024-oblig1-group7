# Report for the group assignment: 
This group assignment is about recreating Finn websites, using BEM and Sass.
In this report, we will document our process for this CSS Advanced oblig.
Here you'll get to know how we solved this task, what were some issues we faced, and how we managed to solve it (in the end).

### How we solved the task:

#### 1. Identifying the main components
We started by observing both the webpages (in the screenshots) and identifying the main components. We marked these components.

Here is our images from this part of the task:

##### Screenshot 1:
![Image Alt Text](screenshot1.png)

##### Screenshot 2:
![Image Alt Text](screenshot2.png)




#### 2. Implement BEM code for the components
Then we gaves some (BEM) class names to the components we had identified.

Screenshot 1:
- nav bar ---> .header_nav-list
- input text ---> search search__input
- button --> catergories__item
- card --> .card

Screenshot 2:
- card --> .login__card
- input text --> .login__form-input (type="text" id="username")
- input password --> .login__form-input (type="password" id="password")
- button --> .login__button (login__button--existing) (login__button--new)

These components was then stored in common.scss, and deployed on both page-screenshot1.html anf page-screenshot2.html. And later demo.html.

In this section we also went to the finn.no and the log in site to inspect the page. 
We looked at how the element changed when you hover it or click it. This was a good way to get to know the pages, before building them on your own.

#### 3. Page implementation
Then we split the pages between us, and worked on each one. 
We worked in seperate branches, and recreated each of the webpages. 

We faced some issues downloading the branches, but managed to solve them.
The github branches wouldnt download properly.However, we managed to solve them in the end.

Upon reviewing the page even further, we saw a mistake when classifying the category-options as buttons. We then corrected this.

We ended up making one compiled branch in the end, where we had both the screenshot pages, and all the styles. This branch was later pushed to main.

#### 4.. Demo page
Implementing the demo page:
Then we used the common.scss file to declare what was going to be in the demo.html.
After looking demo.html we inserted the html code related to the components from task 1. 


#### 5. Finalizing
When we had merged it all together, we could now deploy the webpage on github.
Here are screenshots from the websites showing that we accomplished this task

![Image Alt Text](githubconfirm.png)

##### index.html
![Image Alt Text](githubindex.png)

##### Page-screenshot1.html
![Image Alt Text](githubscreen1.png)

##### Page-screenshot2.html
![Image Alt Text](githubscreen2.png)


### Conclusion

Through this assignment, we have learned more about the use of BEM. We have managed to use BEM and implement it, in a already existing webpage.
We have faced some issues, but managed to solve them in the end. I think this will help us alot, if we face the same or similar issues in the future.
We have understood how to work togehter in a Github reposistory, and finalize a comined "product" working this way.


