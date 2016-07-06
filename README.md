# Microsoft Bing Speech API: Javascript Speech-to-Text Sample
This repo contains a Javascript client library and samples for webpages using Speech-to-Text in the Microsoft Bing Speech API, an offering within [Microsoft Cognitive Services](https://www.microsoft.com/cognitive-services), formerly known as Project Oxford.
* [Learn about the Bing Speech API](https://www.microsoft.com/cognitive-services/en-us/speech-api)
* [Read the documentation](https://www.microsoft.com/cognitive-services/en-us/speech-api/documentation/overview)
* [Find more SDKs & Samples](https://www.microsoft.com/cognitive-services/en-us/SDK-Sample?api=bing%20speech)


## The Client Library
To use the client library in your own application, simply host Speech.1.0.0.js on your website. A 'minified' version of Speech.JS is also available Speech.1.0.0.min.js.


## The Sample
The Oxford.Speech.JS sample demonstrates how to use the Microsoft Bing Speech API in a web application. It features using a .wav file or external microphone input to perform:
 * Short-form recognition
 * Long-form dictation
 * Recognition with intent


### Build the Sample
 1. First, you must obtain a Bing Speech API subscription key by [following the instructions on our webiste](<https://www.microsoft.com/cognitive-services/en-us/sign-up>).

 2. Start Visual Studio and choose the menu "File", "Open", "Project/Solution" the workspace file Speech \> Speech.JS \> Oxford.Speech.JS.sln.
 
 3. In Visual Studio , select menu "Build\> Build Solution" to build the sample.
 
 4. Choose the target browser you would like to use.
 
  <img src="SampleScreenshots/SelectEmulator.png"/>

 5. "Debug" to launch the sample app.

### Running the Sample
 1. In the web application, enter your Bing Speech subscription key under "Oxford Key".

 2. Select whether you would like to use the Microphone and what speech mode you would like to use by select "Use Microphone" and the "Mode" drop down box.

 3. For modes where you would like both Speech recognition and Intent to work, you need to sign up [Language Understanding Intelligent Service (LUIS)](<https://www.microsoft.com/cognitive-services/en-us/sign-up>) and set the key values in the fields "Luis AppID" and "LUIS SubscriptionId".

 4. To Start recognition, press the Start button.

  <img src="SampleScreenshots/SampleRunning1.png"/>


## Contributing
We welcome contributions. Feel free to file issues and pull requests on the repo and we'll address them as we can. Learn more about how you can help on our [Contribution Rules & Guidelines](</CONTRIBUTING.md>). 

You can reach out to us anytime with questions and suggestions using our communities below:
 - **Support questions:** [StackOverflow](<https://stackoverflow.com/questions/tagged/microsoft-cognitive>)
 - **Feedback & feature requests:** [Cognitive Services UserVoice Forum](<https://cognitive.uservoice.com>)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License
All Microsoft Cognitive Services SDKs and samples are licensed with the MIT License. For more details, see
[LICENSE](</LICENSE.md>).

Sample images are licensed separately, please refer to [LICENSE-IMAGE](</LICENSE-IMAGE.md>).


## Developer Code of Conduct
Developers using Cognitive Services, including this client library & sample, are expected to follow the “Developer Code of Conduct for Microsoft Cognitive Services”, found at [http://go.microsoft.com/fwlink/?LinkId=698895](http://go.microsoft.com/fwlink/?LinkId=698895).
