# GitHub-nonlink-on-link-area
Tutorial on how to do this, if you used this tutorial, please give an ⭐ star! :D

## Overview

When you create an GitHub project, normally theres **no link "area"**

![image](https://github.com/user-attachments/assets/373d609b-323e-4b9d-b841-ad1ecf05b3ff)

To make that link blue clickable text, you need to...

- Click on the Settings button
![image](https://github.com/user-attachments/assets/822b5aff-edde-4803-b2b7-eeddb4ee1a71)

- And THEM put your *valid* link
![image](https://github.com/user-attachments/assets/9892ffc1-903d-467f-a296-f018eee4c7a2)



_Right?_

*Well, **no...***

## Stage 1: HTML

We all know what HTML is, so i will not explain.

Github uses a BUNCH of HTML features to make the website working, like, defining that the `password` on the login page will not display the current password typed, etc.

And the link feature also uses one of these fearues, in case `type="url"`.

But **What if i change it?**

### Stage 1.1: Values

Right-clicking the `textbox` area, i get this:
![image](https://github.com/user-attachments/assets/ea759eae-31f9-4e18-acc7-64b6082999eb)

``` html
<input type="url" id="repo_homepage" class="color-bg-default form-control input-contrast width-full" name="repo_homepage" value="" placeholder="Enter a valid URL">
```

You noticed the `input type="url"`, right? But, **what would happen if i DELETE this value?**
![image](https://github.com/user-attachments/assets/b9fac749-e169-43ae-b63e-9afc14d129c5)

Nothing change, right?

Well, lets test it...

![image](https://github.com/user-attachments/assets/9a0c407b-1934-4ffc-aaca-05c2b30785d9)
![image](https://github.com/user-attachments/assets/de74f9ad-db4a-41cc-b587-9b5580006d35)
![image](https://github.com/user-attachments/assets/d5a0f737-2d11-4d80-823b-ae60161e701f)

**TA-DA!!** Easy, right?
