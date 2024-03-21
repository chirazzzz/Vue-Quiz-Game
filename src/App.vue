<template>
  <div class="container">
    <header>
      <h1>Quizzes</h1>
      <input type="text" placeholder="Search..." />
    </header>
    <div class="cards-container">
      <div class="card">
        <img
          src="https://schoolsweek.co.uk/wp-content/uploads/2021/12/Maths-feat.jpg"
          alt="Picture of maths calculations"
        />
        <div class="card-text">
          <h2>Subject</h2>
          <p>15 questions</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  max-width: 1000px;
  margin: 0 auto;
}

header {
  margin-bottom: 0.625em;
  margin-top: 1.875em;
  display: flex;
  align-items: center;
}

header h1 {
  font-weight: bold;
  margin-right: 1.875em;
}

header input {
  border: none;
  background: rgba(128, 128, 128, 0.1);
  padding: 0.625em;
  border-radius: 0.313em;
}

.cards-container {
  display: flex;
  flex-wrap: wrap;
  margin-top: 2.5em;
}

/* CARD */
.card {
  width: 310px;
  overflow: hidden;
  border-radius: 2%;
  box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.1);
  margin-bottom: 2em;
  margin-right: 1.25em;
  cursor: pointer;
}

.card img {
  width: 100%;
  height: 190px;
  margin: 0;
}

.card .card-text {
  padding: 0 0.375em 0.375em;
}

.card .card-text h2 {
  font-weight: bold;
}
</style>
