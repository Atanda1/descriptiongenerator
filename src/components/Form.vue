<template>
  <div class="inner__container__form">
    <h6 class="inner__container__form__label">Role</h6>
    <select name="Role" id="role" class="inner__container__form__dropdown">
      <option value="Select job role">Select job role</option>
      <option value="Frontend developer">Frontend developer</option>
    </select>
    <h6 class="inner__container__form__label">Company name</h6>
    <input
      placeholder="Enter company name"
      class="inner__container__form__input"
    />
    <h6 class="inner__container__form__label">Company website</h6>
    <input
      placeholder="Enter company website"
      class="inner__container__form__input"
    />
    <h6 class="inner__container__form__label">Years of experience</h6>
    <select
      name="experience"
      id="role"
      class="inner__container__form__dropdown"
    >
      <option value="Select job role">Select years of experience</option>
      <option value="1">1</option>
    </select>
    <h6 class="inner__container__form__label">Job location</h6>
    <select
      name="experience"
      id="role"
      class="inner__container__form__dropdown"
    >
      <option value="Select job location">Select job location</option>
      <option value="London">London</option>
    </select>
    <h6 class="inner__container__form__label">Employment type</h6>
    <select
      name="experience"
      id="role"
      class="inner__container__form__dropdown"
    >
      <option>Select employment type</option>
      <option>Contract</option>
    </select>
    <button class="inner__container__form__button">Generate</button>
  </div>
</template>

<script>
export default {
	name: "Form"
};
</script>

<style></style>
