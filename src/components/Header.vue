<template>
  <div>
    <b-nav>
      <b-nav-item disabled>Fancy Quiz</b-nav-item>
      <b-nav-item disabled>Count {{numCorrect}} / {{numTotal}}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"]
};
</script>