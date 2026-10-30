/* ShopWise AI - Main Design */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #080d1c;
  color: #ffffff;
}

.app {
  min-height: 100vh;
  background: radial-gradient(circle at top, #18264a, #080d1c 65%);
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 8%;
  border-bottom: 1px solid #263453;
  background: rgba(10, 17, 35, 0.9);
}

.navbar h2 {
  font-size: 27px;
  color: #ffffff;
}

.navbar h2 span {
  color: #8b7cff;
}

.navbar p {
  color: #aab5d0;
  font-size: 14px;
  margin-top: 5px;
}

.main {
  width: 90%;
  max-width: 1100px;
  margin: auto;
  padding: 75px 0;
}

.hero {
  text-align: center;
  max-width: 850px;
  margin: auto;
}

.tag {
  display: inline-block;
  padding: 10px 18px;
  border: 1px solid #6657dc;
  border-radius: 30px;
  background: #211b4a;
  color: #b7adff;
  font-size: 12px;
  font-weight: bold;
  letter-spacing: 1px;
  margin-bottom: 25px;
}

.hero h1 {
  font-size: clamp(38px, 6vw, 65px);
  line-height: 1.15;
  margin-bottom: 22px;
}

.hero h1 span {
  color: #9a8cff;
}

.hero > p {
  color: #aab5d0;
  font-size: 17px;
  line-height: 1.7;
  margin-bottom: 35px;
}

.search-box {
  display: flex;
  gap: 12px;
  max-width: 750px;
  margin: 0 auto;
  padding: 10px;
  border: 1px solid #35466d;
  border-radius: 16px;
  background: #111b33;
}

.search-box input {
  flex: 1;
  min-width: 0;
  padding: 16px;
  border: none;
  outline: none;
  color: white;
  background: transparent;
  font-size: 16px;
}

.search-box input::placeholder {
  color: #8290ad;
}

.search-box button {
  padding: 15px 25px;
  border: none;
  border-radius: 10px;
  background: linear-gradient(135deg, #7565ff, #a05bff);
  color: white;
  font-weight: bold;
  cursor: pointer;
  transition: 0.2s;
}

.search-box button:hover {
  transform: translateY(-2px);
  opacity: 0.9;
}

.results {
  margin-top: 65px;
}

.results h2 {
  font-size: 25px;
  margin-bottom: 25px;
}

.results article {
  padding: 24px;
  margin-bottom: 16px;
  border: 1px solid #2b3a5c;
  border-radius: 15px;
  background: #111b33;
  transition: 0.2s;
}

.results article:hover {
  border-color: #8373ff;
  transform: translateY(-3px);
}

.results article h3 {
  font-size: 19px;
  margin-bottom: 12px;
}

.results article p {
  color: #aab5d0;
  line-height: 1.6;
  margin-bottom: 12px;
}

.results article a {
  color: #a99cff;
  text-decoration: none;
  font-weight: bold;
}

.results article a:hover {
  text-decoration: underline;
}

footer {
  text-align: center;
  padding: 25px;
  border-top: 1px solid #263453;
  color: #8794b0;
  font-size: 13px;
}

@media (max-width: 600px) {
  .navbar {
    padding: 18px 5%;
  }

  .main {
    width: 92%;
    padding: 50px 0;
  }

  .search-box {
    flex-direction: column;
  }

  .search-box button {
    width: 100%;
  }

  .hero > p {
    font-size: 15px;
  }
}
