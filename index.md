<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this NFCU z/OS Connect workshop. 



## Accessing the hands-on lab

Click [here](NFCU-Lab-Connection-Instructions.pdf) to read the instructions for IBM System access. 

All lab instructions are in the "Lab Docs" folder on your remote desktop, or can be downloaded from [here](https://jbrefach.github.io/WSC-ZCEE-Material/docs/labs/) to view it locally.



**Please enter your email address.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">Email Address</span>
<input type="text" class="form-control" placeholder="Email Address" aria-label="EmailAddress" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
</div>

## Help 
Having trouble with labs? Send an email to [Mitch Johnson](mailto: mitchj@us.ibm.com) or  [John Brefach](mailto: John.J.Brefach@ibm.com) or  [Kenishia Callaway](mailto: kenishia@us.ibm.com).
