<template>
  <form>
    <input type="text" name="" id="" placeholder="Search GitHub username" />
    <button>Search</button>
  </form>
</template>

<style scoped>
form {
  background-color: #ffffff;
  padding: 12px;
  border-radius: 8px;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 13px 27px -5px,
    rgba(0, 0, 0, 0.3) 0px 8px 16px -8px;

  display: flex;
  gap: 10px;
  justify-content: space-between;
}

input {
  flex: 1;
  outline: none;
  border: none;
  background-color: transparent;

  font-weight: 400;
  font-size: 1.125rem;

  padding: 12px;
}

button {
  color: #ffffff;
  background-color: var(--secondary);
  border: none;
  padding: 12px 24px;
  border-radius: 8px;

  font-weight: 700;
  font-size: 1.125rem;

  transition: all 150ms ease-in-out;

  &:hover {
    cursor: pointer;
    filter: brightness(1.2);
  }
}
</style>
