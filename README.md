CSS Styling
body {
        background-color: black;
        font-family: "poppins", sans-serif;
      }
      nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 70px;
        margin-bottom: 11rem;
      }
      nav ul {
        display: flex;
        justify-content: space-around;
        align-items: center;
      }
      nav ul li {
        color: yellow;
        list-style: none;
        margin: 20px;
        font-size: 20px;
        font-weight: bolder;
      }
      nav ul li a {
        text-decoration: none;
        color: rgb(255, 0, 0);
        border: 4px solid black;
        font-size: 25px;
        transition: 0.5s;
      }
      ul li a:hover {
        cursor: pointer;
        transition: all 0.5s ease;
      }
      ul li a:active {
        color: lime;
      }
      main {
        display: flex;
        justify-content: space-around;
      }
      .Title {
        width: 550px;
        height: 150px;
        font-size: 46px;
        color: white;
      }
      .name {
        color: aqua;
      }
      #content {
        color: lime;
      }
      section p {
        color: lime;
        font-size: 2rem;
        display: flex;
      }
      .About {
        margin: 50px;
      }
      h1 {
        text-align: center;
        color: white;
        font-weight: bolder;
      }
      main {
        margin-bottom: 300px;
      }
      .Contact {
        text-align: center;
        font-weight: bolder;
      }
      .myself {
        border: 5px solid lime;
        border-radius: 20px;
        padding: 10px;
        margin: 10px;
        background-color: lime;
        color: black;
      }
      .info {
        width: 500px;
        height: 200px;
        color: lime;
        background-color: red;
        border: 3px solid red;
        border-radius: 20px;
        font-weight: bolder;
        font-size: larger;
      }
      .Contact {
        margin: 50px;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .Links {
        display: flex;
        justify-content: space-around;
      }
      .insta,
      .facebook,
      .youtube {
        width: 200px;
        height: 200px;
        border: 5px solid red;
        background-color: lime;
        border-radius: 50%;
      }
      HTML Structure.
      <header>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">Links</a></li>
          <li><a href="#">Projects</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <div class="Title">
        Hi, this is <span class="name">Toheed,</span> I am a
        <span id="content"></span>
      </div>
      <div class="Photo"></div>
    </main>
    <section class="About">
      <h1>About Me</h1>
      <p class="myself">
        As I told you before, My name is Toheed Ur Rehman i live in Bhopal and
        as far as my qualification is concern, right now i am completing my
        Batchler degree in Business Administration from Indira Priyadarshini
        College (IPC) Bhopal. I am a Web Developer, Web Designer by using
        JavaScript, React.js, Bootstrap, Github and many more. I have completed
        my Higher Education form Demonstration Multipurpose School Reginal
        Institute Bhopal, A part form this i have also learnt the Web
        Development course from G.I.S.T Education accedemy in Bhopal.
      </p>
    </section>
    <section class="Contact">
      <div class="info">
        <h1 class="Contact">Contact Me</h1>
        <span class="Email">Email </span>Urrehmantoheed97@gmail.com
        <br />
        <span class="Phone">Phone </span>
        <br />
        <span class="Address">Address </span>
      </div>
    </section>
    <section class="Links">
      <div class="insta"></div>
      <a href="https://www.instagram.com/toheedurrehma/">@toheedurrehma</a>
      <div class="facebook"></div>
      <a href="#"></a>
      <div class="insta"></div>
    </section>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
      var typed = new Typed("#content", {
        strings: [
          "Web Developer",
          "Web Disigner",
          "JavaScript Developer",
          "React Developer",
        ],
        typeSpeed: 50,
      });
