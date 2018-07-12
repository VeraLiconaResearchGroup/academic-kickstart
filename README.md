# Website of Vera Licona Lab

This website uses **Academic**, a framework to help beautiful academic websites. [Check out the latest demo](https://themes.gohugo.io/theme/academic/) of what you'll get in less than 10 minutes or [view the documentation](https://sourcethemes.com/academic/docs/).

This repository is based on **Academic Kickstart** which provides a minimal template to kickstart an academic website.

[![Screenshot](https://raw.githubusercontent.com/gcushen/hugo-academic/master/academic.png)](https://github.com/gcushen/hugo-academic/)

## Getting Started

The following describes how to install the work environment required to contribute to this website using the Command Prompt/Terminal app.

### Prerequisites

* [Download and install Git](https://git-scm.com/downloads)
* [Download and install Hugo](https://gohugo.io/getting-started/installing/#quick-install)
* [Connect github with ssh on your PC](https://help.github.com/articles/connecting-to-github-with-ssh/)

### Install and run the website on your local machine

1. Clone this repository with Git (using ssh): 

       git clone git@github.com:VeraLiconaResearchGroup/website.git website
    
    *Note that if you forked Academic Kickstart, the above command should be edited to clone your fork.*

2. Initialize the theme and the public submodules:

       cd website
       git submodule update --init --recursive

3. View your new website:
      
       hugo server

    Now you can go to [localhost:1313](http://localhost:1313) and the website of VeraLiconaResearchGroup should appear.
    
### Make changes and deploy them online
  
1. Read the [Quick Start Guide](https://sourcethemes.com/academic/docs/) to learn how to add Markdown content, customize your site, and deploy it.

2. Install a decent code editor like [Brackets](http://brackets.io/) to have a nice user experience working on the website.

3. Make sure you have the server running (see previous section) in the background so that, everytime you save a file, the webrowser refreshes so that you can see the changes in real time.

5. Once you are satisfied with the changes you've made, add/commit your changes and push them to the github repository [using the `git` command line](http://rogerdudler.github.io/git-guide/).

4. Once you are done, you can push the changes online with a single command:

       ./deploy.sh <optional changelog msg>

    This will compile the website in the `public` folder, add/commit the changes to this folder and push it to the VeraLiconaResearchGroup.github.io repository, triggering the update of the [publicly accessible website](http://veraliconaresearchgroup.github.io).
    

## License

* The VeraLiconaResearchGroup website is copyrighted by [Paola Vera-Licona](https://health.uconn.edu/vera-licona-lab/)
* The Academic Framework is copyrighted to [George Cushen](https://georgecushen.com) and released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.
