<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>payment form</title>
    <link rel="stylesheet" href="payform.css">
</head>
<body>
    <div class="container">
    <form action="" method="get">
        <h1 class="hidding">Payment Form</h1>
        <h2>contact information</h2>
        <p>Name:* <input type="text" name="name" required placeholder="Enter Name"></p>

       <fieldset>
        <legend>Gender *</legend> <p>
            
            Male <input type="radio" name="gender" required>Female <input type="radio" name="gender" required>
           </p> </fieldset>
           <p>Address: * <textarea name="Address" id="Address" cols="100" rows="8" required placeholder="Enter Address"></textarea></p>
           <p>Email: <input type="email" name="email" placeholder="abc@gmail.com"></p>
           <p>Mobile no: *<input type="number" name="Mobile_no" required placeholder="Mobile_no"></p>
           <p>Pincode: * <input type="number" name="Pincode" required placeholder="12345"></p>
           <h2>Payment Information</h2>
           <p>Card Type: *
            <select name="Card_type" id="Card_type">
                <option value="">--select Card_type--</option>
                <option value="debit card/credite card">Debit Card/credite Card</option>
                <option value="upi">UPI</option>
                <option value="QR code">QR code</option>

            </select>
           </p>
           <p>Card Number: *<input type="number" name="card_number" placeholder="card_number"></p>
           <p>Exp Date: *<input type="date" name="Exp_date" placeholder="mm/yyyy"></p>
           <p>CVV: * <input type="password" name="CVV" placeholder="111"></p>
           
           <button>pay now</button>

    </form>
    </div>
<script src="payform.js">

</script>
    
</body>
</html>
