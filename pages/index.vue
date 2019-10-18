<script>

export default {
}
</script>

<template lang="pug">
main.container
  section
    .hero
      .banner
        .logo
          svg.eliza-logo(viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg")
            g(id="Filled_outline" data-name="Filled outline")
            circle(cx="32" cy="32" fill="#96d1c7" r="29")
            circle(cx="32" cy="32" fill="#fff" r="25")
            path(d="m19.109 33.455a84.988 84.988 0 0 1 3.855 8.929c1.57 4.126 2.517 6.616 5.036 6.616 3 0 3-2.131 3-6 0-1.867.13-5 1-5s1 3.133 1 5c0 3.869 0 6 3 6 2.519 0 3.466-2.49 5.036-6.616a84.988 84.988 0 0 1 3.855-8.929c.235-.462.531-.961.843-1.489 1.066-1.796 2.266-3.831 2.266-5.966 0-6.271-3.869-11-9-11a10.289 10.289 0 0 0 -5.607 2.206 3.4 3.4 0 0 1 -2.786 0 10.289 10.289 0 0 0 -5.607-2.206c-5.131 0-9 4.729-9 11 0 2.135 1.2 4.17 2.266 5.966.312.528.608 1.027.843 1.489zm5.891-16.455a8.1 8.1 0 0 1 4.371 1.779 10.667 10.667 0 0 0 7.229 2.426 15.551 15.551 0 0 0 2.561-.219l-.33-1.972a12.113 12.113 0 0 1 -4.526-.044 2.541 2.541 0 0 0 .3-.176 8.127 8.127 0 0 1 4.395-1.794c3.991 0 7 3.869 7 9 0 1.587-1.056 3.373-1.987 4.948-.335.566-.651 1.1-.9 1.6a86.959 86.959 0 0 0 -3.942 9.128c-1.336 3.497-2.082 5.324-3.171 5.324-.905 0-1 0-1-4 0-3.387-.232-7-3-7s-3 3.613-3 7c0 4-.095 4-1 4-1.089 0-1.835-1.827-3.167-5.327a86.959 86.959 0 0 0 -3.942-9.128c-.253-.494-.569-1.031-.9-1.6-.935-1.572-1.991-3.358-1.991-4.945 0-5.131 3.009-9 7-9z")
            path(d="m32 62a30 30 0 1 0 -30-30 30.034 30.034 0 0 0 30 30zm0-58a28 28 0 1 1 -28 28 28.032 28.032 0 0 1 28-28z", fill="#5eb7b7")
            path(d="m16 31h-2v-2h-2v2h-2v2h2v2h2v-2h2z", fill="#fc7978")
            path(d="m20 43h-2v2h-2v2h2v2h2v-2h2v-2h-2z", fill="#fc7978")
            path(d="m47 40h-2v2h2v2h2v-2h2v-2h-2v-2h-2z", fill="#fc7978")
            path(d="m16 38h2v2h-2z", fill="#5eb7b7")
            path(d="m49 31h2v2h-2z", fill="#5eb7b7")
            path(d="m41 48h2v2h-2z", fill="#5eb7b7")
            path(d="m37.669 31.743-1.338-1.486c-4.254 3.828-8.485.156-8.664 0l-1.336 1.489a9.118 9.118 0 0 0 5.829 2.254 8.088 8.088 0 0 0 5.509-2.257z")
            path(d="m28 25h2v2h-2z")
            path(d="m34 25h2v2h-2z")
            path(d="m21.586 27h2.828v2h-2.828z", transform="matrix(.707 -.707 .707 .707 -13.062 24.464)", fill="#fc7978")
            path(d="m40 26.586h2v2.828h-2z" transform="matrix(.707 -.707 .707 .707 -7.79 37.192)", fill="#fc7978")
            path(d="m28 11h2v2h-2z", fill="#5eb7b7")
            path(d="m27 52h2v2h-2z", fill="#5eb7b7")
        .info
          h1 Ελίζα Ι. Παναγιωτίδου
          h2 Χειρουργός Οδοντίατρος
          p Εξειδικευμένα Οδοντιατρεία στην Ορθοδοντική και την Χειρουργική Στόματος
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
  section
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
  text-shadow: 0 0 0 #fc7978;
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
