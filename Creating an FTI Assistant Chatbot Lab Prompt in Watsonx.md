Following are the steps to create a project in Watsonx Lab Prompt for training
FTI Assistant chatbot.

## Create WatsonX
  1. Return to the main IBM Cloud Dashboard then search for and select the "Watsonx" service in the service catalog.
     Then click Launch Watson.ai and the Watsonx project display will appear as shown in the image below 
     ![Teks Alternatif](https)

## Create Project FTI Assistant
  1. Select Experiment with Foundation Models and Build Prompts
     ![Teks Alternatif](https)
  2. Select the sample lab prompt that will be used, then Generate
     ![Teks Alternatif](https)

## Create Personal API Key
  1. At the Watsonx lab prompt select “View Code”
     ![Teks Alternatif](https)
  2. Klik “Create a Personal API Key”
     ![Teks Alternatif](https)
  3. Click "Create"
     ![Teks Alternatif](https)
  4. Next, set the API Name and Description and "Create"
     ![Teks Alternatif](https)
  5. Copy or Download the API Key
     ![Teks Alternatif](https)

## Setting Extensions WatsonX
  1. Select the Resource View menu and select Watson Assistant, and click Launch Watson Assistant
     ![Teks Alternatif](https)
  2. Click "Integrations"
     ![Teks Alternatif](https)
  3. Next, open "WatsonX Extension", and click "Confirm"
     ![Teks Alternatif](https)
  4. Next, set the Authentication type to "OAuth 2.0" and enter the API that we downloaded/copied when creating the
     API Key earlier and click "Save and Exit"
     ![Teks Alternatif](https)

## Setting up Project FTI Assistant in Watson Assistant and WatsonX
  1. Click the "Actions" menu
     ![Teks Alternatif](https)
  2. Click “New Action” to create a dialog in Watson Assistant. FTI Assistant has 5 Actions in its dialogue model as
     shown in the image below
     ![Teks Alternatif](https)
  3. In the SWCU FTI General Information Action step 1 Assistant says using Iframe Response Type so that message
     confirmation can vary and to Define customer response using "Options"
     ![Teks Alternatif](https)
  4. For steps 2,3 and 4, use with condition so that what the user confirms is in accordance with step 1. Returning
     the information provided by the Chatbot is based on the information created in the Assistant says and "And then"
     using "Go to Subaction:" which is connected to the "Return Question" variable so that the question will continue
     to run according to user input confirmation
     ![Teks Alternatif](https)
  5. Step 5 for user responses is made into "Free Text" so that users can ask questions directly
     ![Teks Alternatif](https)
  6. Create step Call Watsonx Extension which functions when Watson Assistant takes the answer/response from the
      Watsonx Lab Prompt to return it to the user as an answer to a question
      ![Teks Alternatif](https)
  7. Click New step then set it to with conditions and adjust all the settings as shown so that when the statement is
      executed, all dialogue that occurs between the user and the chatbot, the information provided can be in
      accordance with the Watsonx Lap Prompt and "And then" using "Go to Subaction:" which in connect it to the
      “Return Question” variable so that the question will continue to run according to user input confirmation
      ![Teks Alternatif](https)
  8. A Return Question is an action that is created so that it can be set to Subaction so that every question step in
      all actions that are "And then" set to Go to Subaction can be connected. So the questions will continue
      according to confirmation from user input
      ![Teks Alternatif](https)
  9. The UKSW FTI Leadership Action has 8 steps, each Assistant Says is created using direct information from Watson
      Assistant and each user responds using "Options", and "And then" using Go to Subaction
      ![Teks Alternatif](https)
  10. Academic action has 6 steps, each Assistant Says is created using direct Watson assistant information and each
      user responds using "Options", and "And then" using Go to Subaction
      ![Teks Alternatif](https)
  11. Preview view of the FTI Assistant Chatbot
      ![Teks Alternatif](https)
