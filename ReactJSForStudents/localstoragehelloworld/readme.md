# React JS Hello World Project with Local Storage

![image info](RandomStuffGeneratorReactApp.png)

Note: This is useful when you want to store something, like for session management. For example, after a successfull login, you want to store the logged in user, and clear the values, when the user logs out. 

Of course, this is not the most secure way to do things. However, good for hobby projects. 

Note : If you are just starting with React JS, I would recommend, trying this link. [create-react-app, Hello World, 2022 edition](https://medium.com/projectwt/create-react-app-hello-world-2022-edition-f36275a0e7c4)

# code sandbox

1. https://codesandbox.io/s/react-js-local-storage-8mpqxc

# local storage usage

```
  function addStuff() {
    //foo is the key
    //bar is the value
    //standard key value things that you see in dictionaries
    ls('foo', 'bar');
    ls.set('batman', 'Bruce Wayne');
    // <- 'bar'
    console.log(`added stuff`);
  }

  function showStuff() {
    console.log(ls.get('batman'))
    console.log(ls('foo'));
  }
```

# Related Projects

1. https://stackblitz.com/edit/github-agqlf5?file=src%2FApp.jsx - Try this as well. It's pretty basic and pretty cool. 

# Local host running 

1. Local:            http://localhost:3000
1. On Your Network:  http://192.168.29.208:3000

Note : When doing react JS, I would strongly recommending using two computers. One computer for coding. One computer for debugging over a network. Or, you can have two monitors.

# Setting Up Project and Running

```
    npm install
    npm install local-storage
    npm start

```

1. npm install. Installs all neccessary node modules. 
1. npm install local-storage. Installs the local storage library.
1. npm start

# Notes - General

1. I have put comments and console logs (caveman debugging) all over the place. ensure you have console open when you are running the app. 

# References

1. https://medium.com/projectwt/create-react-app-hello-world-2022-edition-f36275a0e7c4
1. https://www.npmjs.com/package/local-storage

# Hire Me

I work as a full time freelance coding tutor. Hire me at [UpWork](https://www.upwork.com/fl/vijayasimhabr) or [Fiverr](https://www.fiverr.com/jay_codeguy). 

# Hobbies

I try to maintain a few hobbies.

1. Podcasting. You can listen to my [podcast here](https://stories.thechalakas.com/listen-to-podcast/).
1. Photography. You can see my photography on [Unsplash here](https://unsplash.com/@jay_neeruhaaku).
1. Digital Photorealism 3D Art and Arch Viz. You can see my work on this on [Adobe Behance](https://www.behance.net/vijayasimhabr).
1. Writing and Blogging. You can read my blogs. I have many medium Publications. [Read them here](https://medium.com/@vijayasimhabr).

# important note 

This code is provided as is without any warranties. It's primarily meant for my own personal use, and to make it easy for me share code with my students. Feel free to use this code as it pleases you.

I can be reached through my website - [Jay's Developer Profile](https://jay-study-nildana.github.io/developerprofile)