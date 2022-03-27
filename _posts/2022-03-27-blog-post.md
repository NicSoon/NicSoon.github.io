---
layout: post
title : "blog post"
date: 2022-03-27
catogeries: jekyll blogging
---

##My first blog post!

Learning to use github and the world of coding was scary at first but as I learn more about it, its actually so fascinating and fun to work with.

Lets test this and add a code block

```
<footer class="footer">
        <nav class="social">
            <a href="https://wwww.facebook.com/TAFENSW/">
                <i class="fa-brands fa-facebook"></i>
            </a>
            <a href="https://twitter.com/tafensw">
                <i class="fa-brands fa-twitter"></i>
            </a>
            <a href="https://www.instagram.com/tafensw/">
                <i class="fa-brands fa-instagram-square"></i>
            </a>
            <a href="https://www.linkedin.com/company/tafe-nsw/">
                <i class="fa-brands fa-linkedin-in"></i>
            </a>
        </nav>
    </footer>
```

##Add images

Create an `asset` folder where you can put all your images,
then display them with a link starting with an exclamative mark like this:
`![my inspiring image]({{ "/asset/sample-image.jpg" | relative_url }})`.

![my inspiring image]({{ "/asset/sample-image.jpg" | relative_url }})
_Photo by [Denise Jans](https://unsplash.com/@dmjdenise)_

