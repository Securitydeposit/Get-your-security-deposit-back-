# Get-your-security-deposit-back-

Before: <input type="hidden" name="name" value="Sample Demand Letter"/>
<input type="hidden" name="docx_uri" value="http://www.codingthelaw.org/Fall_2017/work/moiucihdaa/lasm/Sample-Demand-Letter.docx"/>

</div><h2 style="text-align:center;">Get Your Security Deposit Back!</h2>
<p>Answer a few questions to find out how you may be able to get your security deposit back.  Here is a link if you have additional questions about Security Deposit law in Rhode Island. <a href=http://brown.edu/Administration/Auxiliary_Housing/documents/LTHandbook.pdf>RI Security Deposit Law Overview</a> </p>


<p>Damages: <a href=https://law.justia.com/codes/rhode-island/2012/title-34/chapter-34-18/chapter-34-18-19/> Chapter 34-18-19</a>  RI law may allow you to recover not only your security deposit but also damages up to two times your security deposit and possibly reasonable attorney fees if you retain a lawyer.  (i.e $1000 security deposit was not returned, a court may award the $1000 security deposit, the court may also award up to 2x the security deposit held so in this case up to $2000 may be awarded in addition to the original security deposit, the court may also allow reasonable attorney fees if you are represented by an attorney.) 


<p>Answer the following questions to see if you qualify to submit a demand letter to to your landlord, this may take up to 10 minutes.</p>
Title: Get Your Security Deposit Back!


Q(1): Was your security deposit returned in full at the termination of your lease?
A: No.
	Q(1.1): Were you given a reason why, that included an explanation of how the money spent was allocated (a list of each dollar spent to repair damages or applied to a missed rental payment)?
	A: No.
		Q(1.1.1): Has it been longer than 20 days since you moved out of the apartment and returned the keys?
		A: Yes.
			Q(1.1.1.1): You can send a demand letter asking for the security deposit back in full or have the landlord supply the reason why it is being withheld with the accounting for how each dollar was spent, would you like to write a demand letter? 
			A: Yes.
				Q(myname): What is your name?
				X:
					Q(myaddress): What is your current address?
					X:
						Q(Landlordname): What is your landlords name?
						X:
							Q(landlordsaddress): What is your landlords address?
							X:
								Q(date): What is todays date? (mm/dd/yyyy)
								X:
									Q(deposit): What is the total amount of the security deposit withheld?
									X:
										Q(phonenumber): What is your phone number?
										X:
											Q(oldaddress): What was the rental address of the property in question?
											X:
												Q(moveoutdate): When did you move out of the rental? (mm/dd/yyyy)
												X:
													DOC(1.1.1.1.1.1.1.1.1.1.1.1.1.1):From,<br><br> 
													<x>myname</x><br>
													<x>myaddress</x><br><br>
													To:<br><br>
													<x>landlordname</x><br>
													<x>landlordsaddress</x>
													Today's date:<x>date</x><br><br>
													As you know, I was your tenant at <x>oldaddress</x> and I moved out on <x>moveoutdate</x>.<br>
													This is to demand that you return to me my security deposit of $<x>deposit</x> within 20 days of the date I moved out.<br>
													Please mail me a check or money order at my new address, which is <x>myaddress</x> or call me at <x>phonenumber</x> to make other arrangements.<br>
													If I do not receive the security deposit back within 20 days, I can take you to Small Claims Court and ask the judge to award me twice the amount of the deposit as compensation.<br><br>
													Sincerely,<br><br>
													<x>myname</x>

						
													Q(1.1.1.1.1.1.1.1.1.1.1.1.1.1):Alright, are you ready to see your letter?
													A[javascript:submit2('http://www.qnamarkup.org/doc/parse/html/','POST','t','Proof read your letter. Print it out, and mail it to: your landlord')]: Yes.
														Q(1.1.1.1.1.1.1.1.1.1.1.1.1.1.1): Thank you.

				
			A: No.
				Q(1.1.1.1.2): Ok. Have a good day.

			
					
			A: List of lawyers who may be able to help
				Q(1.1.1.1.3): (fill in with list of lawyers).
		A: No.
			Q(1.1.1.2): The landlord has 20 days to return a security deposit in full or supply notice of what was deducted and the costs to repair or apply the amount to unpaid rent.
	A: Yes.
		Q(1.1.2): Do you believe that the amounts withheld are incorrect (excessive costs, dispute anything was damaged or owed, improper use of the funds)?
		A: Yes
			Q(1.1.2.1): You may be able to recover some of this by sending a demand letter.  Would you like to send a demand letter?
			A:Yes.
				Q(1.1.2.1.1): Okay. GOTO:1.1.1.1
			A:No. 
				Q(1.1.2.1.2): Okay. GOTO:2
		A: No
			Q(1.1.2.2): Okay then, have a great day.
A: Yes. 
	Q(1.2): Okay then. GOTO:2

Q(2): Have a nice day.
