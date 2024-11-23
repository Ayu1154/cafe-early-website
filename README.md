* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  line-height: 1.6;
  background-color: #f9f9f9;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background-color: #ff7043;
  color: #fff;
}

header .logo h1 {
  font-size: 1.8rem;
}

header nav ul {
  list-style: none;
  display: flex;
}

header nav ul li {
  margin-left: 20px;
}

header nav ul li a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
}

.hero {
  text-align: center;
  background: url('https://source.unsplash.com/featured/?food') no-repeat center center/cover;
  color: #fff;
  padding: 60px 20px;
}

.hero h2 {
  font-size: 2.5rem;
}

.hero p {
  margin: 20px 0;
  font-size: 1.2rem;
}

.hero .btn {
  padding: 10px 20px;
  background-color: #ff7043;
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

section {
  padding: 20px;
}

#menu .menu-items {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}

#menu .item {
  background-color: #fff;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  text-align: center;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #ff7043;
  color: #fff;
}
