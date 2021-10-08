<template>
  <h1>For Loop List</h1>
  <ul>
    <li v-for="item in friends" :key="item">{{ item }}</li>
  </ul>
  <br />
  <h1>For Array Objects</h1>
  <ol>
    <li v-for="item in user" :key="item.name">
      Name is <b>{{ item.name }}</b> email address <b>{{ item.email }}</b>
    </li>
  </ol>
</template>

<script>
export default {
  loop: "For_Loop",
  data() {
    return {
      friends: ["sabir", "subhan", "nabeel"],
      user: [
        {
          name: "sabir",
          email: "sabir@test.com",
        },
        {
          name: "subhan",
          email: "subhan@test.com",
        },
        {
          name: "nabeel",
          email: "nabeel@test.com",
        },
      ],
    };
  },
};
</script>
