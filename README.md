# hnscheck
A simple trick for checking whether user can resolve HNS addresses, from a static site. 

## Using hnscheck.js
Add a link to load http://welcome.2d/hns.js to your site's code
e.g. <script src="http://welcome.2d/hns.js"></script> if it's just HTML

Next, add the following lines to your CSS stylesheet:

    .hns
    {
        display: none;
    }

    .nohns 
    {
      display: block;
    }

Now just add "nohns" to anything you want to show only to users who *aren't* able to resolve HNS, and "hns" to anything you want to show only to users who *can*.

## Modifications
If you want to hide or display inline elements, you'll want to change the "block" stuff to "inline" and also  


## Ideas for cool things to do with this

