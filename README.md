<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Form Page</title>
    <link href="form.html" rel="stylesheet"
  </head>
  <body>
    <nav>
      <ul>
        <li><a href="#">Form Page</a></li>
        <li><a href="./index.html">Home Page</a></li>
      </ul>
    </nav>

    <h1>Application Form</h1>
    <p>Fill in your deatils correctly</p>

    <form action="process_form.phd" method="post">
      <div>
        <label for="name">First Name*</label><br />
        <input
          type="text"
          id="name"
          name="name"
          placeholder="Enter first name"
          required
        /><br /><br />
      </div>

      <div>
        <label for="name">Last Name*</label><br />
        <input
          type="text"
          id="name"
          name="name"
          placeholder="Enter last name"
          required
        /><br /><br />
      </div>

      <div>
        <label for="gender">Gender*</label><br />
        <select id="gender" name="gender" required>
          <option disabled selected value="Select gender">Select gender</option>
          <option value="Male">Male</option>
          <option value="Female">Female</option>
          <option value="Other">Other</option>
        </select>
        <br /><br />
      </div>

      <div>
        <label for="dob">Date of Birth</label>
        <input type="date" id="dob" name="dob" /><br /><br />
      </div>

      <div>
        <label for="email">Email Address*</label><br />
        <input
          type="email"
          id="email"
          name="email"
          placeholder="Enter email address"
          required
        /><br /><br />
      </div>

      <div>
        <label for="education">Education Level*</label><br />
        <select id="education" name="level">
          <option disabled selected value="Select education level">Select level of education</option>
          <option value="level">Secondary Education</option>
          <option value="level">Primary Education</option>
          <option value="level">Bachelor's Degree</option>
          <option value="level">Master's Degree</option></select><br /><br />
      </div>

      <div>
        <label for="country">Country*</label><br />
        <select id="country" name="country">
          <option disabled selected value="Select country">Select your country</option>
          <option value="country">Nigeria</option>
          <option value="country">USA</option>
          <option value="country">Kenya</option>
          <option value="country">Ghana</option></select><br /><br />
      </div>

      <div>
        <label for="state">State/City of Residence*</label><br />
        <select id="state" name="state">
          <option disabled selected value="Select state">Enter your state of residence</option>
          <option value="state">Enugu</option>
          <option value="state">Lagos</option>
          <option value="state">Ebonyi</option>
          <option value="state">Benin</option></select><br /><br />
      </div>

      <div>
        <label for="employment">Employment Status*</label><br />
        <select id="employment" name="work">
          <option disabled selected value="Select employment status">
            Select employment status
          </option>
          <option value="work">Self-Employed</option>
          <option value="work">Unemployed</option>
          <option value="work">Employed</option></select
        ><br /><br />
      </div>

      <div>
        <label for="number">Phone Number*</label><br />
        <input
          type="number"
          id="number"
          name="number"
          placeholder="Enter phone number"
          required
        /><br /><br />
      </div>

      <div>
        <label for="school">Choose School*</label><br />
        <select id="school" name="school">
          <option disabled selected value="Select school">Select School</option>
          <option value="school">School Of Engineering</option>
          <option value="school">School Of Marketing</option>
          <option value="school">School Of Product</option></select
        ><br /><br />
      </div>

      <div>
        <label for="course">Choose Course*</label><br />
        <select id="course" name="course">
          <option disabled selected value="Select course">Choose Course Of Study</option>
          <option value="school">Frontend Engineering</option>
          <option value="school">Backend Engineering</option>
          <option value="school">Cloud Engineering</option></select
        ><br /><br />
      </div>

      <p>How did you hear about us?</p><br />

      <div>
        <select id="course" name="channel">
          <option disabled selected value="Select channel">Select channel</option>
          <option value="school"></option>
          <option value="school"></option>
          <option value="school"></option></select
        ><br /><br />
      </div>

      <div>
        <label for="scholarship">scholarship/Discount Code (optional)*</label><br />
        <select id="course" name="course">
          <option disabled selected value="scholarship/Discount Code">scholarship/Discount Code</option>
          <option value="school">Livinus</option>
          <option value="school">Caleb</option>
          <option value="school">Onah</option></select
        ><br /><br />
      </div>


      <p>
        By clicking continue, I agree to
        <a href="http://Terms of use">Terms of Use</a> and acknowledge that I
      </p>
      <p>have read the <a href="http://Privacy Policy">Privacy Policy</a></p>
      <button>Proceed</button><br /><br />

      <p>Already have an account? <a href="http://portal.altschoolafrica.com">Sign In</a></p>
    </form>
  </body>
</html>
