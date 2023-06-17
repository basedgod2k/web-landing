<template>
  <Overlay>
    <div class="card">
      <header class="search_header">
        <form class="search_form">
          <input
            class="search_input"
            type="text"
            placeholder="Search FDG docs"
          />
        </form>
      </header>
    </div>
  </Overlay>
</template>

<style scoped>
.card {
  background-color: #201e1b;
  border-radius: 6px;
  padding: 12px;
  max-width: 568px;
  width: 568px;
  margin: 64px auto auto;
  z-index: 11;
  position: relative;
}
.search_header {
  width: 100%;
}
.search_form {
  border-radius: 4px;
  background-color: black;
  width: 100%;
  position: relative;
  display: flex;
  height: 56px;
  border: 2px solid #1aadff;
  padding: 0 12px;
}
.search_input {
  width: 100%;
  background-color: transparent;
  height: 100%;
  appearance: none;
  border: 0;
  color: #f5f6f7;
  font: inherit;
  font-size: 1.2em;
  outline: none;
}
</style>
