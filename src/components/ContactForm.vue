<template>
  <form @submit.prevent="submitData">
    <div class="name-wrapper">
      <div class="form-container">
        <label for="firstName">First Name</label>
        <input
          type="text"
          name="firstname"
          id="firstname"
          placeholder="Mehmet"
        />
      </div>
      <div class="form-container">
        <label for="lastName">Last Name</label>
        <input type="text" name="lastname" id="lastname" placeholder="Ulga" />
      </div>
    </div>
    <div class="form-container">
      <label for="service">Service</label>
      <select name="product" id="product">
        <option value="website">Website</option>
        <option value="marketing">Marketing</option>
        <option value="marketing">Marketing</option>
        <option value="roboter">Roboter</option>
      </select>
    </div>
    <div class="form-container">
      <div class="checks">
        <label for="lowbugdet">lowbugdet</label>
        <input type="radio" name="budget" id="lowbugdet" />
      </div>
      <div class="checks">
        <label for="midbugdet">midbugdet</label>
        <input type="radio" name="budget" id="midbugdet" />
      </div>
      <div class="checks">
        <label for="heighbugdet">heighbugdet</label>
        <input type="radio" name="budget" id="heighbugdet" />
      </div>
    </div>
    <div class="form-container"></div>
  </form>
</template>

<script>
export default {
  name: "ContactForm",
  data() {
    return {};
  },

  methods: {
    name() {},
  },
};
</script>

<style scoped>
form {
  max-width: 500px;
}
label {
  display: block;
  color: #fff;
}
input,
select {
  display: block;
  text-align: left;
  width: 100%;
  max-width: 500px;
}

.name-wrapper,
.checks {
  display: flex;
  gap: 2rem;
  align-items: center;
}
.checks {
  justify-content: space-between;
}
</style>
