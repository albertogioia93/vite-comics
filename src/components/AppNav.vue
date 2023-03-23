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
nav {
    ul {
        margin: 0;
        list-style: none;
        display: flex;
        
    }

    li {
        
        a {
            display: inline-block;
            padding: 20px;
            
        }
    }
}
</style>