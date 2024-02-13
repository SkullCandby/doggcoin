<template>
  <header class="site-header">
    <nav>
      <ul>
        <li><a href="https://twitter.com/Babydoge_onSol" target="_blank"><i class="fab fa-twitter"></i> Twitter</a></li>
        <li><a href="https://dexscreener.com/solana/52mE2VRk8qGmLFWmRABYvGHxMwDMCM4jnXpJPazCJ2fu" target="_blank"><i class="fas fa-chart-line"></i> Chart</a></li>
        <li><a href="https://t.me/+erZHwqC7xlRhZjMy" target="_blank"><i class="fab fa-telegram-plane"></i> Telegram</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderSection',
}
</script>

<style scoped>
.site-header {
  background-color: #FFD870; /* Pink color */
  padding: 1rem;
}

.site-header nav ul {
  list-style-type: none;
  display: flex;
  justify-content: space-around;
}

.site-header nav ul li a {
  color: white;
  text-decoration: none;
  /* Add some spacing around the emoji for better visual appearance */
  padding: 0 0.5rem;
  font-weight: bold; /* Make link text bold */
}
</style>
