<template>

    <div class="mt-5 card p-1 bg-white shadow rounded-0">
      <div class="card-body p-0">
        <h1 class="text-primary text-center my-3">ToDo Apps By Fharizal</h1>
        <Form/>
        <TodoWrap/>
        <Footer/>
      </div>
    </div>

</template>

<script>


import Form from '../components/Form.vue';
import TodoWrap from '../components/Todo/TodoWrap.vue';
import Footer from '../components/Footer.vue';

export default {
  components: {
    Form,
    TodoWrap,
    Footer,
  }
}
</script>

<style scoped></style>
