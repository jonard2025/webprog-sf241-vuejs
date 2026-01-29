<template>
  <div class="container">
    <h1>Personal Profile</h1>
    <p class="subtitle"><strong>WEBPROG SF241 – Introduction</strong></p>

    <h2>About Me</h2>
    <p>
      I am a dynamic, motivated, and highly accomplished professional student with a customer-centric approach and over four years of experience in client-facing roles across various industries, including Customer Service, Customer Success, Account Management, and administrative positions.
    </p>
    <p>
      I possess strong interpersonal skills and the ability to build and maintain long-term relationships with both internal and external stakeholders. I am fluent in English and Tagalog, with excellent written and verbal communication skills.
    </p>
    <p>
      I am a critical thinker with strong attention to detail, capable of working independently while also being a highly resourceful team player. I am proficient in Microsoft Office Suite and Google Workspace, and I can quickly adapt to new tools and technologies.
    </p>

    <h2>Education</h2>
    <p>
      <strong>Asia Pacific College</strong><br>
      Bachelor of Science in Computer Science<br>
      Specialization in Cybersecurity and Forensics
    </p>

    <h2>Interests</h2>
    <ul>
      <li>Cybersecurity</li>
      <li>Traveling</li>
      <li>Snorkeling</li>
      <li>Gaming</li>
    </ul>

    <h2>Personal Goal</h2>
    <p>
      To maintain focus, achieve my goals, and become successful in my chosen field.
    </p>

    <h2>Picture Gallery</h2>
    <img
      src="https://www.w3schools.com/tags/img_girl.jpg"
      alt="Profile Image"
      class="profile-img"
    >

    <footer>
      © 2026 | Personal Profile Web Page
    </footer>
  </div>
</template>

<script>
export default {
  name: "PersonalProfile"
};
</script>

<style scoped>
.container {
  max-width: 900px;
  margin: 40px auto;
  background: #ffffff;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  font-family: Arial, Helvetica, sans-serif;
  color: #333;
}

h1, h2 {
  color: #2c7a7b;
}

h1 {
  text-align: center;
  margin-bottom: 10px;
}

h2 {
  margin-top: 30px;
  border-bottom: 2px solid #e2e8f0;
  padding-bottom: 5px;
}

p {
  line-height: 1.6;
}

ul {
  list-style-type: square;
  margin-left: 20px;
}

.subtitle {
  text-align: center;
  margin-bottom: 30px;
}

.profile-img {
  display: block;
  margin: 20px auto;
  border-radius: 10px;
  width: 300px;
  height: auto;
}

footer {
  text-align: center;
  margin-top: 30px;
  font-size: 0.9em;
  color: #666;
}
</style>

<!-- External CSS (optional) -->
<style src="./css/personalprofile.css"></style>
