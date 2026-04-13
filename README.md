# Finals-Activity_AriasRaymond
ws-101

exercise 1:

<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Profile Page</title>
  </head>
  <body>
    <header>
      <nav class="nav-links">
        <div class="logo">RAYMOND</div>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#skill">Skills</a></li>
          <li><a href="#contact">Contacts</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section id="about">
        <h2>About Me</h2>
        <img src="images/Raymond.png" alt="Profile Picture" />
        <p>
         I am Raymond, a 1st college student pursuing my 
         passion in Information Technology. I’ve always been 
         curious about how technology works and how it can solve real-world problems.
        </p>
      </section>

      <section id="skill">
        <h2>My Skills</h2>
        <table>
          <tr>
            <th>Skill</th>
            <th>Level</th>
          </tr>
          <tr>
            <td>HTML</td>
            <td>Beginner</td>
          </tr>
          <tr>
            <td>CSS</td>
            <td>Beginner</td>
          </tr>
          <tr>
            <td>JavaScript</td>
            <td>Beginner</td>
          </tr>
        </table>
      </section>

      <section id="contact">
        <h2>Contact Me</h2>
        <form>
          <label>Name:</label>
          <input type="text" required /><br /><br />

          <label>Email:</label>
          <input type="email" required /><br /><br />

          <label>Message:</label><br />
          <textarea rows="5" required></textarea><br />

          <button type="submit">Send</button>
        </form>
      </section>
    </main>

    <footer>&copy; Raymond. All Rights Reserve</footer>
  </body>
</html>



exercise 2:

ml>
Raymond
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="style.css" />
    <title>Webpage</title>
  </head>

  <body>
    <header>
      <nav>
        <h1>Group6</h1>
        <ul>
          <li><a href="#image">Image</a></li>
          <li><a href="#table">Table</a></li>
          <li><a href="#form">Contact</a></li>
        </ul>
      </nav>
    </header>

    <section id="image">
      <div class="image-container">
        <a href="https://www.facebook.com/share/16Xhqx1SFa/" target="_blank">
          <img src="Images/Obis.jpg" alt="Obis" />
        </a>
        <a href="https://www.facebook.com/share/18y9pzWLyt/" target="_blank">
          <img src="Images/Monforte.jpg" alt="Monforte" />
        </a>
        <a href="https://www.facebook.com/share/1HEhwxQ2uv/" target="_blank">
          <img src="Images/Mazo.jpg" alt="Mazo" />
        </a>
        <a href="https://www.facebook.com/share/1Homexrzo5/" target="_blank">
          <img src="Images/Manzo.jpg" alt="Manzo" />
        </a>
        <a href="https://www.facebook.com/raymond.arias.161" target="_blank">
          <img src="Images/Arias.jpg" alt="Arias" />
        </a>
        <a href="https://www.facebook.com/share/1DdYSPQZbt/" target="_blank">
          <img src="Images/Arellano.jpg" alt="Arellano" />
        </a>
        <p>Click the image to view it in a new tab</p>
      </div>
    </section>

    <section id="table">
      <h2>Members</h2>
      <table>
        <tr>
          <th>Name</th>
          <th>Age</th>
          <th>Course</th>
        </tr>
        <tr>
          <td>Obis</td>
          <td>22</td>
          <td>BSIT</td>
        </tr>
        <tr>
          <td>Monforte</td>
          <td>19</td>
          <td>BSIT</td>
        </tr>
        <tr>
          <td>Mazo</td>
          <td>19</td>
          <td>BSIT</td>
        </tr>
        <tr>
          <td>Manzo</td>
          <td>21</td>
          <td>BSIT</td>
        </tr>
        <tr>
          <td>Arias</td>
          <td>22</td>
          <td>BSIT</td>
        </tr>
        <tr>
          <td>Arellano</td>
          <td>27</td>
          <td>BSIT</td>
        </tr>
      </table>
    </section>

    <section id="form">
      <h2>Contact Form</h2>
      <form>
        <label>Name:</label>
        <input type="text" required minlength="3" />

        <label>Email:</label>
        <input type="email" required />

        <label>Message:</label>
        <textarea required minlength="10"></textarea>

        <button type="submit">Submit</button>
      </form>
    </section>
  </body>
</html




















