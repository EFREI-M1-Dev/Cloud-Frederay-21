# PROJECT BY [missating](https://github.com/missating)

# COMMAND LIST SAMEPLE
- Créé un token pour ce login : exemple token : 965864853458345484389TYGT4
- faire un docker login:
```bash
 echo 965864853458345484389TYGT4 | docker login ghcr.io -u fredray-21 --password-stdin
```
- faire un docker build (on build l'image)

Exemple :
```bash 
docker build -t $(nom de l'image complet) .
```

Commande :
```bash 
docker build -t ghcr.io/fredray-21/NOM_IMAGE .
```

- faire un push de l'image
```bash 
docker push ghcr.io/fredray-21/NOM_IMAGE
```

---

## DEFAULT README :

# nodejs-todo
<h2> A simple To Do List application built with Node.js and Express</h2>

<p> Nodejs application that let's you add and complete task on a single page, storing both new and completed task in a different array. This appllication makes use of: </p>

<ul>
<li> EJS - A simple templating engine that lets you generate HTML markup with plain JS </li>

<li> Body-parser - This extracts the entire body portion of an incoming request stream and exposes it on req.body </li>
</ul>

![png](https://github.com/missating/nodejs-todo/blob/master/todo.png?raw=true 'web todo')

<br>

<p> How to run the app locally: </p>

<ol>
<li> Run <code> npm install </code> to install all needed dependencies </li>

<li> Then start the server using <code> node index.js </code> </li>

<li> Navigate to your browser <code> http://localhost:3000/ </code> to view the app </li>
</ol>

<p> I wrote a blog post on how to build this app, you can check it out <a href="https://medium.com/@atingenkay/creating-a-todo-app-with-node-js-express-8fa51f39b16f" target="_blank">Here</a>

