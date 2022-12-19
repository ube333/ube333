using System;

using System.Linq;



namespace Rey_Program

{

	public static class Program

	{

		public static void Main()

		{

		Console.WriteLine("Guess the Nutrients of Fruits, Vegetables, and Legumes Game");

		Console.WriteLine("-----------------------------------------------------------");

		Console.WriteLine();

		

		//pname stands for player name

		Console.WriteLine();

		string pname;

		Console.WriteLine("Please Enter Your Name:");

		pname=Console.ReadLine();

		Console.WriteLine(" Hi " + pname + " Welcome to Guess the Nutrients of Fruits, Vegetables, and Legumes Game");

		Console.WriteLine();

		var totalScore = 0;

		

		while(true){

			string start;

			Console.WriteLine();

			Console.Write(" Would you like to start?\nEnter [Yes or yes] it's your choice:");

			start = Console.ReadLine();

			if (start == "Yes" || start == "yes")

			Console.WriteLine("");

			Console.WriteLine("Select levels based on difficulty. Press (1) Easy Level, (2) Moderate Level, (3) Hard Level.");

			int level;

			Console.WriteLine("");

			Console.Write("Enter Level:");

			level=Convert.ToInt32(Console.ReadLine());

			if (level==1){

				Console.WriteLine();

				Console.WriteLine("Easy Level");

				string EL1;

				Console.WriteLine("");

				Console.WriteLine("1. What is the most nutrients that can be obtained from apple fruit?");

				Console.WriteLine(" a. Vitamin A\n b. Vitamin B\n c. Vitamin C");

				Console.Write("Answer:");

				EL1=Console.ReadLine();

				

				if (EL1== "C" || EL1== "c"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'c'\n");

				}

				Console.WriteLine();

				string EL2;

				Console.WriteLine();

				Console.WriteLine("2. Except Vitamin C, what is the other one main nutrients of pineapple?");

				Console.WriteLine(" a. Sulfur\n b. Manganese\n c. Phosporus");

				Console.Write("Answer:");

				EL2=Console.ReadLine();

				

				if (EL2== "B" || EL2== "b"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'b'\n");

				}

				Console.WriteLine();

				string EL3;

				Console.WriteLine();

				Console.WriteLine("3. Which fruit has most protein?");

				Console.WriteLine(" a. Guava\n b. Banana\n c. Orange");

				Console.Write("Answer:");

				EL3=Console.ReadLine();

				

				if (EL3== "A" || EL3== "a"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'a'\n");

				}

				Console.WriteLine();

				string EL4;

				Console.WriteLine();

				Console.WriteLine("4. What fruit is the good source of folate, several B vitamins,?");

				Console.WriteLine(" a. Kiwi\n b. Mango\n c. Cherry");

				Console.Write("Answer:");

				EL4=Console.ReadLine();

				

				if (EL4== "B" || EL4== "b"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'b'\n");

				}

				Console.WriteLine();

				string EL5;

				Console.WriteLine();

				Console.WriteLine("5. What is the 2 main nutrient in grapes?");

				Console.WriteLine(" a. Vitamin K and copper\n b. Vitamin E and nickel\n c. Vitamin D and Iron");

				Console.Write("Answer:");

				EL5=Console.ReadLine();

				

				if (EL5== "A" || EL5== "a"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'a'\n");

				}

				Console.WriteLine();

				string EL6;

				Console.WriteLine();

				Console.WriteLine("6. What fruit is high in healthy fats and low in natural sugars?");

				Console.WriteLine(" a. Lemon\n b. Water Melon\n c. Avocado");

				Console.Write("Answer:");

				EL6=Console.ReadLine();

				

				if (EL6== "C" || EL6== "c"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'c'\n");

				}

				Console.WriteLine();

				string EL7;

				Console.WriteLine();

				Console.WriteLine("7. Berries provide many nutrients that we need each day to stay healthy, such as.");

				Console.WriteLine(" a. Fiber, vitamin C, Iron and B vitamins. \n b. Vitamin E, Nickel, Vitamin B and C Vitamin\n c. Vitamin D, Iron, Vitamin C, and Fiber");

				Console.Write("Answer:");

				EL7=Console.ReadLine();

				

				if (EL7== "A" || EL7== "a"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'a'\n");

				}

				Console.WriteLine();

				string EL8;

				Console.WriteLine();

				Console.WriteLine("8. What is 2 vitamins does watermelon have?");

				Console.WriteLine(" a. Vitamin C and D\n b. Vitamins A and C\n c. Vitamin D and E");

				Console.Write("Answer:");

				EL8=Console.ReadLine();

				

				if (EL8== "B" || EL8== "b"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'b'\n");

				}

				Console.WriteLine();

				string EL9;

				Console.WriteLine();

				Console.WriteLine("9. What is the most nutrient rich fruit?");

				Console.WriteLine(" a. Lemon and Melon\n b. orange and Limes\n c. Citrus and Berries");

				Console.Write("Answer:");

				EL9=Console.ReadLine();

				

				if (EL9== "C" || EL9== "c"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'c'\n");

				}

				Console.WriteLine();

				string EL10;

				Console.WriteLine();

				Console.WriteLine("10. Which fruit is the king of vitamin?");

				Console.WriteLine(" a. Durian\n b. Apple\n c. Peach");

				Console.Write("Answer:");

				EL10=Console.ReadLine();

				

				if (EL10== "A" || EL10== "a"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'a'\n");

				}

				Console.WriteLine();

				string EL11;

				Console.WriteLine();

				Console.WriteLine("11. Figs are good source of what nutrient?");

				Console.WriteLine(" a. Calories\n b. Fiber\n c. Protein");

				Console.Write("Answer:");

				EL11=Console.ReadLine();

				

				if (EL11== "B" || EL11== "b"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'b'\n");

				}

				Console.WriteLine();

				string EL12;

				Console.WriteLine();

				Console.WriteLine("12. Orange and Apple are high in what nutrients?");

				Console.WriteLine(" a. Lipids\n b. Calcium\n c. Carbohydrates");

				Console.Write("Answer:");

				EL12=Console.ReadLine();

				

				if (EL12== "C" || EL12== "c"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'c'\n");

				}

				Console.WriteLine();

				string EL13;

				Console.WriteLine();

				Console.WriteLine("13. Which fruit is rich in lipids?");

				Console.WriteLine(" a. Rambutan\n b. Avocados\n c. Guava");

				Console.Write("Answer:");

				EL13=Console.ReadLine();

				

				if (EL13== "B" || EL13== "b"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'b'\n");

				}

				Console.WriteLine();

				string EL14;

				Console.WriteLine();

				Console.WriteLine("14. What nutrients is in the Jackfruit, Kiwi, and Apricot?");

				Console.WriteLine(" a. Sulfur\n b. Fats\n c. Protein");

				Console.Write("Answer:");

				EL14=Console.ReadLine();

				

				if (EL14== "C" || EL14== "c"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'c'\n");

				}

				Console.WriteLine();

				string EL15;

				Console.WriteLine();

				Console.WriteLine("15. What nutrients is obtained by the fruits like dried peaches, apricots, sultanas, and figs.");

				Console.WriteLine(" a. Sulfur\n b. Magnesium\n c. Iron");

				Console.Write("Answer:");

				EL15=Console.ReadLine();

				

				if (EL15== "A" || EL15== "a"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'a'\n");

				}

				Console.WriteLine();

				Console.WriteLine("Your score is "+ totalScore);

				if(totalScore >= 8){

				Console.WriteLine("Exellent. You passed the challenge");

				}

				else if (totalScore >= 6){

					Console.WriteLine("You failed. Better luck next time");

				}

				else{

					Console.WriteLine("You failed. Better luck next time");

				}

   	}

		   else if(level == 2){

				Console.ReadLine();

				Console.WriteLine("Moderate Level");

				string ML1;

				Console.WriteLine("");

				Console.WriteLine("1. Carrots is an exellent source of Vitamin A");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML1=Console.ReadLine();

				

			   if (ML1== "True" || ML1== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML2;

				Console.WriteLine();

				Console.WriteLine("2. A Cabbage has 72.75 Potaasium");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML2=Console.ReadLine();

				

				if (ML2== "True" || ML2== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML3;

				Console.WriteLine();

				Console.WriteLine("3. Eggplant provides a bad amount of Fiber, Vitamins, and Minerals in few calories");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML3=Console.ReadLine();

				

				if (ML3== "False" || ML3== "false"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'false'\n");

				}

				string ML4;

				Console.WriteLine();

				Console.WriteLine("4. Eating pumpkin is a good for the eyes");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML4=Console.ReadLine();

				

				if (ML4== "True" || ML4== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML5;

				Console.WriteLine();

				Console.WriteLine("5. Lettuce is a packed with Vitamin A, Vitamin D, and Manganese");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML5=Console.ReadLine();

				

				if (ML5== "False" || ML5== "false"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'false'\n");

				}

				string ML6;

				Console.WriteLine();

				Console.WriteLine("6. Spinach is the healthiest vegetable");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML6=Console.ReadLine();

				

				if (ML6== "True" || ML6== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML7;

				Console.WriteLine();

				Console.WriteLine("7. A Cucumber has low calories");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML7=Console.ReadLine();

				

				if (ML7== "False" || ML7== "false"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'false'\n");

				}

				string ML8;

				Console.WriteLine();

				Console.WriteLine("8. Broccoli have Saturated fat 10%");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML8=Console.ReadLine();

				

				if (ML8== "False" || ML8== "false"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'false'\n");

				}

				string ML9;

				Console.WriteLine();

				Console.WriteLine("9. Silverbeet is good for kidneys");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML9=Console.ReadLine();

				

				if (ML9== "True" || ML9== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML10;

				Console.WriteLine();

				Console.WriteLine("10. Asparagus is good for Gut Health");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML10=Console.ReadLine();

				

				if (ML10== "True" || ML10== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML11;

				Console.WriteLine();

				Console.WriteLine("11. According to FDA garlic contains several Vitamins and Minerals");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML11=Console.ReadLine();

				

				if (ML11== "False" || ML11== "false"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'false'\n");

				}

				string ML12;

				Console.WriteLine();

				Console.WriteLine("12. 15% of Vitamin B6 has shallot have");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML12=Console.ReadLine();

				

				if (ML12== "True" || ML12== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML13;

				Console.WriteLine();

				Console.WriteLine("13. Potato also have Potassium, Vutamins B and E, and other nutrients");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML13=Console.ReadLine();

				

				if (ML13== "True" || ML13== "true"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'true'\n");

				}

				string ML14;

				Console.WriteLine();

				Console.WriteLine("14. A Potato skin is dangerous to our health");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML14=Console.ReadLine();

				

				if (ML14== "False" || ML14== "false"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'false'\n");

				}

				string ML15;

				Console.WriteLine();

				Console.WriteLine("15. Celery is rich in Viramins and Minerals with a high glycemic index");

				Console.WriteLine(" True\n False");

				Console.Write("Answer:");

				ML15=Console.ReadLine();

				

				if (ML15== "False" || ML15== "false"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'false'\n");

				}

				Console.WriteLine();

				Console.WriteLine("Your score is "+ totalScore);

				if(totalScore >= 8){

				Console.WriteLine("Exellent. You passed the challenge");

				}

				else if (totalScore >= 6){

					Console.WriteLine("You failed. Better luck next time");

				}

				else{

					Console.WriteLine("You failed. Betterluck next time");

				}

	

		  }

		   else if(level == 3){

				Console.ReadLine();

				Console.WriteLine("Hard Level");

				string HL1;

				Console.WriteLine("");

				Console.WriteLine("1. White beans are a nutritional powerhouse, as they're packed with ___________ and protein");

				Console.Write("Answer:");

				HL1=Console.ReadLine();

			   if (HL1== "Fiber" || HL1== "fiber"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'fiber'\n");

				}

				string HL2;

				Console.WriteLine("");

				Console.WriteLine("2. Kidney beans are mainly composed of carbs and fiber but also serve as a good source of ____________");

				Console.Write("Answer:");

				HL2=Console.ReadLine();

			   if (HL2== "Protein" || HL2== "protein"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'protein'\n");

				}

				string HL3;

				Console.WriteLine("");

				Console.WriteLine("3. Pinto beans are primarily comprised of carbs, fiber, and protein. They also pack an incredible punch of _____________ and minerals ");

				Console.Write("Answer:");

				HL3=Console.ReadLine();

			   if (HL3== "Vitamins" || HL3== "vitamins"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'vitamins'\n");

				}

				string HL4;

				Console.WriteLine("");

				Console.WriteLine("4. Soybeans are mainly composed of protein but also contain good amount of carbs and _____________");

				Console.Write("Answer:");

				HL4=Console.ReadLine();

			   if (HL4== "Fat" || HL4== "fat"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'fat'\n");

				}

				string HL5;

				Console.WriteLine("");

				Console.WriteLine("5. Black-eyed peas are also a good source of several important micronutrients, including folate, coppper, thiamine, and ____________");

				Console.Write("Answer:");

				HL5=Console.ReadLine();

			   if (HL5== "Iron" || HL5== "iron"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'iron'\n");

				}

				string HL6;

				Console.WriteLine("");

				Console.WriteLine("6. Green peas are a popular vegetable. They are also quite nutritious and contain a fair amount of fiber and ____________ ");

				Console.Write("Answer:");

				HL6=Console.ReadLine();

			   if (HL6== "Antioxidants" || HL6== "antioxidants"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'antioxidants'\n");

				}

				string HL7;

				Console.WriteLine("");

				Console.WriteLine("7. Interms of nutrient content, snow peas are packed with Vitamin A, Vitamin C, iron, ____________, dietary fiber, magnesium, folic acid, and small levels of fats");

				Console.Write("Answer:");

				HL7=Console.ReadLine();

			   if (HL7== "Potassium" || HL7== "potassium"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'potassium'\n");

				}

				string HL8;

				Console.WriteLine("");

				Console.WriteLine("8. Carob powder is a valuable source of Vitamins E, D, ________, Niacin, B6, and Folic acid");

				Console.Write("Answer:");

				HL8=Console.ReadLine();

			   if (HL8== "C" || HL8== "C"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'c'\n");

				}

				string HL9;

				Console.WriteLine("");

				Console.WriteLine("9. _____________ are rich in protein, fats, and various healthy nutrients");

				Console.Write("Answer:");

				HL9=Console.ReadLine();

			   if (HL9== "Peanuts" || HL9== "peanuts"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'peanuts'\n");

				}

				string HL10;

				Console.WriteLine("");

				Console.WriteLine("10. Lentils are low in ____________ and saturated fat");

				Console.Write("Answer:");

				HL10=Console.ReadLine();

			   if (HL10== "Sodium" || HL10== "sodium"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'sodium'\n");

				}

				string HL12;

				Console.WriteLine("");

				Console.WriteLine("12. ____________ are made up of more than 25% protein");

				Console.Write("Answer:");

				HL12=Console.ReadLine();

			   if (HL12== "Lentils" || HL12== "lentils"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'lentils'\n");

				}

				string HL13;

				Console.WriteLine("");

				Console.WriteLine("13. Chickpea is high in calories and mik has ______________ less calories than chickpea");

				Console.Write("Answer:");

				HL13=Console.ReadLine();

			   if (HL13== "70%" || HL13== "70%"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is '70%'\n");

				}

				string HL14;

				Console.WriteLine("");

				Console.WriteLine("14. Tamarind is an excellent source of B vitamins, vitamin C, potassium, magnesium, iron, thiamine, phosphorus, _____________ and fiber");

				Console.Write("Answer:");

				HL14=Console.ReadLine();

			   if (HL14== "Riboflaxin" || HL14== "riboflaxin"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'riboflaxin'\n");

				}

				string HL15;

				Console.WriteLine("");

				Console.WriteLine("15. Peas are high concentrationof vitamins, minerals, antioxidants, and _____________");

				Console.Write("Answer:");

				HL15=Console.ReadLine();

			   if (HL15== "phytonutrients" || HL15== "phytonutrients"){

					//This is for incrementation

					Console.WriteLine("You're correct");

					totalScore+=1;

				}

				else{

					Console.WriteLine("Your answer is wrong. The correct answer is 'phytonutrients'\n");

				}

				Console.WriteLine();

				Console.WriteLine("Your score is "+ totalScore);

				if(totalScore >= 8){

				Console.WriteLine("Exellent. You passed the challenge");

				}

				else if (totalScore >= 6){

					Console.WriteLine("You failed. Better luck next time");

				}

				else{

					Console.WriteLine("You failed. Better luck next time");

				}

		   }

		   string answer;

		   Console.WriteLine();

		   Console.Write("Want to try again? (Yes | No):");

		   answer=Console.ReadLine();

		   if (answer != "Yes"){

		   string answer_2;

		   Console.WriteLine();

		   Console.Write("Wanted to Exit? (Yes | No):");

		   answer_2=Console.ReadLine();

		   if (answer_2 == "Yes"){

		   	Environment.Exit(0);

		   }

		   

		   }

			

		    }

	   }

		}}

	   

	









