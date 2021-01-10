# Google's Search

>Beta testing for hide native discourse's search and show only Google's search

This component eliminates the ability for users to use Discourse's native search engine. Instead, they will use the search engine powered by Google, and it allows adding monetization through it.

My original idea is to remove the native Discourse search engine for anonymous and users with TL0 - TL1, while to the rest of the registered users, hide the new Google search engine and show them the native one.

## Screenshot

![Demo Screenshot](https://raw.githubusercontent.com/SidVal/www/master/files/img/screen1.png)

## How To

1. Fork this repo first! _(Here with Github, you will need a Github free account)_
1. Create new "Google's Search" [here](https://cse.google.com/cse/)
1. Settings (your forum's URL it's a must)
1. Edit and modify your [`head_tag.html`](https://github.com/SidVal/discourse-google-search/blob/main/common/head_tag.html) with the google's search code.
1. Go to your forum's admin panel, and Install the component. [How do I install a Theme or Theme Component?](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682?u=sidv)
1. Preview it.
1. Test it.
1. Enjoy!

## To Do

- [ ] I wanted to put the search engine on the "`header`" section, however I couldn't find a way via CSS to place it inside the "`panel clearfix`" class. I'm sure someone on the forum can help out with this.
- [ ] Conditional: if the user is anonymous or TL0 or TL1, show the Google search engine. If not, show the native one (and hide the one from google)

### Features requested

- [ ] "Configuration" section to configure which levels of users can see one or the other search engine. I need help with this as I don't handle `"/settings.yml"` yet
- [ ] [Add your idea](https://github.com/SidVal/discourse-google-search/issues)

## Disclaimer

**This is a ALPHA / Beta version, please TEST it!** 

You can tell me what do you think here on [issues section](https://github.com/SidVal/discourse-google-search/issues) :pray: 
