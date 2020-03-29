# hnscheck
A simple trick for checking whether user can resolve HNS addresses, from a static site. 

## Using hnscheck.js
* Add a link to load http://welcome.2d/hns.js to your site's code
e.g. <script src="http://welcome.2d/hns.js"></script> if it's just HTML

* Next, add the following lines to your CSS stylesheet:

    .hns
    {
        display: none;
    }

    .nohns 
    {
      display: block;
    }

* Now just add "nohns" to anything you want to show only to users who *aren't* able to resolve HNS, and "hns" to anything you want to show only to users who *can*.

## Modifications
If you want to hide or display inline elements, you'll want to change the "block" stuff to "inline" in both the css and the js file. You'll need to rehost the js file on your own handshake domain. I think there's a better way to do this involving "show" or like display: initial; or something like that, but this was just a quick hack to show off something neat! If you have a better way to do this, please let me know.

## Ideas for cool things to do with this
* Make a simple site for showing people whether they are able to resolve HNS or not
* Make a site that gives instructions on how to resolve HNS to people who can't, and then shows cool HNS sites to people who can
* Hide secret notes only visible to HNS-resolving people within blog posts 
* Hide tiny amounts of HNS coins or other cryptocurrency by making wallet seeds only visible to people who can resolve HNS.





