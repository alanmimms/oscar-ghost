# (Alan's version of) Oscar for Ghost

*Demo:* [alanmimms.com](http://alanmimms.com)

## Introduction
I hacked up Oscar's pure work for my own evil designs. Much of what is
in here was originally written by Oscar to describe his work. I can
take little credit for anything, but I did find it useful and I did
make it compatible with Ghost v1.0.

The **Oscar Ghost** Theme is a clean, simple, minimalistic theme built for ghost. The theme is built from an original 
fork of the [Lanyon-Ghost](https://github.com/PxlBuzzard/lanyon-ghost) Theme. 

This theme is ideal for single author, tag heavy, looking for a simple design, with code highlighting. 

## Features
- Configurable Features
- Custom Navigation Menu ([#7](https://github.com/oscarmorrison/oscar-ghost/issues/7))
- Submenu for tags ([#20](https://github.com/oscarmorrison/oscar-ghost/pull/20))
- [Prism.js](http://prismjs.com) Code Highlighting (Markup, Bash, Swift, JS, C, Go, Python...)
- Font: [Lato](https://www.google.com/fonts/specimen/Lato) weights 100,300,300italic
- Automatic internal and external linking
- Featured Image on Posts
- Custom Tag Home Page
- Tag Styling
- Date Styling
- Single Author (no Author on Posts)
- Gallery Viewer ([Photoswipe](http://photoswipe.com/)) ([#10](https://github.com/oscarmorrison/oscar-ghost/issues/10))
- Custom Gallery Post Listing


## Customization

### Configuration
I have included with v1.0.4 a way to do some basic feature configuration that is often asked for:
These are the default values (found in oscar.js):
```
let oscar = {
    animatedNav: true,
    tagMenu: true,
    tagKey: '#tagnav',
    requirePosts: false
};
```

**animatedNav:**  if the nav auto hides, or is shown  
**tagMenu:** if the secondary tag menu is shown  
*tagMenu is dependant on ghost api beta feature this can be turned on under [Ghost Admin] -> [Labs] -> [Public API]*  
**tagKey:** what the custom key to look for in the tag description is. (this can be any string)  
**requirePosts:** show only tags that have posts in them  

### Navigation
![NavBar](http://blogoscarmorrison.s3.amazonaws.com/2016/Dec/navigationBar.png)   
The navigation menu can be customize through the [ghost admin](https://blog.ghost.org/navigation/), 
the theme come with 32 custom icons that can be used in the nav bar menu.  
Please see here for all icons http://ogem.co/blogiconmoon  
simply just use the icon class name   
e.g **icon-twitter** for -> **twitter**.
![Navigation](http://blogoscarmorrison.s3.amazonaws.com/2016/Dec/navigation.png)   


### Gallery
To get the full benefits of the Gallery Viewer (Photoswipe) in a blog post, simply tag the post with 
**gallery**. Any post that is of type gallery will get special behavior. 
* Gallery Post will be displayed differently in a the list post view, they will show special gallery icon, and will not show any description.
* Gallery Post will have special behavior for the user. The images will all have a cursor pointer and be clickable. Once any image is clicked, the photoswipe viewer will open in full view. 
* To add images to a gallery post, add them as you normally would with any post.

### Code Syntax Highlighting
Use [prismjs](http://prismjs.com/download.html) for syntax highlighting.  
in your blog symply surround code block with:

\```language-bash  


## Installation

- Download the [Theme](https://github.com/oscarmorrison/oscar-ghost/archive/master.zip) .zip
- Install the Theme ([Instructions](http://support.ghost.org/switch-themes/)]
    - Unzip the folder and upload to 'ghost/content/themes'
    - Restart ghost and log in
    - Go to settings > themes and select Upholsterygeist

### Cost
Free. As in free beer...   
If you like the theme, and would like me to keep building cool free ghost themes feel free to buy
 me a beer.  
[![Paypal Badge](http://blogoscarmorrison.s3.amazonaws.com/2016/May/PaypalBadgeSmall.png)](http://paypal.me/oscarmorrison)

## Author

**Alan Mimms** (hacker of Oscar's work)
- <https://github.com/alanmimms>
- <https://twitter.com/alanmimms>

**Oscar Morrison**
- <https://github.com/oscarmorrison>
- <https://twitter.com/oscargemorrison>

## License

Open sourced under the [MIT license](LICENSE.md).
