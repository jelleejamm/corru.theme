# corru.theme
### corru.theme is a _work in progress_ discord theme, themed around [corru.observer](https://corru.observer).
it is intended for use with [equicord](https://equicord.org) and [vencord](https://vencord.dev), and usage of the themeattributes plugin is advised

**this theme currently DOES NOT WORK in light mode!!!** i might try and make it work in the future but that is currently out of the cards + a pain in the ass

## installation

1. make sure you have either [equicord](https://equicord.org) or [vencord](https://vencord.dev) installed
2. in the client mod settings, go to the themes tab

now, you have two choices. either:
- insert `https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/corru.theme.css` (and any other additional .css files) into your online themes (recommended if you want it to update automatically)
- download `corru.theme.css` (and any other additional .css files), open the themes folder and put them in

3. enable the theme in the themes menu
4. (optional) enable the `themeattributes` plugin (if you wish to use any of the addons that depend on it)
5. you're all set!

### .css file explanations
- `corru.theme.css` is the main theme
- `corru.theme.interloper.css` makes your messages appear like the interloper's. **themeattributes plugin required**
- `corru.theme.selfcolor.css` lets you customize your messages' colors independently. to use this: open your quickcss, add an element called `:root` and in it add a `--corrutheme-chat-selfcolor` attribute with a hex code after it. (ie `:root { --corrutheme-chat-selfcolor: #ff0066 }`). incompatible with the interloper theme, **themeattributes plugin required**
- `corru.theme.selfmsgright.css` moves your messages to the right, similarly to the interloper's. **themeattributes plugin required**

- `corru.theme.akizet.css` is an example theme which uses `corru.theme.selfcolor.css` to turn your messages into akizet's. **themeattributes plugin and corru.theme.selfcolor theme required**
- `corru.theme.obesk.css` is an example theme which turns messages in chat and search results to match that of obeski

## screenshots
![chat example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex1.png)
![message search example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex10.png)
![markdown changes example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex7.png)
![server list and server banner example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex3.png)
![invite link example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex4.png)
![system message example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex8.png)
![emoji picker example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex2.png)
![user profile example](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex9.png)
![chat example with selfcolor, selfmsgright, obesk and akizet themes on](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex5.png)
![chat example with interloper theme on](https://raw.githubusercontent.com/jelleejamm/corru.theme/refs/heads/main/githubimgs/ex6.png)
