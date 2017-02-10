<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
    <link href="style.css" rel="stylesheet" />
    <title>Styling an HTML Form</title>
    <meta charset="utf-8" />
</head>

<body>
<center>
    <div id="container">
	
        <form method="get" action="#">
            <fieldset>
                <legend>Step 1: Your details</legend>
				
                <div>
                    <label for="name">Name</label>
                    <input type="text" name="name" id="name" placeholder="First and last name" title="Latin letters, hyphens and spaces only" pattern="[a-zA-Z\- ]+" maxlength="40" />
                </div>
                <div>
                    <label for="mail">Email</label>
                    <input type="email" name="mail" id="mail" placeholder="example@domain.com" />
                </div>

                <div>
                    <label for="phone">Phone</label>
                    <input type="tel" name="phone" id="phone" placeholder="e.g. +4475000000000" />
                </div>
            </fieldset>
			
            <fieldset>
                <legend>Step 1: Delivery address</legend>

                <div id="text-area">
                    <label for="address">Address</label>
                    <textarea name="address" id="address"></textarea>
                </div>

                <div>
                    <label for="post">Post code</label>
                    <input type="text" name="post" id="post" title="Digits only" pattern="[0-9]+" />
                </div>

                <div>
                    <label for="country">Country</label>
                    <input type="text" name="country" id="country" title="Latin letters, hyphens and spaces only" pattern="[a-zA-Z\- ]+" maxlength="40" />
                </div>
            </fieldset>
			
            <fieldset>
                <legend>Step 1: Card details</legend>

                <div>
                    <span id="top-aligned">Card type</span>
                    
					<table>
                        <tr>
                            <td>
                                <input type="radio" name="card-type" value="VISA" id="VISA" class="radio" />
                            </td>                            
                            <td id="visa">
                                <label class="radio" for="VISA">VISA</label>
                            </td>                        
                            <td>
                                <input type="radio" name="card-type" value="AmEx" id="AmEx" class="radio" />
                            </td>                            
                            <td id="amex">
                                <label class="radio" for="AmEx">AmEx</label>
                            </td>                        
                            <td>
                                <input type="radio" name="card-type" value="Mastercard" id="Mastercard" class="radio" />
                            </td>                            
                            <td id="master">
                                <label class="radio" for="Mastercard">Mastercard</label>
                            </td>
                        </tr>
                    </table>
                </div>

                <div>
                    <label for="card-number">Card number</label>
                    <input type="text" name="card-number" id="card-number" title="Exactly 16 digits, no spaces" pattern="\d{16}" />
                </div>

                <div>
                    <label for="security">Security code</label>
                    <input type="text" name="security" id="security" title="3 or 4 digits, no spaces" pattern="\d{3}\d?" />
                </div>

                <div>
                    <label for="card-holder">Name on card</label>
                    <input type="text" name="card-holder" id="card-holder" placeholder="exact name as on the card" title="Latin letters, hyphens, dots and spaces accepted" pattern="[a-zA-Z\-\.]+" />
                </div>
            </fieldset>

            <input type="submit" value="BUY IT!" id="submit" />
        </form>
    </div>
</center>
</body>
</html>
