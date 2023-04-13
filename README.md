# Brainhack School
This is the website of the brainhack school, built with [hugo](https://gohugo.io/). 

## Deploying site
The deployment of the website is automated using github actions. 

## Run locally 
To test it locally, you will need to:
1. Clone/fork this GitHub repo: `git clone https://github.com/school-brainhack/school-brainhack.github.io.gitt`
1. Make sure you're inside the **school/** dir (`cd school`), then **clone the submodule for themes:** `git submodule update --init --recursive --remote`
1. If [Hugo](https://gohugo.io/) is not installed, follow the steps in their documentation to install it on your machine: https://gohugo.io/getting-started/installing/
1. To run the website locally, make sure you are still in `school/` dir and type `hugo serve -D`.
   - The -D option is to serve the website including the draft .md files.
   

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
