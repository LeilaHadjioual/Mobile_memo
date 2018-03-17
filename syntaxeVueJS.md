
## VueJs  

1-balise script à ajouter 

    <script src="https://cdn.jsdelivr.net/npm/vue"></script> 

*ou taper sur google vue cdn et prendre vue.js* : avec DOM
*ou version common.js* : version sans DOM et qu'avec virtual DOM, plus léger (version minifier)

ne pas oublier d'ajout le script JS

**balises à ajouter après le body**

2-Généralités

- attribut   

v-bind = une directive (peut etre remplacé par :)  
v-if = condition (v-if ='success' / succes = true ou false)  
v-show = affichage mais rajoute un display none contrairement à v-if qui supprime l'élement  
v-else = si opposé à un v-if  
v-for = boucle (person in persons) {{person}}  
v-on = gestion des entrées utilisateurs (v-on:click="close" seulement avec les méthods ou @click)  
v-model = liaison entre champ d'un formulaire et l'application (dans input ajouter v-model="message") (idem checkbox avec input changer le type)  

-instancier une nouvelle vue  

    new vue({     
        el:'#app", //élément  
    })


3-affichage html

    <div id="app">
        {{ message }}
    </div>

4-affichageJS

    new Vue({
        el: '#app',
        data: {
        message: 'Hello Vue !'
        }
    })

5-conditions  

    <div id="app-3">
        <p v-if="seen">Maintenant vous me voyez</p>
    </div>

    var app3 = new Vue({
        el: '#app-3',
        data: {
            seen: true
        }
    })

6-boucles

    <div id="app-4">
        <ol>
            <li v-for="todo in todos">
                {{ todo.text }}
            </li>
        </ol>
    </div>  


    var app4 = new Vue({
        el: '#app-4',
        data: {
            todos: [
                { text: 'Apprendre JavaScript' },
                { text: 'Apprendre Vue' },
                { text: 'Créer quelque chose de génial' }
            ]
        }
    })

*pour afficher un nouvel élément, ajouter dans JS, hors de la variable app4* :

          app4.todos.push({ text: 'Nouvel élément' })


7-interaction utilisateur

    <div id="app-5">
        <p>{{ message }}</p>
        <button v-on:click="reverseMessage">Message retourné</button>
    </div>  

    var app5 = new Vue({
        el: '#app-5',
        data: {
            message: 'Hello Vue.js !'
        },
        methods: {
            reverseMessage: function () {
                this.message = this.message.split('').reverse().join('')
            }
        }
    }

*avec v-model*  

        <div id="app-6">
            <p>{{ message }}</p>
                <input v-model="message">
        </div>  

        var app6 = new Vue({
            el: '#app-6',
            data: {
                message: 'Hello Vue !'
            }
        })  


  
installer vue-cli  

    npm install -g vue-cli
    vue init webpack-simple my-project
    cd my-project
    npm install
    npm run dev


