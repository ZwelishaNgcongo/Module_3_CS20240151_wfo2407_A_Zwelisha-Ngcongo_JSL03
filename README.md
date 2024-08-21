# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: [https://www.loom.com/share/b75f06b19f3b4e63a19b2aff3f092c00]

# Project Overview

In this project, you will be presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. Your task is to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

You will present your reasoning for each example, record your presentation using Loom, and submit your findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).

# Instructions

## Step 1: Clone the Repository

Repo Link: https://github.com/CodeSpace-Academy/Module_3_StudentNo_Classcode_Group_Name-Surname_JSL03

1. Access the provided repository containing the starter code and presentation template.
2. Clone the repository.
3. Open the cloned repository in your preferred code editor.

## Step 2: Analyze the Examples

1. In the cloned repository, you will find two JavaScript code examples labeled "Example 1" and "Example 2."
2. Examine each code example and determine which one follows an imperative programming style and which one follows a declarative programming style.

## Step 3: Record Your Presentation

1. Use Loom (https://www.loom.com/).
2. Create a single video presentation for both examples that include the following:

   - Introduction of the example number.
   - Explanation of whether the example is imperative or declarative.
   - Detailed reasoning for your choice, discussing the code logic and style used in the example.
   - Mention any specific code structures or patterns that align with the chosen programming paradigm.
   
3. Keep each video presentation concise, with a maximum length of 2 minutes for each example. Your total recording time should not exceed 5 minutes.

## Step 4: Insert Loom Links

1. After recording, upload your presentation videos to Loom.
2. Obtain the Loom recording links for the video presentation.
3. Edit the `README.md` file in the cloned repository and insert the Loom recording links.
   
## Step 5: Submit Your Project
1. Commit your changes to the Git repository and push them to your GitHub account.
2. Ensure that the repository is public so that it can be accessed.
3. Submit the GitHub project link (URL) that includes your Loom recording link to the [JSL03] Project Tab on the LMS for evaluation.

# Project Evaluation

Your project will be evaluated based on your ability to:

- Accurately identify and differentiate between imperative and declarative programming styles.
- Provide clear and well-reasoned explanations for your choices.
- Present your findings concisely within the specified time limit.
- Follow the submission instructions accurately.

Follow the steps outlined above to complete the project successfully.

# Presentation Talking Points

Example #: [Example_1]

## Imperative Approach [2 Minutes]
Reasoning for Imperative Programming style: The function dictates the order of executing the operations(pre-heating grill, seasoning, cooking steak & having to serve steak).The cooking steps are sequential, whereby one step is executed after the other.
1.Function cookSteak has 2 parameters: SteakWeight & desiredDoneness.
2.Two Temperature Variables : grillTemperature & steakTemperature set at default values of zero.
3.Two Constants: grillTemperature set to 240ºC and seasoning set to “Salt and Pepper”.
4.Cooking Procedure: cooking process has an array of objects, informing of the steps in the cooking process. Temperature, seasoning & desiredDoneness provide details on how to carry out the steps in cooking.
5.Looping and executing the conditions. The while loop ensures the cooking process is carried out for as long as steakTemperature has not met the desiredDoneness.
Switch statements checking action and logging message e.g.:
1.Season steak: logs seasoning method.
2.Preheat grill: logs preheated temperature.
3.Cooking steak until desired doneness: logs the doneness temperature.
4.Serve the steak: logs that steak is ready to be served. If the condition is not met steak needs more cooking.
6.The function is called with cooksteak(16,63) 16 oz, 63ºC meaning cooking of steak should be medium-rare .





Example #: [Example_2]

## Declarative Approach [2 Minutes]
Reasoning for Declarative conclusion: The cooksteak function highlights the specific action to be carried out throughout the cooking process( “preheat grill”, “seasoning steak”, “cook steak until desired doneness” than “serve steak”)
1.Function cooksteak has two parameters: steakWeight  and  desiredDoneness.
2.Two constants grillTemperatureCelsius set at 204ºC and seasoning= “Salt and Pepper”.
3.Executing cooking process: has an array of objects highlighting actions to be undertaken in the cooking process. Temperature, seasoning and desiredDoneness provide the relevant details.
4.A for loop has been implemented in order to execute the cookingProcess. There are switch statements that monitors the actions and logs a message out:
-“Preheat grill” logs the preheating temperature.
-“Season Steak” logs the method used in seasoning.
-“Cook steak until desired doneness” logs the desired doneness temperature.
-“Serve steak” logs that the steak is ready to be served.
If the action does not meet any of the cases it logs message “invalid step in the cooking process”.
5.The function cooksteak is called at(16,63)16 oz, 63ºc of which it is at a medium rare state.
The declarative approach has abstract away from control flow and low-level operations, by specifying what needs to be achieved in the cooking process.


# Learning Outcome [1 Minute]
Imperative vs Declarative approach

Example_1 followed the Imperative approach which had focused on how the tasks is to be performed, which was inclusive of the various steps ranging from step1-step4. It made usage of a while loop with set conditions and instructions on how to go about cooking the steak.

Example_2 followed the Declarative approach which was orientated on the “how” to achieve the desired outcome. It had not detailed the steps to achieve the desired outcome.

In conclusion I was able to distinguish between the two approaches one of which is step orientated(imperative) and the other being focused on the goal at hand without being centred on following steps(declarative).


