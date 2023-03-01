---
title: 'Contact'
date: 2018-02-22T17:01:34+07:00
---

Ready to experience the magic of cloud-connected lighting? Contact RainbowLabs today to schedule a consultation. Our team of experts will work with you to design a custom installation that meets your specific needs and exceeds your expectations.

{{< rawhtml >}}
<style>
form {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 80%;
  margin: 0 auto;
}

label {
  font-weight: bold;
  margin-bottom: 0.5rem;
}

input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 0.5rem;
  margin-bottom: 1rem;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1rem;
}

input[type="submit"] {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  font-size: 1rem;
  cursor: pointer;
  transition: all 0.3s ease;
}

input[type="submit"]:hover {
  background-color: #0062cc;
}
</style>

<form action="mailto:contact@cloud.rainbowlabs.de" method="post" enctype="text/plain">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="subject">Subject:</label>
    <input type="text" id="subject" name="subject" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="5" required></textarea>

    <input type="submit" value="Send">
</form>
{{< /rawhtml >}}