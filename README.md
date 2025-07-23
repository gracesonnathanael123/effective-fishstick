# effective-fishstick
WEB TECHNOLOGY LAB EXPERIMENT 2
HTML CODE 

TOPIC:VOLUNTEER REGISTRATION FORM

!DOCTYPE html>
<html>
    <head>
        <title>Volunteer Registration Form</title>
    </head>
    <body>
        <h1>Registration</h1>
        <form action="register.html" method="post">
            <fieldset>
                <legend>Personal Info</legend>
                <label for ="fullname">Enter your Full Name:</label><br>
                <input type="text" id="fullname" name="fullname" required><br><br>


                <label for="dob">Enter Date of Birth:</label><br>
                <input type="data" id="dob" name="dob" required><br><br>

                <label for="gender">Please select your gender:</label><br>
                <input type="radio" id="male" name="gender" value="male"> Male
                <input type="radio" id="female" name="gender" value="female"> Female
                <input type="radio" id="Prefer not to say" name="gender" value="Prefer not to say"> Prefer not to say <br><br>


                <label for="phone">Enter your Phone Number:</label><br>
                <input type="tel" id="phone" name="phone" required><br><br>


                <label for="email">Enter your email:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="address">Enter your Address:</label><br>
                <textarea id="address" name="address" rows="3" cols="30"></textarea><br><br>
            </fieldset>

            <fieldset>
                <legend>Emegency Contact Info</legend>
                <label for="emergency_contact">Enter Altenrnate Contact(in case of emergency):</label><br><br>
                <input type="text" id="emergency_contact" name="emergency_contact"><br>

                <label for="emergency_phone">Enter Alternate Phone Number:</label><br><br>
                <input type="tel" id="emergency_phone" name="emergency_phone"><br>
            </fieldset>

            <fieldset>
                <legend>Availability:</legend>
                <p>Select Available Days:</p>
                <input type="checkbox" name="days" value="Monday">Monday
                <input type="checkbox" name="days" value="Tuesday">Tuesday
                <input type="checkbox" name="days" value="Wednesday">Wednesday
                <input type="checkbox" name="days" value="Thursday">Thursday
                <input type="checkbox" name="days" value="Friday">Friday

                <label for="time_preference">
                    Choose your preferred time:
                </label><br>
                <select id="time_preference" name="time_preference">
                    <option value="Forenoon">Forenoon</option>
                    <option value="Afternoon">Afternoon</option>
                </select><br><br>
            </fieldset>

            <fieldset>
                <legend>Final Submission</legend>
                <input type="submit" value="Submit Registration">
            </fieldset>
        </form>
    </body>
</html>
