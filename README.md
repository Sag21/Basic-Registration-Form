# Basic-Registration-Form
<!DOCTYPE html>
<html>

<head>
    <title> Registration Form </title>
</head>
<style>
    table{
        margin: auto;
        border-style:double;
        background-color: azure;
    }
</style>
<body>
    
        <table>
            <tr>
                <th>
                    <h1 style="background-color:powderblue;">
                        <marquee direction="left"> REGISTRATION FORM </marquee>
                    </h1>
                </th>
            </tr>


            <form>

                <tr>
                    <td><label for="first_name">First name:</label><input type="text" placeholder="Enter your name"
                            required><br></td>
                </tr>
                <tr>
                    <td><label for="last_name">Last name:</label><input type="text" placeholder="Enter your surname"
                            required><br></td>
                </tr>
                <tr>
                    <td><label for="phone_no">Phone no.:</label><input type="number" placeholder="Enter your phone no."
                            required><br></td>
                </tr>
                <tr>
                    <td><label for="email">Email:</label><input type="text" placeholder="Example@gmail.com"
                            required><br></td>
                </tr>

                <tr>
                    <td>
                        <p><label for="gender">Select Gender:</label><br>
                            <input type="radio" name="gender"> Male
                            <input type="radio" name="gender"> Female
                        </p>
                    </td>
                </tr>

                <tr>
                    <td>
                        <label for="cast">Cast:</label> <br>
                        <input type="radio" name="cast"> Open
                        <input type="radio" name="cast"> OBC
                        <input type="radio" name="cast"> EBC
                        <input type="radio" name="cast"> SC
                        <input type="radio" name="cast"> NT
                    </td>
                </tr>

                <tr>
                    <td><label for="D.O.B">D.O.B:</label><input type="date" min="2000-01-01" max="2023-01-01">
                        <br>
                    </td>
                </tr>

                <tr>
                    <td> <label for="state">State:</label>
                        <select name="state" id="state">
                            <option value="Assam">Assam</option>
                            <option value="Goa">Goa</option>
                            <option value="Gujarat">Gujarat</option>
                            <option value="Karnataka">Karnataka</option>
                            <option value="Maharashtra">Maharashtra</option>
                            <option value="Punjab">Punjab</option>
                        </select>
                    </td>
                </tr>

                <tr>
                    <td>
                        <p><label for="address">Address:</label> <textarea id="address" name="address"
                                row="3">  </textarea>
                            <label for="pincode">Pincode:</label> <input type="number" maxlength="6">
                        </p>
                    </td>
                </tr>

                <tr>
                    <td>
                        <p><button type="submit" value="submit" style="background-color:rgb(179, 231, 237);"> SUBMIT
                            </button></p>
                    </td>
                </tr>


            </form>
        </table>

</body>

</html>
