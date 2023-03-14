<template>
  <div class="error-404">
    <h1>Oops! Page not found.</h1>
    <p>Sorry, the page you were looking for could not be found.</p>
    <router-link to="/">Go back to the homepage</router-link>
  </div>
</template>

<style>
.error-404 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
}

.error-404 h1 {
  font-size: 4rem;
  margin-bottom: 1rem;
  color: White;
  text-align: center;
  font-weight: 200;
}

.error-404 p {
  font-size: 1rem;
  color: white;
  text-align: center;
  margin-bottom: 3rem;
}

.error-404 a {
  font-size: 1rem;
  padding: 1rem 2rem;
  background-color: purple;
  color: #fff;
  text-decoration: none;
  border-radius: 2rem;
  transition: background-color 0.3s ease;
}

.error-404 a:hover {
  background-color: #444;
}
</style>
