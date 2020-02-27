<template>
  <div id="app">
    <b-container class="bv-example-row">
      <b-row class="text-center">
        <b-col cols="12">
          <section class="title">
            <b-jumbotron header="Iosif Stalin" lead="A historical leader with its steel hands">
            </b-jumbotron>
          </section>
          <section class="image">
            <b-img src="https://abrilsuperinteressante.files.wordpress.com/2017/11/stalin.png" fluid-grow alt="Fluid-grow image"></b-img>
            <p id="caption"> Stalin with his traditional pipe in his mouth </p>
          </section>
          <section class="timeline">
            <b-jumbotron>
            <h2> Here's a timeline of Stalin's life </h2>
              <ul id="list-timeline"> 
                <li> <b>1879</b> - Born in Gori, Georgia </li>
                <li> <b>1894</b> - Stalin enrolls in Tiflis Theological Seminary </li>
                <li> <b>1888</b> - First Congress of the Russian Social Democratic Labour Party </li>
                <li> <b>1889</b> - Stalin is expelled from the Seminary </li>
                <li> <b>1902</b> - Stalin arrested for the first time, exiled to Siberia </li>
                <li> <b>1904</b> - Stalin escapes from Siberia, the first of many escapes from exile in the following decade. </li>
                <li> <b>1912</b> - Bolsheviks officially separate from Social Democrats, Stalin appointed to the Party's Central Committee by Lenin. </li>
                <li> <b>1917</b> - Beginning of Russian Revolution. The Tsar's government falls, replaced with a Provisional Government. Bolsheviks, including Stalin, hasten to St. Petersburg </li>
                <li> <b>1918</b> - Stalin marries Nadezhda Alliluyeva </li>
                <li> <b>1922</b> - Stalin elected General Secretary of the Communist Party </li>
                <li> <b>1924</b> - Death of Lenin. Stalin survives the reading of the Testament by the Central Committee in May. </li>
                <li> <b>1934</b> - Murder, by Stalin's agents, of Sergei Kirov. Beginning of "Great Terror," which continues until 1938. </li>
              </ul>

              <h3 id="quote"> “Ideas are far more powerful than guns. We don't let our people have guns. Why should we let them have ideas?” <br> ― Iosif Stalin </h3> 

              <h3 id="link"> You can know more about Stalin's life in its <a href="https://en.wikipedia.org/wiki/Joseph_Stalin">Wikipedia page</a>!</h3>  
            </b-jumbotron>
           </section>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>



<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>

@media (max-width: 768px) {

#list-timeline{
  width: 80% !important;
}

}

#link {
  margin: 60px auto 50px auto;
  text-align: center;
  width: 50%;
}

#quote {
  font-style: italic;
  margin: 60px auto 50px auto;
  text-align: center;
  width: 50%;
}

#list-timeline {
  text-align: left;
  margin: 60px auto 50px auto;
  width: 50%;
}

#caption {
  margin-top: 10px;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}

h1, h2 {
  font-weight: bolder;
}

ul {
  list-style-type: circle !important;
  padding: 0;
}

li {
  display: block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
