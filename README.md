# Cortana Samples

You can create custom functionality for Cortana using the Cortana Skills kit or the legacy Voice Command (VCD) platform. Here is where you can find relevant samples:

## Cortana Skills Kit

Currently Cortana skills are built on top of the Microsoft Bot Framework. As such, majority of Bot Framework samples can be used to create Cortana skills. Here are some places to find samples:

* [Cortana Skills Samples - Build 2017](https://github.com/Microsoft/Cortana-Skills-Samples-Build-2017) - These are samples from the presentations on Cortana Skills at the Microsoft Build 2017 conference.
* [BotBuilder-Samples](https://github.com/Microsoft/BotBuilder-Samples)
* [BotBuilder - C# samples](https://github.com/Microsoft/BotBuilder/tree/master/CSharp/Samples)
* [BotBuilder - Node.js samples](https://github.com/Microsoft/BotBuilder/tree/master/Node/examples)

### Cortana Skills Kit Resources

| Platform     | Resources |
|--------------|-----------|
| Cortana Skills Kit | [Developer Dashboard](https://developer.microsoft.com/en-US/cortana/dashboard)<br/>[Documentation](http://aka.ms/CortanaSkillsDocs)<br/>[Developer Forums (MSDN)](https://social.msdn.microsoft.com/Forums/en-us/home?forum=cortanaskillskit )<br/>[Stack Overflow forums (cortana-skills-kit)](http://stackoverflow.com/questions/tagged/cortana-skills-kit) |
| Bot Framework| [Developer Portal](https://dev.botframework.com/)<br/>[Documentation](https://aka.ms/botdocs)<br/>[BotBuilder SDK](https://github.com/Microsoft/BotBuilder)<br/>[BotBuilder SDK Samples](https://github.com/Microsoft/BotBuilder-Samples)<br/>[Stack Overflow Forums (botframework)](http://stackoverflow.com/questions/tagged/botframework) |
| Luis.ai Developer Forums | [Developer Portal](https://www.luis.ai/)<br/>[Developer Forums (MSDN)](https://social.msdn.microsoft.com/Forums/windows/home?forum=LUIS)<br/>[Stack Overflow Forums (luis)](http://stackoverflow.com/questions/tagged/luis)<br/>[Luis.ai UserVoice](https://cognitive.uservoice.com/forums/551524-luis) |
| Microsoft Cognitive Services | [Developer Site](https://www.microsoft.com/cognitive-services)<br/>[Developer Forums](https://social.msdn.microsoft.com/Forums/en-US/home?forum=mlapi) |

## Voice Commands (VCD)

Here is a list of samples that showcase how you can join Cortana's team of experts:

**[Adventure Works Voice Command Sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/CortanaVoiceCommand)**

This app showcases how developers can integrate their apps with Cortana's speech and language understanding capabilities. 
When Cortana is listening, any of the following voice commands are supported. By default, "London", "Melbourne", and "Yosemite National Park" are provided as sample destinations. New destinations can be added in the app.

- "Adventure Works, show trip to London"
- "Adventure Works, when is my trip to London"
- "Adventure Works, cancel trip to London"

Infix and suffix forms are also supported.

- "Show trip to London in Adventure Works"
- "Show my Adventure Works trip to London"

Duplicates can also be handled. For an example of handling disambiguation, add a second trip to London in the app and try the following:

- "Adventure Works, cancel trip to London"

