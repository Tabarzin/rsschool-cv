## Rustam Sabirov

I am an Orientalist by education, but I have worked a lot as an editor in various magazines and web projects.  Many of them were related to technology, video games and programming. I've learned the basics of HTML and CSS for a long time, but I was afraid to take up programming. Many years ago I tried PHP and decided that it was very difficult and not for me.  But some time ago I started learning Javascript and I really liked it. I want to continue and become a skillfull engeneer.

### Skills
* HTML, CSS, JavaScript, Git
* Adobe Photoshop, Figma, GIMP
* Linux (Ubuntu based, Manjaro)

### Code Example

```
function generateHashtag (str) {
  if (str === ""){
    return false;
  } 
  
  let strCapital = str.replace(/(^\w|\s\w)/g, m => m.toUpperCase());
  let strNoSpace = "#" + strCapital.replace(/\s+/g, '');
  
  if (strNoSpace == "#") {
    return false;
  }
  
  if (strNoSpace.length > 140) {
    return false
  }
  
  return strNoSpace;
}

```
### Education
* Moscow State University
* Freecodecamp.org
* Hexlet (free cources)

### English
* Fluent

### Contacts
* _email_: golovanoga@yahoo.com
* _discord_: Rustam(@tabarzin)


