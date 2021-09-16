
# ` Pre-Configuration for VS Code like My Office setup 🖥️`

## `Here I'll be  providing `Pre-configuration` files  of my office system setup 🤤`

---

```diff
       For a different languages VS Code will supports with different plugins.

       We can use best plugins for all in one work support. But, more plugins may raise performance issue of VS Code.

       That's the reason I'm giving My Personal setup with free of cost to make yours ** Beautiful ** & ** Productive **
```

```
    I'll be attaching All the files down below and steps to setup.
```

### Files 📁

    1. Extensions list 
    2. Settings object
    3. ttf file for Font.

### <a href="https://github.com/SURESH-BABU-G/VScode-Configuration/blob/main/Pre%20Configurations/Configs/Office/extensions.list" download="extensions.list">Extensions file</a>,  <a href="https://github.com/SURESH-BABU-G/VScode-Configuration/blob/main/Pre%20Configurations/Configs/Office/settings.json" download="settings.json">Settings file</a>,  <a href="https://github.com/SURESH-BABU-G/VScode-Configuration/blob/main/Pre%20Configurations/Configs/Office/CascadiaCode.ttf" download="CascadiaCode.ttf">Font file</a>

Or Download the current folder files or zip file
***
 ## `Installation Steps:` 
***

    1. First Download all three files.
    2. Next Run the below command (extensions.list should be the file name and command should run in the same folder where files are downloaded).

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

    3. Then we need to open the settings.json file. Copy the content and replace the content of settings.json of vsCode.

How to find the settings.json file of vs Code?

    
    ## Steps to Find the settings.json
    1. open vs code and press cnttl + , ( mac - command + ,)
       1. else you can see cog icon on the left side down, press that , and open settings.
    2. Next search for settings - you'll see ** Edit in settings.json ** Open that and replace whatever you downloaded file of settings.json
       1. If you want you can have backup of what you've currently.
   

    4. Final step is, double click the ttf file and install it 
   

   ### Once All done then restart the vs code. You good to go.

