# Session 4 - Designing tests - Lesson plan

## Learning objectives

By the end of the session students will be able to:

* Repeat mnemonics to retrieve heuristics and oracles
* Describe what a heuristic is
* Describe what an oracle is
* Apply using heuristics and oracles to a testing situation
* Correlate between heuristics and test ideas

### **Before the session**

Students will be recommended to view the following videos:

* Heuristics - [https://dojo.ministryoftesting.com/lessons/99-second-introduction-to-heuristics](https://dojo.ministryoftesting.com/lessons/99-second-introduction-to-heuristics)
* Oracles - [https://dojo.ministryoftesting.com/lessons/99-second-introduction-to-oracles](https://dojo.ministryoftesting.com/lessons/99-second-introduction-to-oracles)
* Biases - [https://dojo.ministryoftesting.com/dojo/lessons/99-second-introduction-to-biases-in-testing](https://dojo.ministryoftesting.com/dojo/lessons/99-second-introduction-to-biases-in-testing)

### **Schedule**

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Start time</b>
      </th>
      <th style="text-align:left"><b>End time</b>
      </th>
      <th style="text-align:left"><b>Activity</b>
      </th>
      <th style="text-align:left"><b>Mentor notes</b>
      </th>
      <th style="text-align:left"><b>Resources</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">6:30pm</td>
      <td style="text-align:left">6:35pm</td>
      <td style="text-align:left">
        <p><b>Introduction to the session</b>
        </p>
        <ul>
          <li>Ground rules</li>
          <li>What we are covering tonight</li>
          <li>Other business</li>
        </ul>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">None</td>
    </tr>
    <tr>
      <td style="text-align:left">6:35pm</td>
      <td style="text-align:left">6:50pm</td>
      <td style="text-align:left">
        <p><b>Exploratory testing exercise<br /></b>
        </p>
        <p>Groups are given a product and a charter to test by the clinic hosts.
          <br
          />
        </p>
        <p>They are asked to note down their test ideas</p>
      </td>
      <td style="text-align:left">
        <p>Clinic hosts will provide charters and a product.
          <br />
        </p>
        <p>Let the students explore and generate ideas. Note down ideas they came
          up with for future reference.
          <br />
        </p>
        <p>For those new to ET help by introducing the subject</p>
      </td>
      <td style="text-align:left">
        <p>Clinic hosts provide link to a page with a basic feature
          <br />
        </p>
        <p><a href="http://the-internet.herokuapp.com/login">http://the-internet.herokuapp.com/login</a>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">6:50pm</td>
      <td style="text-align:left">7:00pm</td>
      <td style="text-align:left">
        <p><b>Big group discussion<br /></b>
        </p>
        <p>Questions for the groups:</p>
        <ul>
          <li>How did that go?</li>
          <li>What ideas did you come up with?</li>
          <li>How did you come up with your ideas?</li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>Use the fifteen second rule</p>
        <ul>
          <li>Sit back and let the students submit ideas.</li>
          <li>If nobody speaks for 15 seconds then say something that might stem new
            ideas</li>
        </ul>
      </td>
      <td style="text-align:left">None</td>
    </tr>
    <tr>
      <td style="text-align:left">7:00pm</td>
      <td style="text-align:left">7:15pm</td>
      <td style="text-align:left">
        <p><b>Whiteboard session<br /></b>
        </p>
        <ul>
          <li>An introduction to Heuristics
            <br />What are they?</li>
          <li>Why do we need them?</li>
          <li>Examples
            <ul>
              <li>Mnemonics</li>
              <li>Cheat sheets</li>
              <li>Test Sphere</li>
            </ul>
          </li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>Use the fifteen second rule</p>
        <ul>
          <li>Sit back and let the students submit ideas.</li>
          <li>If nobody speaks for 15 seconds then say something that might stem new
            ideas</li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>Whiteboard</p>
        <p>Markers</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7:15pm</td>
      <td style="text-align:left">7:30pm</td>
      <td style="text-align:left">
        <p><b>Group exercise<br /></b>
        </p>
        <p>Groups are given another charter to test by the clinic hosts.
          <br />
        </p>
        <p>They are asked to explore once again, but this time using heuristics</p>
      </td>
      <td style="text-align:left">
        <p>Use Active listening to observe the students as they work.
          <br />
        </p>
        <p>Suggest heuristics you typically use and share any tips and tricks.</p>
      </td>
      <td style="text-align:left">
        <p>Cheat sheets</p>
        <p>Test Sphere</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7:30pm</td>
      <td style="text-align:left">7:45pm</td>
      <td style="text-align:left"><b>Food break</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">7:45pm</td>
      <td style="text-align:left">7:55pm</td>
      <td style="text-align:left">
        <p><b>Big group discussion<br /></b>
        </p>
        <p>Question for the group:</p>
        <ul>
          <li>How do we know when something is a bug?</li>
          <li>What sources of information can we use to inform our testing?</li>
        </ul>
      </td>
      <td style="text-align:left">
        <p>Use the fifteen second rule</p>
        <ul>
          <li>Sit back and let the students submit ideas.</li>
          <li>If nobody speaks for 15 seconds then say something that might stem new
            ideas</li>
        </ul>
      </td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">7:55pm</td>
      <td style="text-align:left">8:15pm</td>
      <td style="text-align:left">
        <p><b>Whiteboard session<br /></b>
        </p>
        <ul>
          <li>What are oracles?</li>
          <li>What oracles are there?</li>
        </ul>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">8:15pm</td>
      <td style="text-align:left">8:45pm</td>
      <td style="text-align:left">
        <p><b>Group exercise<br /></b>
        </p>
        <p>Discovering board game rules
          <br />
        </p>
        <p>Using heuristics for Oracles, Students will attempt to discover what the
          rules are for the game (including how many players and age limit)
          <br />
        </p>
      </td>
      <td style="text-align:left">
        <p>Mentor will bring or borrow a board game, removing any rules and the box
          in which it’s stored
          <br />
        </p>
        <p>Mentors should encourage students to use Oracles to explain why they have
          chosen a specific rule for a game</p>
      </td>
      <td style="text-align:left">Board game</td>
    </tr>
    <tr>
      <td style="text-align:left">8:45pm</td>
      <td style="text-align:left">8:55pm</td>
      <td style="text-align:left">
        <p><b>Debrief<br /></b>
        </p>
        <p>Students will be invited to feedback on their game and what rules they
          generated</p>
      </td>
      <td style="text-align:left">Encourage students to debrief on behalf of their team.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">8:55pm</td>
      <td style="text-align:left">9:00pm</td>
      <td style="text-align:left">
        <p><b>Wrap up<br /></b>
        </p>
        <p>Hosts will wrap up the session and offer additional activities to carry
          out after the session on the Ministry of Testing Club forum</p>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>