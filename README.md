<h1>Recipe AI Chef - Frontend</h1>

<p align="center">
  <a href="#requirements">Requirements</a> •
  <a href="#backend">Connect to the backend Key</a> •
  <a href="#how-to-install">How to Install</a> •
  <a href="#how-to-use">How to use</a> 
</p>


Application that generate a recipe with given ingredients, by calling Open AI completion API and returns to the frontend, to be displayed to the user.

<h2 id="requirements"> ⚠️  Requirements</h2> 
To be able to run this project you will need to:
<br>
- Have node installed in your machine
<br>
- Have an account and create an Open AI API key

<h2 id="backend"> ⚙️ Connecting to the Backend</h2>
<p>Follow the steps provided in the <a href="https://github.com/pilarfernandezz/recipe-generator-server/tree/main" target="_blank">GitHub</a> README.</p>

<h2 id="how-to-install"> 🚀 How to Install</h2>

Start by cloning this repository 

```bash
# Cloning
$ git clone https://github.com/pilarfernandezz/recipe-generator-frontend.git

# Directing to the folder
$ cd recipe-generator-frontend
```

Then, create and .env file with the backend PORT

```
BACKEND_API='http://localhost:4000'
```

Back on the terminal, run:
```bash
$ npm install
$ npm run serve
```

<h2 id="how-to-use"> 🏁 How to use</h2>

Open `http://localhost:5173/` and you are ready to use the application!
