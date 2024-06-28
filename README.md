<html>
    <head><title> good vibes form </title></head>
    <body>
        <h1 align="center"> GOOD VIBES FORM </h1>
        <h2 align="center"> Tell us something positive that happened to you today</h2>
        <br>
        <br>
        <form > 
            <table>
                <tr>
                   <td>  <label for="name"> Name</label> </td>
                   <td> <input type="text" name="name"></td>
                </tr>
                <tr> 
                    <td> <label for="email"> Email</label></td>
                    <td> <input type="email"></td>
                </tr>
                <tr>
                    <td> <label > On scale of 1-10 ,how good was it</label></td>
                    <td> <input type="number" name="rating" min="1" max="10"></td>
                </tr>
                <tr>
                    <td> <label for="location"> where did it happen?</label></td>
                    <td>
                         <select>
                            <option value="null"> select</option>
                             <option value="home"> home</option>
                            <option value="college"> college </option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td><label for="date"> Date:</label></td>
                    <td><input type="date" name="date"></td>
                </tr>
                <tr>
                    <td><label for="atwhattime"> At what time did it happen ?</label></td>
                    <td> <input type="radio" name="time"/> Morning</td>
                    <tr>
                        <td><k>         </k></td>
                        <td> <input type="radio" name="time"/> Afternoon</td>
                    </tr>
                    <tr>
                        <td><k>         </k></td>
                        <td> <input type="radio" name="time"/> Evening</td>
                    </tr>
                    
                   
                </tr>
                <tr>
                    <td><label for="experience"> what emotions did you experience?</label></td>
                    <td><input type="checkbox" name="experience" > loved </td>
                    <tr>
                        <td><k>(select all that apply)        </k></td>
                        <td><input type="checkbox"name="experience"> Enthusistic</td>
                    </tr>
                    <tr>
                        <td><k>         </k></td>
                        <td><input type="checkbox"name="experience"> Elited</td>
                    </tr>
                </tr>
                <tr>
                    <td><label for="description"> Please describe your positive experience </label></td>
                    <td><textarea name="description" rows="5" cols="100"></textarea></td>
                </tr>
                <tr>
                    <td> <input type="submit" name="submit" /></td>
                </tr>
            </table>
        </form>
    </body>
</html>
