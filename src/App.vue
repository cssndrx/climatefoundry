<template>
  <v-app>
    <v-app-bar
      app
      color="white"
    >
      CLIMATE FOUNDRY
      <v-spacer></v-spacer>


    </v-app-bar>

<v-main class="main">
  <v-container>

<section style="height:100vh; padding-top: 10vh; text-align: center">
<h1>CLIMATE FOUNDRY</h1>
<p>We have 10 years to make climate ideas happen. Fast.</p>
<v-btn>SUBSCRIBE FOR UPDATES</v-btn>
</section>

<section style="max-width: 600px">
  <h1>ABOUT</h1>
  <p>
    In leaving Google to work on climate, we founded the 1800+ strong climate community workonclimate.org. We see that there is an immense amount of talent looking for direction. We started the Climate Foundry to facilitate rapid prototyping and team creation around non-obvious climate problems.
  </p>
  <p>
—Cassandra Xia, Eugene Kirpichov
  </p>


  <h1>EXPERIMENT</h1>
  <h2>Two month sprint</h2>
  <p>
  Want to try working on a climate idea that could turn into a company?
</p>

<p>
Apply below - especially if you have experience in business, in climate, or both! We will help form groups of people who might work well together. 
</p>

<p>
Each group will commit to spending 2 months refining and working on an idea. Groups will share access to domain experts, networks and resources.
</p>

<p>
If this works well, some groups will stick around and form companies. If this works really well, we’ll do it again!
</p>

<v-btn>SPRINT WITH US</v-btn>

<h1>INSPIRE</h1>
<h2>Ideas from experts</h2>

<p>
The best ideas in climate are non-obvious, often spottable only by experts in the weeds of a specific domain. 
</p>

<p>
Do you have an idea in your domain that you wish someone explored in depth? Submit it and let people work on it!
</p>

<p>
As an extra token of gratitude, any team that picks up your idea and starts a company will offer you a startup advisory role.
</p>

<v-btn>Drop an idea</v-btn>

<h2>Hire for a problem</h2>

<p>
We are currently accepting short-term consulting contracts in order to understand real world needs of decarbonizing industries, e.g. mining, manufacturing, logistics, financial risk. 
</p>

<p>
Do you have a climate-related problem that you think others may have as well? Tell us about your problem in a paragraph.
</p>

<v-btn>HIRE US</v-btn>


<h1>PARTNER</h1>
<h2>Advisors</h2>

<p>
We believe that maximum climate impact comes from tackling just the right problems. Join as an advisor to help teams identify one of these!
</p>

<p>
We especially seek advisors with partnerships with corporates, in legacy industries, and those who have domain expertise for identifying problems.
</p>

<p>
Advisors have the chance to shape, partner with, and invest in companies coming out of the foundry.
</p>

<v-btn>JOIN AS ADVISOR</v-btn>

<h2>Investors</h2>

<p>
We are building a community of investors looking to invest in non-obvious climate solutions. Investors provide a sniff test for helping us identify investable ideas coming out of the foundry, and help make necessary introductions to early stage companies. 
</p>

<p>
Join us as an investor for the chance to meet early-stage teams and advise companies coming out of the foundry.
</p>

<v-btn>JOIN AS INVESTOR</v-btn>


<h1>CURIOUS</h1>

<h2>Keep in touch</h2>

<p>
Want to see what happens? We will share the learnings of our first Climate Foundry cohort. Sign up to check in on us in a few months. No spam, we promise.
</p>

<v-btn>SUBSCRIBE</v-btn>
</section>

</v-container>
</v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped lang="scss">
* {
  font-family: 'Work Sans', sans-serif;
}

h1 {
  padding-top: 20vh;
  font-size: 6em;
}

h2 {
  font-weight: 300;
  font-size: 2.5em;
  padding-top: 5vh;
}
</style>