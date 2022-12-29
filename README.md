# Smart usage of Obsidian (iPhone, Mac, Git, & as teams)
### Use Obsidian asynchronously in Mac, iPhone using GIt, iCloud. Smart solution
---
### Before start, 

1. you have to download `Obsidian Git` for your Mac Obsidian app from Community plugins. [For more info](https://github.com/denolehov/obsidian-git)
   - Create a git `repository` to upload your local Obsidian works.
   - Now, your local Obsidian works will automatically commit and push as you set.
2. you have to download Obsidian iOS app for your apple device and if you've never used this app, please follow below

>open the app and create a vault **<u>enabling Store iCloud</u>** so that it can automatically create an `Obsidian` folder inside iCloud.


<br>

Your Obsidian is now syncing with Git. __But you want to sync it with your iPhone as well.__

### Let's start

Now, what we're going to do is to clone `Obsidian repository` that you've created. <br>
We're not just cloning into your local Mac directory but into your iCloud -> Obsidian folder

Using terminal, direct to iCloud folder -> Obsidian isn't pretty easy. <br>
So, to make it easier, open terminal and type in terminal command below:

````bash
$ cd ~
$ ln -s Library/Mobile\ Documents/iCloud~md~obsidian/Documents/ Obsidian
$ cd Obsidian
````
This command creates the links for the files/folders

now, we can direct to iCloud -> Obsidian folder very easily by just typing `cd Obsidian` only. <br> <br> 
You can now git clone into the obsidian folder and enjoy git - iCloud synchronous environment. <br> 
Once cloning is completed, open your iOS Obsidian app, find cloned folder/files and check beautifully synced between devices. <br> <br>


### More

If you set your Obsidian Git plugin `Pull updates on startup` turned on, your iPhone will show you an error that is failed to pull/push once you open the app. That's because you didn't login to your Git on your iOS Obsidian app. <br>

Inside of your Obsidian app -> Settings -> Obsidian Git -> Authentication/Commit Author
enter your username on GitHub, type in your password.
Restart your Obsidian, it will work perfectly.





