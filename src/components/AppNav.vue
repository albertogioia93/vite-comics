<script>
    export default {
        nome: 'AppNav',
        data (){
            return {
                menuList: [
                  {
                      nome: 'CHARACTERS',
                      link: '#',
                  },
                  {
                      nome: 'COMICS',
                      link: '#',
                  },
                  {
                      nome: 'MOVIES',
                      link: '#',
                  },
                  {
                      nome: 'TV',
                      link: '#',
                  },
                  {
                      nome: 'GAMES',
                      link: '#',
                  },
                  {
                      nome: 'COLLECTIBLES',
                      link: '#',
                  },
                  {
                      nome: 'VIDEOS',
                      link: '#',
                  },
                  {
                      nome: 'FANS',
                      link: '#',
                  },
                  {
                      nome: 'NEWS',
                      link: '#',
                  },
                  {
                      nome: 'SHOP',
                      link: '#',
                  }

                    
                ]
            }
        }
    }
   

</script>

<template>
    <nav>
        <ul>
            <li v-for="menu in menuList">
                <a :href="menu.link">{{ menu.nome }}</a>
            </li>
        </ul>
    </nav>
</template>


<style lang="scss" scoped>
@use 'src/assets/styles/partials/_reset.scss' as *;
@use 'src/assets/styles/partials/_variables.scss' as *;
nav {
    ul {
        margin: 0;
        // USO QUESTO COMANDO DA _reset.scss GRAZIE AL RELATIVE PATH COPIATO E INCOLLATO DOPO @use
        // list-style: none;
        display: flex;    
    }

    li {
        
        a {
            display: inline-block;
            padding: 20px;

            // quando passo sopra col mouse, lo sfondo dell'elemento diventa di colore lightgrey e il testo di colore definito nel file variables.scss
            &:hover {
                background-color: lightgrey;
                color: $text-hover-color;
            }
        }
    }
}
</style>