<template>
  <div class="hello">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">RemoTeacher</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
              >
                Про викладача
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Біографічні дані</a></li>
                <li><a class="dropdown-item" href="#">Досвід роботи</a></li>
                <li>
                  <a class="dropdown-item" href="#">Перелік технологій</a>
                </li>
                <li><a class="dropdown-item" href="#">Співпраця</a></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
                <li><hr class="dropdown-divider" /></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >Наукові роботи</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >Освітня діяльність</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >Календар подій</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >Завдання</a
              >
            </li>
          </ul>
        </div>
        <i class="fas fa-user"></i>
      </div>
    </nav>

    <main role="main" class="container mt-5">
      <!-- Content here -->
      <div class="card mt-3">
        <div class="card-body">
          This is some text within a card body. This is some text within a card
          body. This is some text within a card body. This is some text within a
          card body. This is some text within a card body. This is some text
          within a card body. This is some text within a card body. This is some
          text within a card body. This is some text within a card body. This is
          some text within a card body. This is some text within a card body.
        </div>
      </div>

      <div class="card mt-3">
        <div class="card-body">
          This is some text within a card body. This is some text within a card
          body. This is some text within a card body. This is some text within a
          card body. This is some text within a card body. This is some text
          within a card body. This is some text within a card body. This is some
          text within a card body. This is some text within a card body. This is
          some text within a card body. This is some text within a card body.
        </div>
      </div>

      <div class="card mt-3">
        <div class="card-body">
          This is some text within a card body. This is some text within a card
          body. This is some text within a card body. This is some text within a
          card body. This is some text within a card body. This is some text
          within a card body. This is some text within a card body. This is some
          text within a card body. This is some text within a card body. This is
          some text within a card body. This is some text within a card body.
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
	name: "HelloWorld",

	props: {
		msg: String,
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
