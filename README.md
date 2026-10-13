/* Reset CSS cơ bản */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 5%;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 1.8rem;
    font-weight: bold;
    color: #2c3e50;
}

.logo span {
    color: #27ae60; /* Màu xanh lá biểu tượng cho xe buýt/môi trường */
}

.logo i {
    color: #27ae60;
    margin-right: 5px;
}

nav ul {
    list-style: none;
    display: flex;
    align-items: center;
}

nav ul li {
    margin-left: 1.5rem;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #27ae60;
}

.btn-login {
    background-color: #27ae60;
    color: #fff !important;
    padding: 8px 20px;
    border-radius: 20px;
}

.btn-login:hover {
    background-color: #219653;
}

/* Hero Section */
.hero {
    height: 80vh;
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?q=80&w=2069&auto=format&fit=crop') center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #fff;
}

.hero-content h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.search-box {
    display: flex;
    max-width: 600px;
    margin: 0 auto;
    background: #fff;
    border-radius: 30px;
    overflow: hidden;
}

.search-box input {
    flex: 1;
    padding: 15px 25px;
    border: none;
    outline: none;
    font-size: 1rem;
}

.search-box button {
    padding: 15px 30px;
    background-color: #27ae60;
    color: #fff;
    border: none;
    cursor: pointer;
    font-size: 1rem;
    font-weight: bold;
    transition: background 0.3s;
}

.search-box button:hover {
    background-color: #219653;
}

/* Features Section */
.features {
    padding: 5rem 5%;
    background-color: #f9f9f9;
    text-align: center;
}

.features h2 {
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #2c3e50;
}

.feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.feature-card {
    background: #fff;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    transition: transform 0.3s;
}

.feature-card:hover {
    transform: translateY(-10px);
}

.feature-card i {
    font-size: 3rem;
    color: #27ae60;
    margin-bottom: 1rem;
}

.feature-card h3 {
    margin-bottom: 1rem;
    color: #2c3e50;
}

/* Footer */
footer {
    text-align: center;
    padding: 2rem;
    background-color: #2c3e50;
    color: #fff;
}
