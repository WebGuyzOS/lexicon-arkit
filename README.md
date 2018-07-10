# lexicon-arkit

Apple ARKit integration and sample scene

1. Start by setting up ARKit in Unity

 - Import the ARKit Plugin from the Unity Asset Store: https://assetstore.unity.com/packages/essentials/tutorial-projects/unity-arkit-plugin-92515
 - Switch Platform to iOS in Build Settings
 - Run the UnityARKitScene sample scene on a supported device

2. Import Watson and Lexicon from the Unity Asset Store

 - Watson: https://assetstore.unity.com/packages/tools/ai/ibm-watson-sdk-for-unity-108831
 - Lexicon: https://assetstore.unity.com/packages/tools/ai/lexicon-113459

3. Set up Lexicon (credentials and cloud sync)

 - Follow the quickstart: http://mixspace.tech/lexicon-documentation/0-quick-start/quick-start
 - Run the Basic sample in the editor to test

4. Place this repo in a folder inside your Assets folder. Suggested structure:

    Assets  
    |-- Lexicon  
    |-- LexiconARKit  
    |-- UnityARKitPlugin  
    |-- Watson  
    
5. Add a Microphone Usage Description (e.g. "Lexicon") under Player Settings > Other Settings > Configuration

6. Deploy to an iOS device

 - Use the ARKit scene included in this repo
 - Be sure to accept the microphone permission
 - Find a surface before creating objects

<br>

Website: http://mixspace.tech  
Documentation: http://mixspace.tech/lexicon-documentation  
Support: https://mixspacetech.slack.com (invite link on website)  
Email: mixspacetech@gmail.com  
