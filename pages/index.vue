<script>
import Features from '@/components/features'

export default {
  name: 'Home',
  components: {
    Features
  }
}
</script>

<template lang="pug">
main
  section
    .hero
      .banner
        .logo
          img(
            src="/Panagiotidou_logo.png",
            alt="Παναγιωτίδου Ελίζα, Χειρουργός Οδοντίατρος Εξειδικευμένα Οδοντιατρεία στην Ορθοδοντική και την Χειρουργική Στόματος",
            width="600")
      .locations
        .box
          .location-outer
            svg.location-logo(viewBox="0 0 54.757 54.757")
              path(d="M27.557 12c-3.859 0-7 3.141-7 7s3.141 7 7 7 7-3.141 7-7-3.141-7-7-7zm0 12c-2.757 0-5-2.243-5-5s2.243-5 5-5 5 2.243 5 5-2.243 5-5 5z")
              path(d="M40.94 5.617A19.052 19.052 0 0027.38 0a19.05 19.05 0 00-13.56 5.617c-6.703 6.702-7.536 19.312-1.804 26.952L27.38 54.757 42.721 32.6c5.755-7.671 4.922-20.281-1.781-26.983zm.159 25.814L27.38 51.243 13.639 31.4C8.44 24.468 9.185 13.08 15.235 7.031 18.479 3.787 22.792 2 27.38 2s8.901 1.787 12.146 5.031c6.05 6.049 6.795 17.437 1.573 24.4z")
            address
              h3 Καβάλα
              br
              | Κωστή Παλαμά 8
              br
              .phone-outer
                a.phone(href="tel:+30-2510-839-144") 2510 839144

        .box
          .location-outer
            svg.location-logo(viewBox="0 0 54.757 54.757")
              path(d="M27.557 12c-3.859 0-7 3.141-7 7s3.141 7 7 7 7-3.141 7-7-3.141-7-7-7zm0 12c-2.757 0-5-2.243-5-5s2.243-5 5-5 5 2.243 5 5-2.243 5-5 5z")
              path(d="M40.94 5.617A19.052 19.052 0 0027.38 0a19.05 19.05 0 00-13.56 5.617c-6.703 6.702-7.536 19.312-1.804 26.952L27.38 54.757 42.721 32.6c5.755-7.671 4.922-20.281-1.781-26.983zm.159 25.814L27.38 51.243 13.639 31.4C8.44 24.468 9.185 13.08 15.235 7.031 18.479 3.787 22.792 2 27.38 2s8.901 1.787 12.146 5.031c6.05 6.049 6.795 17.437 1.573 24.4z")
            address
              h3 Χρυσούπολη
              br
              | 7ης Μεραρχίας 3
              br
              .phone-outer
                a.phone(href="tel:+30-25910-25850") 25910 25850
        .box
          .location-outer
            svg.location-logo(viewBox="0 0 54.757 54.757")
              path(d="M27.557 12c-3.859 0-7 3.141-7 7s3.141 7 7 7 7-3.141 7-7-3.141-7-7-7zm0 12c-2.757 0-5-2.243-5-5s2.243-5 5-5 5 2.243 5 5-2.243 5-5 5z")
              path(d="M40.94 5.617A19.052 19.052 0 0027.38 0a19.05 19.05 0 00-13.56 5.617c-6.703 6.702-7.536 19.312-1.804 26.952L27.38 54.757 42.721 32.6c5.755-7.671 4.922-20.281-1.781-26.983zm.159 25.814L27.38 51.243 13.639 31.4C8.44 24.468 9.185 13.08 15.235 7.031 18.479 3.787 22.792 2 27.38 2s8.901 1.787 12.146 5.031c6.05 6.049 6.795 17.437 1.573 24.4z")
            address
              h3 Θάσος
              br
              | Γαλλικής Αρχαιολογικής Σχολής
              br
              .phone-outer
                a.phone(href="tel:+30-25930-23581") 25930 23581
  hr
  //- section
    //- Features
</template>

<style lang="scss" scoped>
@import '~assets/style/_breakpoints.scss';
.hero {
  text-align: center;
}

.phone-outer {
  margin-top: 1.4em;
}

.phone::before {
  color: transparent;
  content: '\01F4DE'; // phone icon
  font-size: 1em;
  padding-right: 0.5em;
  text-shadow: 0 0 0 var(--link-color);
  vertical-align: middle;
}

.banner {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 3em;
}

.location-outer {
  text-align: center;
}

.logo {
  margin-bottom: 1em;
}

p {
  margin: 1em auto;
  font-style:italic;
  color: #999;
  font-size: 1em;
}

address {
  font-style: normal;
}

.eliza-logo {
  width: 80px;
  height: 80px;
}

.location-logo {
  width: 40px;
  height: 40px;
  margin-bottom: 1em;
}

.box {
  width: 100%;
  margin-bottom: 25px;
}

@include tablet-up {
  .banner {
    flex-direction: row;
    margin-bottom: 5em;
  }

  p {
    font-size: 1.2em;
  }

  .locations {
    display: flex;
    justify-content: space-around;
    max-width: 80%;
    margin: auto;
  }

  .box {
    margin: 20px;
    // max-width: 200px;
  }

  .logo {
    margin-right: 30px;
    margin-bottom: 0;
  }

  .info {
    text-align: initial;
  }

  .eliza-logo {
    width: 120px;
    height: 120px;
  }
}
</style>
