# Forms

|                                                                                                                                                                                                |        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [The search element](https://www.scottohara.me/blog/2023/03/24/search-element.html?utm\_source=newsletter\&utm\_medium=email\&utm\_campaign=wdrl-311)                                          | 5/4/23 |
| [How to autocomplete two-factor authentication codes with a single HTML attribute](https://gomakethings.com/how-to-autocomplete-two-factor-authentication-codes-with-a-single-html-attribute/) | 10/28  |
| [How to create an autocomplete input with only HTML](https://gomakethings.com/how-to-create-an-autocomplete-input-with-only-html/?mc\_cid=c61de3cb62\&mc\_eid=\[UNIQID])                       | 3/5    |

{% code title="Form" %}
```markup
<form>
<!-- text input -->
<label for="name">Name:</label>
<input id="name" type="text" name="textfield">

<!-- textarea -->
<label for="address">Enter your address:</label><br>
<textarea id="address" name="addresstext"></textarea>

<!-- checkboxes -->
<fieldset>
<legend>Select your pizza toppings:</legend>
<input id="ham" type="checkbox" name="toppings" value="ham">
<label for="ham">Ham</label><br>
<input id="pepperoni" type="checkbox" name="toppings" value="pepperoni">
<label for="pepperoni">Pepperoni</label><br>
<input id="mushrooms" type="checkbox" name="toppings" value="mushrooms">
<label for="mushrooms">Mushrooms</label><br>
<input id="olives" type="checkbox" name="toppings" value="olives">
<label for="olives">Olives</label>
</fieldset>

<!-- radio buttons -->
<fieldset>
<legend>Choose a shipping method:</legend>
<input id="overnight" type="radio" name="shipping" value="overnight">
<label for="overnight">Overnight</label><br>
<input id="twoday" type="radio" name="shipping" value="twoday">
<label for="twoday">Two day</label><br>
<input id="ground" type="radio" name="shipping" value="ground">
<label for="ground">Ground</label>
</fieldset>

<!-- select dropdown menu -->
<label for="favcity">Choose your favorite city?</label>
<select id="favcity" name="select">
<option value="1">Amsterdam</option>
<option value="2">Buenos Aires</option>
<option value="3">Delhi</option>
<option value="4">Hong Kong</option>
<option value="5">London</option>
<option value="6">Los Angeles</option>
<option value="7">Moscow</option>
<option value="8">Mumbai</option>
<option value="9">New York</option>
<option value="10">Sao Paulo</option>
<option value="11">Tokyo</option>
</select>

<!-- buttons -->
<input type="submit" name="submit" value="Submit Search">
<input type="reset" name="reset" value="Reset">
<button>Activate</button>
<input type="image" name="submitbutton" alt="search" src="submit.png">

</form>
```
{% endcode %}

|                                                                                                                                  |   |
| -------------------------------------------------------------------------------------------------------------------------------- | - |
| [https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form) |   |
| [https://www.w3schools.com/html/html\_forms.asp](https://www.w3schools.com/html/html\_forms.asp)                                 |   |
| \<label>                                                                                                                         |   |
| \<fieldset>                                                                                                                      |   |
| \<legend>                                                                                                                        |   |
