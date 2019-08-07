<template>
    <v-app>
        <NavBar/>
        <v-content>
            <Home/>
            <About/>
            <Content/>
            <Footer/>
        </v-content>    
    </v-app>
</template>

<script>
    import NavBar from '../src/components/NavBar'
    import Home from '../src/views/Home'
    import About from '../src/views/About'
    import Content from '../src/views/Content'
    import Footer from '../src/components/Footer'

    export default {
        name: 'App',
        components:{
            NavBar,
            Home,
            About,
            Content,
            Footer
        }
    };
</script>
