Following are the steps for creating a project in Watson Lab Prompt for FTI Assistant Chatbot training.

## Create WatsonX
  * Return to the main IBM Cloud Dashboard then search for and select the `Watsonx` service in the service catalog.
    Then click `Launch Watson.ai` and the Watsonx project display will appear as shown in the image below. 
    ![Teks Alternatif](assets/img/WatsonX.png)

## Create Project FTI Assistant
  * In this section, I Experiment with the Foundation Model and an example lab prompt Create a Select Command and
    then I create a Model: llama-2-70b-chat.
    ![Teks Alternatif](assets/img/WX-3.png)

## Create Personal API Key
  * Here I explain the steps to create an API Key At the Watsonx lab prompt select `View Code`, Click `Create Private
    API Key`, Click `Create`, Next, I set the API Name and Description and `Create`.
    ![Teks Alternatif](assets/img/sample-prompt-lab.png)
    ![Teks Alternatif](assets/img/View-Code.png)
    ![Teks Alternatif](assets/img/Create-a-Personal-API-Key.png)
    ![Teks Alternatif](assets/img/Download-API-Key.png)

## Setting Extensions Watsonx
  * Then I set up WatsonX Extensions, here I follow some important steps. First, open the `Resource List` menu and
    select the `Watson Assistant` option. Then, click `Launch Watson Assistant` to enter Watson Assistant. After
    that, navigate to the `Integration` tab where I clicked on the `WatsonX Extension` option. Click `Confirm` to
    open it. Next, to configure the settings, I selected the authentication type `OAuth 2.0` and entered the API that
    I had downloaded or copied when generating the API key earlier. Finally, I saved the changes by clicking `Save
    and Exit`.

## Setting up Project FTI Assistant in Watson Assistant and WatsonX
I created an FTI Assistant chatbot for dialogue in Watson Assistant. Where the dialogue has 5 different actions, 
including:
  * UKSW FTI General Information Action, UKSW FTI Leadership Action, and Academic Action are actions that I created
    to provide general information dissemination from the FTI Assistant Chatbot to FTI Assistant chatbot users
    related to the Faculty of Information Technology (FTI) at Satya Wacana Christian University (UKSW ). The
    information provided is the result of variables created in Watson Assistant and information trained in Prompt Lab
    using artificial intelligence in IBM Watsonx.
  * Meanwhile, Action Question Back is an action that I made into a Subaction which functions to make questions
    continue according to confirmation from user input.
  11. Preview view of the FTI Assistant Chatbot
      ![Teks Alternatif](assets/img/Preview.png)
