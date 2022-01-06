# Eva-voice
How to enable eva (cortana) voice in windows for normal use

## Must
The use must have windows 10 language to EN (US) since eva is only available for this language.
Cortana must also be set to use EN as language
Check the folder `C:\Windows\Speech_OneCore\Engines\TTS\en-US\` for files starting with `M1033Eva` (there should be 9 of them)

## Need
- Download the file `Microsoft-Eva-Mobile.reg`, and double click on it to merge its content with your registery (you can also open it with a text editor to make sure nothing bad is in it).  
- Restart your computer.  
- Open any software using TTS and check that `Microsoft Eva Mobile` is available for you to use.  
- Enjoy.

## Addon
Other mobile voices found in `C:\Windows\Speech_OneCore\Engines\TTS\en-US\` can be enabled by running the scipts `EnableAllWindowsVoice.ps1` from an admin PowerShell window. (You may need to open the file with a text editor and paste it in powershell)

## Honorable Mention
Big shoutout to this guy: [PessimistPrime (Aus)](https://www.reddit.com/r/EliteDangerous/comments/5d02vv/if_you_use_voiceattack_eddi_or_any_other/)
