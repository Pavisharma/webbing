# webbing
FOR THE MAIN PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .img1 {
              float:right;
              margin-left: 15px;
              margin-right: 20px;
              border: 10px solid rgba(255, 255, 2, 0.719);            
              }
        body {
            background-color: #bcbcbc;
            margin: 40px;
        }
        h1 {
            text-align: center;
            color: yellow;
            background-color:rgb(66, 66, 58) ;
            border: yellow;
            margin:30px;
            padding:8px;
            text-shadow: 0 0 6px rgb(248, 182, 0);
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        h2 {
            color: yellow;
            text-shadow: 3px 3px 7px rgb(66, 66, 58);
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif         
        }
        .img2 {
              float:left;
              margin-left: 15px;
              margin-right: 35px;
              border: 10px solid rgba(255, 255, 2, 0.719);
              
              }
        p {
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }
        ul {
            font-family:Verdana, Geneva, Tahoma, sans-serif;
        }
        hr {
            width:500px;
        }
       
        
    </style>
    
</head>
<body>
    <h1>Workplace Harassment</h1>
    <h2>What is workplace harassment?</h2>
    <img class="img1" src="https://lh3.googleusercontent.com/7XpHYPpUYOPY-zULWFf3go-p3gP4lUVLAcZksk9aK7VRRRWt1S2PBunLqoR4txkK5KWuOJpyMf3uny_TT3ooeV58MqqZ-FqnWgMMv_jiYnUReUfqNdN9kt7SglOr-oTIR7YPsJsErA=w2400" alt="Workplace Harassment" style="width:320px;height:190px;">
    <p>Workplace harassment occurs when an employee or group of employees feel thratened or get belittled by their colleagues. The sole purpose of a workplace harasser is to make their victims feel unsafe and uncomfortable.</p>
    <h2>Types of workplace harassment</h2>
    <ul>
        <li>Verbal harassment</li>
        <li>Psychological harassment</li>
        <li>Cyberbullying</li>
        <li>Sexual harassment</li>
        <li>Physical harassment</li>
    </ul>
    <img class="img2" src="https://lh3.googleusercontent.com/Z_DVX1Jy4tNr6zjRh1asOltLRl4vK_wPf_EM9sbPEjRnwcPIb6CJcDwUHOgEy2LrhArYj1Zc-gClc2NFl_zaBrEJDRi7TV1OarNxqHP0sV9yuXOQoAgcTPCpvtx14IZ2wEqnMAzOcw=w2400" alt="Statistics" style=" width:180px; height:200px;">
    <p><br>The “MeToo” movement has indeed given courage to many people to speak openly about offensive conduct at the workplace. Yet, many are still skeptical about opening their mouths and reporting harassing behaviors of colleagues or managers.</p>
    <p>Workplace harassment is common but not spoken openly in most work environments. Harassment at work leads to a toxic and abusive workplace. Many individuals are not sure what is considered harassment at work; hence, most cases go unnoticed and unreported.</p>
    <br><br><br><br><br>
    <h2>Aim of our Website</h2>
    <p>We aim to build a platform where people can fill the form if they've experienced any sort of harassment at their workpace. We would use it to help the job seekers know if the workplace they are desiring to join is safe or not! You can fill the form by <a href="./form.html">clicking here.</a></p>

</body>
</html>


FOR THE FORM 

<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content= "width=device-width, initial-scale=1.0">
	<title>
		Speaking against wrong
	</title>

	<style>

		/* Styling the Body element i.e. Color,
		Font, Alignment */
		body {
			background-color: #bcbcbc;
			font-family: Verdana;
			text-align: center;
		}

		/* Styling the Form (Color, Padding, Shadow) */
		form {
			background-color: #636161;
			max-width: 500px;
			margin: 50px auto;
			padding: 30px 20px;
			box-shadow: 2px 5px 10px rgba(0, 0, 0, 0.5);
		}

		/* Styling form-control Class */
		.form-control {
			text-align: left;
			margin-bottom: 25px;
		}

		/* Styling form-control Label */
		.form-control label {
			display: block;
			margin-bottom: 10px;
		}

		/* Styling form-control input,
		select, textarea */
		.form-control input,
		.form-control select,
		.form-control textarea {
			border: 1px solid #777;
			border-radius: 2px;
			font-family: inherit;
			padding: 10px;
			display: block;
			width: 95%;
		}

		/* Styling form-control Radio
		button and Checkbox */
		.form-control input[type="radio"],
		.form-control input[type="checkbox"] {
			display: inline-block;
			width: auto;
		}

		/* Styling Button */
		button {
			background-color: #BCBCBC;
			border: 1px solid #777;
			border-radius: 2px;
			font-family: inherit;
			font-size: 21px;
			display: block;
			width: 100%;
			margin-top: 50px;
			margin-bottom: 20px;
		}
	</style>
</head>

<body>
	<h1 STYLE="COLOR:rgb(253, 253, 5)">REPORT HERE ANONYMOUSLY</h1>

	<!-- Create Form -->
	<form id="form">

		<!-- Details -->
		<div class="form-control" STYLE="COLOR:rgb(253, 253, 5)">
			<label for="name" id="label-name">
				Name (Optional)
			</label>

			<!-- Input Type Text -->
			<input type="text"
				id="name"
                               Background-color:"rgb(253, 253, 5)" 
				placeholder="Enter your name" />
		</div>
                        
                     
		

		<div class="form-control" STYLE="COLOR:rgb(253, 253, 5)" > 
			<label for="email" id="label-email">
				Email (optional)			</label>

			<!-- Input Type Email-->
			<input type="email"
				id="email"
				placeholder="Enter your email" />
		</div>

		<div class="form-control" STYLE="COLOR:rgb(253, 253, 5)">
			<label for="age" id="label-age">
				Age
			</label>

			<!-- Input Type Text -->
			<input type="text"
				id="age"
				placeholder="Enter your age" />
		</div>

		<div class="form-control" STYLE="COLOR:rgb(253, 253, 5)">
			<label for="gender" id="gender">
				Gender
			</label>
			
			<!-- Dropdown options -->
			<select name="role" id="role">
				<option value="Female">Female</option>
				<option value="Male">Male</option>
				<option value="Other">
					Other
				</option>
			</select>
		</div>


                       
                        <div class="form-control" STYLE="COLOR:rgb(253, 253, 5)">
			<label for="Org_name" id="Org-name">
				Name of the Organisation
			</label>

			<!-- Input Type Text -->
			<input type="text"
				id="name"
                               Background-color:"#474747" 
				placeholder="Enter the name of the Organisation" />
                        <div class="form-control" STYLE="COLOR:rgb(253, 253, 5)">
			</div>


                                <label for="role" id="label-role">
				What role you are serving as at your workplace
			</label>
			
			<!-- Input Type Text -->
			<input type="text" 
                               id="your role"
                           placeholder="eg- 'Intern', 'Manager' etc." />
		</div> 

		<div class="form-control"STYLE="COLOR:rgb(253, 253, 5)">
			<label >
				Were you harrased by your superior ?
				
			</label>

			<!-- Input Type Radio Button -->
			<label for="recommed-1">
				<input type="radio"
					id="recommed-1"
					name="recommed">Yes</input>
			</label>
			<label for="recommed-2">
				<input type="radio"
					id="recommed-2"
					name="recommed">No</input>
			</label>
			<label for="recommed-3">
				<input type="radio"
					id="recommed-3"
					name="recommed">Choose not to answer</input>
			</label>
		</div>


		<div class="form-control" STYLE="COLOR:rgb(253, 253, 5)">
			<label for="comment">
				Your experience 
			</label>

			<!-- multi-line text input control -->
			<textarea name="comment" id="comment"
				placeholder="State your experience here">
			</textarea>
		</div>

		<!-- Multi-line Text Input Control -->
		<button type="submit" value="submit"  >
			Submit
		</button>
	</form>
</body>

</html>

