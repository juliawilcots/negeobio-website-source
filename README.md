# Northeast Geobiology Symposium, hosted at MIT

### Symposium Details:
April 16, 2022  
Stata Center (Building 32), MIT, Cambridge, MA  

### Contact
[Email us](mailto:negeobio2022@gmail.com)


## Notes for Julia/future developers
This repository is updated with website info (photos, details, etc.), then built using hugo (locally). The resulting 'public' directory is linked to [this github repo](https://github.com/juliawilcots/NEGeobio-2022-MIT.git), which then publishes the site to [https://juliawilcots.github.io/NEGeobio-2022-MIT/](https://juliawilcots.github.io/NEGeobio-2022-MIT/).  

To do this, work locally on negeobio-website-source. Save changes by pushing to github as you work. Then, when you are ready to deploy, run ```./deploy.sh``` which will build the site (using hugo) and push the resulting ```public``` directory to github (NEGeobio-2022-MIT), which will update the website.
