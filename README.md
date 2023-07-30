# Task 1:

## Online Shop

### Tech requirements:

- Installed docker and docker-compose(example installtion link: https://docs.docker.com/desktop/install/windows-install/)

### Business requirements:

Imagine you are a software engineer who needs to launch an online store. The online store should be fully functional and usable on mobile devices.
In addition, it should meet the following criteria:

1. The store should contain a menu and a footer
2. At the top of the page, it should be possible to display a customizable narrow banner (like gemour.pl).
3. At the stage of order checkout, the form should contain an optional field for entering the VAT number
4. A checkbox must be required in the form to complete the order in order to accept the regulations and privacy policy.
5. Add information in the cart page between cart form and shipping method table
6. The store should be able to search for products by name (normal search engine)

Keep the store in high performance (we will check it with lighthouse)
You have full freedom in using templates, plugins and other components(can't be too old). The shop should be in Polish. You can fill the content of Lore Ipsum. The whole thing should be neat and aesthetic.

### Getting started

To run the project you should run `docker-compose up -d` which will raise 3 containers(check it with `docker-compose ps` command). Then you should be able to open `http://localhost:80`
In `wordpress/html` directory docker will store wordpress files. It will be changing whithing changes you make in admin panel.
In `dbdata` docker stores data from database. Please commit these changes and push it to remote.
Please, make your git history clean in the final solution.

### How to publish your results

Please do not raise a PR to the original repository. Just fork this repository and work on your forked version of this repository. When you finish your work please send us a link to your repository(leave it public) to `kariera@gemour.pl`

# Task 2(15 minutes):

As a software engineer you know that you should keep your work in a high quality. High performance is also a good sign of a good quality product.
Please do a quick review of the store https://gemour.pl/ (we are listing our store here because we know exactly what doesn't work here and what needs improvement/change) and report what you think doesn't work well, what needs repair/change in terms of performance and if you know how, write it
