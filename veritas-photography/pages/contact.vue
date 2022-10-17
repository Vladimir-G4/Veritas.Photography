<template>
    <div>
      
     <!-- <NAVBAR> -->
    <div class="columns">
      
      <div class="column is-one-quarter" style="max-width:50em; padding-left:30em;">
        <a href="/"><img src="../assets/logo.png" style="max-width:45em; padding-right:20em;"></a>
      </div>
      <div class="column is-one-quarter"></div>
      <div class="column is-one-third" style="padding-top: 7em; padding-left:27em; display: inline;">
        <a href="/"><button class="button is-white"><h2 style="font-family: Archivo Black; font-size:larger;">Work</h2></button></a>
        <a href="/contact"><button class="button is-white"><h2 style="font-family: Archivo Black; font-size:larger">Contact</h2></button></a>
      </div>
    </div>
    <!-- </NAVBAR> -->

        <div class="container" style="max-width: 45em; text-align: center;">
            <figure class="image is-5by4">
                <img src="..\assets\me.png">
            </figure>
        </div>

        <div class="container" style="width:30em; padding-top: 1.5em;">
        <section>
            <b-field label="Name">
                <b-input type="name" maxlength="50" placeholder="Vladimir"></b-input>
            </b-field>

            <b-field label="Email">
                <b-input type="email" maxlength="50" placeholder="vladimir@veritasphotography.art">
                </b-input>
            </b-field>
            <b-field label="Message">
                <b-input maxlength="250" type="textarea" placeholder="Whether you want to collaborate or receive a quote on a project, leave the details here!"></b-input>
            </b-field>
            <b-field style="text-align:center;">
                <b-button>Submit</b-button>
            </b-field>
        </section>
        </div>

        <!-- <FOOTER> -->
        <div style="text-align: center; padding-top: 3em; text-decoration: underline;"><a href="https://instagram.com/veritasphotography.art" target="_blank" rel="noopener noreferrer"><h5 class="title is-5">@veritasphotgraphy.art</h5></a></div>
        <div style="text-align: center; padding-top: 0.5em;"><a href="https://github.com/Vladimir-G4" style="color: inherit;" target="_blank" rel="noopener noreferrer"><h5 class="title is-6">Made by <div style="text-decoration: underline; display: inline-block;">Vladimir Gutierrez</div></h5></a></div>
        <!-- </FOOTER> -->

    </div>
</template>
  