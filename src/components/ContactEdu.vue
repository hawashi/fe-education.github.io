<template>
  <!-- contact section starts  -->

  <section class="contact" id="contact">
    <h1 class="heading"><span>contact</span> us</h1>

    <div class="row">
      <div class="image">
        <img src="images/contact-img.svg" alt="" />
      </div>

      <form action="" method="post">
        <span>your name</span>
        <input
          type="text"
          required
          placeholder="enter your full name"
          maxlength="50"
          name="name"
          class="box"
        />
        <span>your email</span>
        <input
          type="email"
          required
          placeholder="enter your valie email"
          maxlength="50"
          name="email"
          class="box"
        />
        <span>your number</span>
        <input
          type="number"
          required
          placeholder="enter your valie number"
          max="9999999999"
          min="0"
          name="number"
          class="box"
          onkeypress="if(this.value.length == 10) return false;"
        />
        <span>select course</span>
        <select name="couses" class="box" required>
          <option value="" disabled selected>select the course --</option>
          <option value="web developement">web developement</option>
          <option value="science and biology">science and biology</option>
          <option value="engineering">engineering</option>
          <option value="digital marketing">digital marketing</option>
          <option value="graphic design">graphic design</option>
          <option value="teaching">teaching</option>
          <option value="social studies">social studies</option>
          <option value="data analysis">data analysis</option>
          <option value="artificial intelligence">
            artificial intelligence
          </option>
        </select>
        <span>select gender</span>
        <div class="radio">
          <input type="radio" name="gender" value="male" id="male" />
          <label for="male">male</label>
          <input type="radio" name="gender" value="female" id="female" />
          <label for="female">female</label>
        </div>
        <input type="submit" value="send message" class="btn" name="send" />
      </form>
    </div>
  </section>

  <!-- contact section ends -->
</template>

<script>
export default {
  name: "ContactEdu",
};
</script>
