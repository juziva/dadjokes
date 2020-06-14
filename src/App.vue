<template>
  <div class="container">
    <Joke
      jokeText="The secret service isn't allowed to yell Get down! anymore when the president is about to be attacked. Now they have to yell Donald, duck!"
      photo="01"
    />
    <Joke
      jokeText="Why did the invisible man turn down the job offer? He couldn't see himself doing it."
      photo="02"
    />
    <Joke
      jokeText="I bought some shoes from a drug dealer. I don't know what he laced them with, but I was tripping all day!"
      photo="03"
    />
    <Joke
      jokeText="Did you hear the news? FedEx and UPS are merging. They’re going to go by the name Fed-Up from now on."
      photo="04"
    />
    <Joke
      jokeText="My daughter screeched, Daaaaaad, you haven't listened to one word I've said, have you!? What a strange way to start a conversation with me..."
      photo="05"
    />
    <Joke
      jokeText="My wife tried to unlatch our daughter's car seat with one hand and said, How do one armed mothers do it? Without missing a beat I replied, Single handedly."
      photo="06"
    />
    <Joke
      jokeText="When a dad drives past a graveyard: Did you know that's a popular cemetery? Yep, people are just dying to get in there!"
      photo="07"
    />
    <Joke
      jokeText="My friend keeps saying cheer up man it could be worse, you could be stuck underground in a hole full of water. I know he means well."
      photo="08"
    />
    <Joke
      jokeText="The fattest knight at King Arthur’s round table was Sir Cumference. He acquired his size from too much pi."
      photo="09"
    />
  </div>
</template>

<script>
import Joke from "./Joke.vue";

export default {
  name: "App",
  components: {
    Joke: Joke,
  },
};
</script>

<style scoped>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}

.container {
  max-width: 30rem;
  margin: 5rem auto;
}
</style>
