# 1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed. Compared to "Run them all after all development is completed", it can be guranteened that each commit does not break test cases. And compared to "Manually run them locally before pushing code", it makes sure that every time the test cases will be ran, decrease some manual mistakes such as forgetting to do that.

# 2) Would you use an end to end test to check if a function is returning the correct output? 

No

# 3) What is the difference between navigation and snapshot mode?
navigation focuses on the page loading, while snapshot foucuses on particular action of user. I think snapshot is more simple, and it mainly concerns interaction.

# 4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. Compress the photo on this page to make it have smaller size.

2. insert lang attribute to html.

3. use meta description to imprve SEO.





