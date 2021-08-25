# VScode-Configuration
It consists all the details of how to setup VsCode in master level for your preferable language or all in one use also


# `Vs code Customization for Quick Coding 💯`

## `Here I'll be explaining the Details of `Plugin` and usage. 🖥️ `

---

```
                        I'll be listing all the Plugins and usage, and Many more will be added constantly
```

<!--  The Result would be looking some thing like below -->

### `I'll be adding the pre-config files in `Content/Configs` folder.`


```diff
+ I'll be adding more files and even in the below I'll be adding new plugins with date of update
```

## <a href="[../../Conten/Configs/](https://github.com/SURESH-BABU-G/VS_code_master-tutorial/tree/main/Content/Configs)">Configs Path</a> - `it consists all required list of pre-configured files.`

```diff
* Please, Feel free to raise a bug or note for required language plugins or configuration for a language ( I research and make a uniq look and comfort for your requirement )
```

```diff
- Important is file should be renamed to extensions and extension will be .list (if it is not with same name)

! finally file should be extensions.list
```

---
 ## `Installation Steps:` 
***
``` For Windows(PowerShell): ```
 ```code
    foreach($line in get-content extensions.list){code --install-extension $($line)}
 ```
***
```For MAC :```
```code
   cat extensions.list | % { code --install-extenstions $_}
````
***
```For Linux :```

``` code
   cat extensions.list | xargs -L 1 code --install-extenstions 
```
***


# ` Pre-Configuration for VS-Code 💯`

## `Here I'll be  providing `Pre-configuration`  file  for  every `Language` puroposes. 🤤`

---

```
       For a different languages VS Code will supports with different plugins.

       We can use best plugins for all in one work support, But, Files will use performance of VS Code.
```

```
 I'll be attaching all the configuration files, And I'll be attaching my system best configurations.
```

## <a href="[../../../Configs/extensions-web.list](https://github.com/SURESH-BABU-G/VS_code_master-tutorial/blob/main/Content/Configs/extensions-web.list)" download="extensions.list">Download File</a> - `it consists all required list of packages`

```diff
- Important is file should be renamed to extensions and extension will be .list (if it is not with same name)

! finally file should be extensions.list
```

---
 ## `Installation Steps:` 
***
``` For Windows(PowerShell): ```
 ```code
    foreach($line in get-content extensions.list){code --install-extension $($line)}
 ```
***
```For MAC :```
```code
   cat extensions.list | % { code --install-extenstions $_}
````
***
```For Linux :```

``` code
   cat extensions.list | xargs -L 1 code --install-extenstions 
```
***
 ## 🚦 `Categories`
✅ Web Development <br/>
⬜ NodeJs <br/>
⬜ Laravel <br/>
⬜ Docker <br/>
⬜ React <br/>
⬜ ReadMe <br/>
⬜ Beautify <br/>
⬜ All in one <br/>
⬜ Individual <br/>

***

# `#1. Detailed Description for Web developement plugin configuration`

| Package                | Description             | Where it Required | How it Works               |
| ---------------------- | ----------------------- | ----------------- | -------------------------- |
| abusaidm.html-snippets | It's for HTML shortcuts | HTML creation     | h1*6 will create 6 h1 tags |
|ecmel.vscode-html-css| It's for CSS selectors | while using Loops | when you type class, it shows used location |
|zignd.html-css-class-completion | It's for CSS classes | Class Redirection | You can get suggesstion of used classes |
|lonefy.vscode-js-css-html-formatter| To indent the HTML file | HTML files | It indenets the HTML code in clean way to make the code more understandable |
|tht13.html-preview-vscode| To preview the HTML code output | While coding HTML | It will show you the real time in HTML output |
|hdg.live-html-previewer| To preview the HTML code output | While coding HTML | It will show you the real time in HTML output |
|sibiraj-s.vscode-scss-formatter| It's a advanced version of CSS file formatter | It's for advanced CSS developer | It format the advanceed CSS files to make it clean |
|mrmlnc.vscode-scss| It's a advanced version of CSS file formatter | It's for advanced CSS developer | It format the advanceed CSS files to make it clean |
|ritwickdey.live-sass| SCSS file compiler | for SCSS file writer | It automatically compile SCSS files code to CSS |


# `#2. Detailed Description for Node JS developement plugin configuration`