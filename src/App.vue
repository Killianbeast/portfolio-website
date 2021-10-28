<template>
  <Header title="Home Page"/>
  <SideBar class="sidenav"/>
  
  <div class="flexbox-container">
    <div class="item" id="AboutMe">
      <h1>About Me</h1>
      <p>Tell me. For whom do you fight?

      Hmph! How very glib. And do you believe in Eorzea? Eorzea's unity is forged of falsehoods. Its city-states are built on deceit. And its faith is an instrument of deception.

      It is naught but a cobweb of lies. To believe in Eorzea is to believe in nothing. In Eorzea, the beast tribes often summon gods to fight in their stead--though your comrades only rarely respond in kind. Which is strange, is it not?

      Are the "Twelve" otherwise engaged? I was given to understand they were your protectors. If you truly believe them your guardians, why do you not repeat the trick that served you so well at Carteneau, and call them down? They will answer--so long as you lavish them with crystals and gorge them on aether. Your gods are no different than those of the beasts--eikons every one. Accept but this, and you will see how Eorzea's faith is bleeding the land dry.

      Nor is this unknown to your masters. Which prompts the question: Why do they cling to these false deities? What drives even men of learning--even the great Louisoix--to grovel at their feet? The answer? Your masters lack the strength to do otherwise! For the world of man to mean anything, man must own the world. To this end, he hath fought ever to raise himself through conflict--to grow rich through conquest. And when the dust of battle settles, is it ever the strong who dictate the fate of the weak.

      Knowing this, but a single path is open to the impotent ruler--that of false worship. A path which leads to enervation and death. Only a man of power can rightly steer the course of civilization. And in this land of creeping mendacity, that one truth will prove its salvation.

      Come, champion of Eorzea, face me! Your defeat shall serve as proof of my readiness to rule! It is only right that I should take your realm. For none among you has the power to stop me!
      </p>
    </div>

    <div class="item" id="Projects">
      <h1>Projects</h1>
      <p>"Shit...seems like I've fallen to you, all my big words crumble to nothing, heh, funny. Anyways, I'm sorta glad you beat me, so, I work for the East. I was gaining the West's trust so I could take them down with one move, I was damn close as well. But, there are a few Western spy outpost around here, good luck taking down those bastards, oh, and Rinkah, if I got you pregnant, name our kiddo...Minerva.." and with that, Tiberius dies.</p>
    </div>

    <div class="item" id="Resume">
      <h1>Resume</h1>
      <p>Glacierbust is a 4 level schooner made of the finest snakewood, whose top speed is 35 knots. It was stolen from Alessagio Kong and market price for it was worth 700,000,000 berri when it was being sold. It has 3 masts with one jolly roger flag on top of the central mast. It has 18 cannons on each side with powerful cannonballs as powerful as Buggy the Clown's "Buggy Balls." On the deck is the garden and the steering wheel. On it's first level (right below the deck) is the kitchen, bedrooms (one for boys one for girls), and the navigation room. On the second floor (further towards the bottom) is workshop, the infirmary and the library. On the 3rd floor is the training room, engine room and the bathroom/showers. On the 4th floor is the storage/treasure room.To each of these floors is a spiral staircase going through all of them. </p>
    </div>

    <div class="item" id="Contact">
      <h1>Contact Me</h1>
      <p>I was at Toys R Us with my 2 year old son shopping for Mickey Mouse toys when one of them started moving! To my shock, it was LeMickey Hamilton! My son turned to me and said "Dad, is it true that LeFraud has no real championships?" I said "Yes son, and he will never win a real championship." LeBozo ran away crying</p>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'

import SideBar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Header,
    SideBar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@200&display=swap');
@import './assets/styles/flexbox.css';
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Roboto Mono', monospace;
}
</style>

