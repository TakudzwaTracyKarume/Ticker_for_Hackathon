<template>
  <div>
    <section class="start">
      <div class="ticker">
        <h1 class="ticker__heading white_text">Ticker</h1>
        <p class="ticker__paragraph white_text">
          One small tick for Alex, one task completed for you!
        </p>
      </div>
      <ImageWaiting />
      <h1 class="start__description mb-5 white_text">
        We have 1440 minutes every day... let's use the first few right
      </h1>
      <ImprovementMan class="mb-5" />
      <div class="story_text white_text">
        
        Welcome to Acornia...
        <!-- Anri you can probably put the first acorn person svg here-->
        <br>
        <br>
        Olaf is unflappable - on top of everything
        <br>
        Big 'man in town, he's got the bling
        <br>
        While everyone else is snoozing away
        <br>
        This early bird, gets his way
        <br>
        <br>
        Sal is straightforward - has the best assertion
        <br>
        Everything requires little or no exertion
        <br>
        Especially getting up in the morning
        <br>
        While others slumber, she goes exploring
        <br>
        <br>
        Now meet Alex....<!--Anri then the second one after this, probably-->
        <br>
        <br>
        Alex has dysania - a hard time waking up
        <br>
        And it's not because he was at the club
        <br>
        He needs your help getting up each day
        <br>
        I promise, he won't get in your way
        <br>
        <br>
        Born in Acornia, the land of his people
        <br>
        To others, he's considered feeble
        <br>
        Simply because he gets left behind
        <br>
        Every morning, in his bed, confined
        <br>
        ...
        <br>
        <br>
        Help him change his narrative from helpless to proactive. Get Alex through the morning AND unlock awesome 
        rewards and boosts after every task completed AND get things done for you!
        <br>
        <br>
        Let's go!...
      </div>
      <WinkFace />
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
import ImageWaiting from "@/components/ImageWaiting";
import ImprovementMan from "../components/ImprovementMan";
import WinkFace from "../components/WinkFace";

export default {
  name: "Home",
  components: {
    ImageWaiting,
    ImprovementMan,
    WinkFace,
  }
};
</script>

<style lang="scss">
@import "../sass/main.scss";
</style>
