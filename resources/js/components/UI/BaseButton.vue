<template>
  <button v-if="!link" :class="mode">
    <slot />
  </button>
  <router-link v-else :to="to" :class="mode">
    <slot />
  </router-link>
</template>
<script>
export default {
  name: 'BaseButton',
  props: {
    mode: {
      type: String,
      required: false,
      default: null
    },
    link: {
      type: Boolean,
      required: false,
      default: false
    },
    to: {
      type: null,
      required: false,
      default: String
    }
  }
}
</script>
<style scoped>

button,
a {
  display: inline-block;
  background-color: var(--first-color);
  color: #fff;
  padding: 1rem;
  border-radius: 0.5rem;
  font-weight: var(--font-medium);
  border: 0;
  text-transform: capitalize;

 /*  background-color: #fce61e;
  color: #262626;
  cursor: pointer;
  border-radius: 30px;
  font-weight: 700;
  line-height: 1;
  padding: 0.75rem 1.5rem;
  text-decoration: none;
  margin-right: 1rem;
  font-size: 14px;
  position: relative;
  transition: 0.3s ease;
  outline: 0;
  -webkit-box-shadow: 0 5px 10px rgb(4 0 252 / 20%) !important;
  box-shadow: 0 5px 10px rgb(4 0 252 / 20%) !important; */
}
button i,
a i {
  font-size: 1.25rem;
  margin-left: var(--mb-0-5);
  transition: var(--main-transition);
}
a:hover,
a:active,
button:hover,
button:active {
  background-color: var(--first-color-alt);
}
.flat {
    background-color: transparent;
    border: 1px solid #FFF;
    color: white;
}
.outline {
  background-color: transparent;
  border: 1px solid var(--first-color);
    color: var(--first-color);
    margin-top: var(--mb-0-25);
}
.flat:hover,
.flat:active,
.outline:hover,
.outline:active {
background-color: var(--input-color);
color: var(--first-color);
}
/* .button{
    display: inline-block;
    background-color: var(--first-color);
    color: #FFF;
    padding: 1rem;
    border-radius: .5rem;
    font-weight: var(--font-medium);
}

.button:hover{
    background-color: var(--first-color-alt);
}

.button__icon{
    font-size: 1.25rem;
    margin-left: var(--mb-0-5);
    transition: var(--main-transition) ;
}

.button--white{
    background-color: transparent;
    border: 1px solid #FFF;
    color: white;
}

.button--white:hover{
    background-color: #FFF;
    color: var(--first-color);
}

.button--flex{
    display: inline-flex;
    align-items: center;
}

.button--small{
    padding: .75rem 1rem;
}

.button--link{
    padding: 0;
    background-color: transparent;
    color: var(--first-color);
}

.button--link:hover{
    background-color: transparent;
    color: var(--first-color-alt);
} */

</style>
