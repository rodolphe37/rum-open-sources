# Tutorial Intro

Let's discover **React Ultimate Messenger in less than 5 minutes**.

### Classic RUM version repository (for open sources contributors)

 ![alt text](/img/rum-demo.png "RUM versions")

 ## Full documentation site

**You can go directly to the complete (Classic & PWA versions) documentation site about the application.** **[here](https://react-ultimate-messenger-documentation.netlify.app/)**,


## Online Demo sites

### Classic RUM version

**You can try Classic React Ultimate Messenger** **[here](https://react-ultimate-messenger.netlify.app/)**,

### PWA versions

**You can try PWA React Ultimate Messenger**

You have two versions with mobile devices menu!

**[With Classic bottom menu](https://pwa-react-ultimate-messenger-with-bottom-menu.netlify.app/)**,

**[With Radial burger menu](https://pwa-react-ultimate-messenger-with-radial-menu.netlify.app/)**,



(The demo is not fully functional without the server started locally*)


> *you can only send/receive messages if you have the server locally on your machine -
> I explain how to test the online version with your local version further in the documentation...


## Getting Started to contribute to the project!

you just have to **clone this repository**.

## start the contribution

Create a folder, go to it and open your terminal from this folder of course,

There is **one line of code to do** before the contribution to the App...
```shell
git clone https://github.com/rodolphe37/rum-open-sources.git
```

## Start your local site version

***Run the development server:***

go to your folder app
```shell
cd my-app
```

At this stage, you have two lines of code to do:

 * *I made several scripts in the package.json so that everything is automatic!*

The first line is for initializing all servers
```shell
npm run initAll
```
> - This script will first install the necessary node_modules in the messages-images server, then create an uploads folder (in which the images sent in the chat will be sent), then rename the .env.example file to .env.
> - And finally, he will rename the .env.local.example file to .env.local & .nvmrc.example to .nvmrc in the React frontend folder.


 ***If you have nvm installed:***

> the chat application requires at least version 12 of Node.js, the nvmrc file is initialized with version 14.15.1. If you have version 12 or higher everything will work fine!
> Otherwise you can change your Node version by simply doing:
> ```shell
> nvm use
> ```

And the second line is to start all the services.
```shell
npm run dev
```

  With this single line of code you will start
 > - the server that manages the chat (messages and images) on port 4000,
 > - as well as the classic React frontend on the classic port 3000.


Your site starts at `http://localhost:3000`.

### How to test your local version with the online version!

> * At this level of the tutorial, you have your backend server(s) and your site started and open at the classic address.
> You just have to open in another browser window the demo that corresponds to the version you just installed (link available at the top of the page).
> Then you just have to connect to the same room in both windows and start testing your version.

  ***The left window is the online (prod) version - The right window is your local (dev) version.***
 ![alt text](/img/test-classic.png "Remote test")

* **Enjoy!**


## To work with this version

Of course, it is **important to contact me beforehand** to submit the **idea of your feature**, or to **discuss the important points** in this project, **the logic, the paradigm and the dynamics**...

 Open your App folder with your **usual editor** and **start making your React App as usual**!

 **Create a local branch**, work on it, then make a **pull request on the contribution branch**, I will do the **code review and integration** on the **prod version** if your feature is **stable, reliable and interesting for the dev/users** who will use this Web Application.

 ## All RUM version template repositories:

 **[Classic React Ultimate Messenger](https://github.com/rodolphe37/cra-react-ultimate-messenger)**,

 **[PWA React Ultimate Messenger](https://github.com/rodolphe37/cra-pwa-react-ultimate-messenger)**,
<!--

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like. -->
