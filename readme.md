![Clipboard Conqueror Graphic logo. The letters are clouds and buildings on a lush estate.](CCfinal.jpg)
Clipboard Conqueror - Readme
=============================
Clipboard Conqueror is a multi-platform omnipresent copilot alternative. Currently requiring a kobold united or openAI compatible back end, this software brings powerful LLM based tools to any text field, the universal copilot you deserve. It simply works anywhere. No need to sign in, no required key. 

Provided you are using local AI, CC is a data secure alternative integration provided you trust whatever backend you use.   

*Special thank you to the creators of KoboldAi, KoboldCPP, llamma, openAi, and the communities that made all this possible to figure out. 

If you are unhappy with my syntax, almost everything is configurable in setup.js. 

With Clipboard Conqueror, you can leverage AI abilities, invoke it by copying `||| "your request"` 

Local AI responds after copying commands or requests for information.

There is a wealth of information below and in this repo.
All you really need to know is copying ||| with Clipboard Conqueror and Koboldcpp running will send any text you copy with that ||| to local AI.

It will actually mess up funny picking up || after a simple invoke.  Reccomend |||code|| query for copying code blocks containing ||. Or change the default invoke setting.

[Install Node](https://nodejs.org/) Clipboard Conqueror requires Node to run. If nothing happens when you click the scripts, you likely need node.

Clipboard Conqueror reccomends [KoboldCPP](http://www.github.com/LostRuins/koboldcpp/releases/) for Windows users. Kobold does the actual AI LLM processing, Clipboard Conqueror bridges kobold with the clipboard for use anywhere. 

[OpenHermes 2.5 Mistral 7B 16K Context.GGUF](https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-16k-GGUF)

Get a model that fits in your graphics card or system ram, more details in installation, faaar below. 

[Download Clipboard Conqueror](https://github.com/aseichter2007/ClipboardConqueror/archive/refs/heads/main.zip). Unzip it.

Windows:
---
Run z-instalCC.bat

Run z-runCC.bat

I like z-runCCnodeMon.bat because it automatically restarts and loads changes in setup.js, unless settings files are enabled, that gets clunky. 

linux or Mac:
---
y-linux-mac-install.sh

y-linux-mac-start-no-nodemon.sh

For openAi access 
--------

put your key into the apropriate endpoints in setup.js and invoke with |||chatGPT3| or change the default in 0endpoints.json. |||chatGPT4| will hit turbo with defaults, change the target model in 0endpoints.json or setup.js.  For now, default behavior does not write the config files.

Kobold or other local inference engines are not required to use Clipboard Conqueror, but it requires paid openAi api credit to access their service. OpenAi access has been included to ensure anyone can master prompting with my tools, on any hardware.  If CC really gets rolling and meets my needs, I will host a dedicated cluster of my own to ensure free access for anyone, on secure and transparent terms with the excess. AI will change everything at an incredible rate, everyone deserves the best tools we can get our hands on in these trying times. 

Please help me share Clipboard Conqueror with everyone. 

Copy, Conquer, Paste.
--------

I solemnly promise that this application and at least one compatible backend will function in the absence of internet connectivity.
One of my design inspirations for this application is to spread LLM models to as many computers as possible. I want to ensure at least one intact system is recovered by future archaeologists, an incredible time capsule of culture, science, and data.  We should be sending intelligent boxes to deep space too. Our Knowledge and posterity must not go to waste. 

I need income. I've been looking for work all year and getting nothing but scams and my hopes up.
Please, if you get good use from this application, especially in a commercial setting, consider subscribing to my kofi, or hiring me. I'm a new father and not having stable income is just frying my brain. 
``````
patreon.com/ClipboardConqueror

ko-fi.com/aseichter2007

|||make these links in markup for a .md file
``````
Captain Clip: Here are the links formatted as Markdown for a .md file:

1. [Patreon](https://patreon.com/ClipboardConqueror)
2. [Ko-fi](https://ko-fi.com/aseichter2007)

I have provided the tools to supply your own custom always ready assitant in any application on your terms. You tip your delivery guy, please drop a coin for your coder, it will really help my family.

BTC: 0x92cB00214fd137E73Fa85eE80e04232D8b14Ea5a

DOGE: bc1qu0zp2y8gwmqelmq5radscdltjxy23t4u0rfx6s



Quick Start Jam, Reccomended:
---

[![YouTube Video](https://i.ytimg.com/vi/fcM8dDtVTYQ/hqdefault.jpg)](https://youtu.be/fcM8dDtVTYQ)

Quick demo: 

[![YouTube Video](https://i.ytimg.com/vi/n8tQJlne3qs/hqdefault.jpg)](https://youtu.be/n8tQJlne3qs)



Using Clipboard Conqueror to mutate content, and Installation: 


[![Youtube Video](https://i.ytimg.com/vi/NqnpBi0MHsc/hqdefault.jpg)](https://youtu.be/NqnpBi0MHsc)


 - *note in this video I mention context leaking with Context Shift, that was my mistake, for a bit I had a bug where re was persisting unexpectedly. 


Productivity:
-------------
Clipboard Conqueror makes the process of accessing an LLM simple and efficient in any workspace.

-  Locally run models can be trusted with private data and do not phone home or report any metrics. Local LLMS are private and secure. 

- Proofread documents, test explanations, get feedback, find inspiration, or just run a game of dungeons and dragons with your friends.

Clipboard Conqueror provides a whole toolbox of predefined assistants, ready to work for you.  



- |||agi|"AI Generate Instructions" will help you execute any operation you ask for help with. Captain Clip does well too, but this is based on the kobold agi script and is superior to a simple ask. 

- |||stable| will write you an image prompt for use in stable diffusion automatic 1111
This identity and some other cards were found on chub.ai, some are my own or significant customizations, or simply found out in the web.

- |||tot|"tree of thought" will expand and include near concepts, questions, or ideas to produce a more comprehensive solution


Save agents on the fly to store, sort, query, think, review, or just tell you jokes or anything you can  ask for, really. 

Key Features:
--------------
* Control every part of LLM prompts without needing to switch context to a different tab, window, or program. 
* Wtite and quickly call targeted agents for specific tasks.
* Quick saving of new agents and information for later use.
* Tailors text with proper formatting for precise AI responses.
* Locally run large language model support with KoboldCPP for powerful, secure, text processing.
* Supports multiple backends, diverse prompt configurations, and even a no code framework for prototyping chain-of-actor or chain-of-thought prompts for multi-step agent development pipelines.
* Supports multiple languages and contexts for diverse applications. Not all LLM models are multilingual, some configuration may be required.


Desktop Platforms:
--------------------
Clipboard Conqueror is designed to work seamlessly across multiple platforms including Windows, macOS, and Linux. It has been gently tested to ensure stability and compatibility.

Usage:
------
The Clipboard Conqueror format is extremely configurable, but always adheres to the following formula:

    (invocation"|||") optional agents and commands (optional split "|")  optional system prompt (optional split "|") user text (optional continue "~~~") optional start of assistant response

"!@# query" could be valid, "123ai+ query" could be valid, and "{!?!?!} agents (8)^ quick prompt (8)^ query" could valid, but there is no setting to change the order. 

Personally I like pipes |||agents|quick prompt|user query ~~~ start assistant response. The default. 


1. Enter `|||` followed by your request or command. Pipe "|" can be typed by pressing shift + backslash (above enter, left of enter for European layouts).
2. Copy the text to your clipboard. After a few moments, you should get a notification and the response is ready to paste:
  ```
  ||| "Ahoy Captain, open the airlock, we're coming aboard the Clipboard Conqueror"
  ```
  Copy the line above. Wait for the notification to paste the AI response. Sometimes my notifications are a little funny but I have about a thousand layers of mess running all the time so it could be something related to streaming stuff. Also errors have been reported with linux notifications and sounds. 

  ```
  |||introduction|
  ```
  This is a writing command, it provides immediately ready to paste text from this application. It will tell you about LLMs and how they work, and explain the settings that are useful to control generation. Ready to paste immediately. Currently after using a command that writes data from the application, "|||agent,write|", "|||help|", "|||introduction|" the next copy made will not send text to the AI. Copy your command again, it should work the second time. If not, ensure you are only copying one ||| invoke with your text. 

  ```
  |||character,temperature:1.4|What is a square root and what dishes and sauces are they best served with?
  ```
  aside: there does not appear to be a too hot for general queries, is this thing on? Hermes is simply not having any square root soup. 
  This is exemplary; character is not a default prompt. Captain Clip will respond. Try:

  ```
  |||frank,!Frank,user| "Hello, Frank. You can't hide from me. Show yourself."
  ```
  Here we have set the assistant name to Frank, by prepending the desired name with an exclaimaiton point, as well as included his character card. Llama-3 is particularly good with the assistant name set. Set names persist until changed or CC is restarted. 

    There are 5 special operators for the |||agents| segment, that start with the symbol, and end with hte next comma "," (agentSplit).
    - "!" assitant name
    - ">" user name
    - "}" system name
    - "~" start of assistant response, ~~~ overwrites a this one.
    - "%" format like format |||%chatML|, do this one first if you use it, it overwrites the others. 

    ||| %chatML, ! Rick, > Morty, writer, } Narrator's notes| Rick answers morty's questions.| Where are we going today, grandpa? 
    
  ```
  "prompt": "<|im_start|> Narrator's notes{\"system\":\" Rick answers morty's questions.\",\"writer\":\"Write a lengthy prose about user's topic. Do not wrap up, end, or conclude the narrative, write the next chapter.\\n \\n\"}<|im_end|>\n<|im_start|> Morty Where are we going today, grandpa?<|im_end|>\n<|im_start|> Rick"}
  ```
  "%}>!" all persist until overwritten. 
  
  Clipboard Conqueror inserts the data to assemble a complex query in seconds. 

  ```
  ||| } set system name, >set user name, ! set assistant name | quick prompt | each change the corresponding portion of the prompt ~~~ Clipboard Conqueror is ready to completely control any LLM!
  ```
  prompt: "<|start_header_id|> set system name<|end_header_id|>\n\n{\"system\":\" quick prompt \"}<|eot_id|><|start_header_id|>set user name<|end_header_id|>\n\n each change the corresponding portion of the prompt<|eot_id|><|start_header_id|> set assistant name<|end_header_id|> Clipboard Conqueror is ready to completely control any LLM!"


|||~~~ sets text after the "~~~" to the start of the assistant reply for this turn only. 
  ```
  |||frank,mem|Frank, how many fingers am I holding up?
  ```

  Ask Frank Drebin if he has information contained in tag "mem"

  - Note: Agents, memory agents, and instructions can be combined like |||agent1,agent2|.
  Three pipes, agent, one pipe. No spaces. Any agents or settings must be closed with one pipe or the names will be sent as text to the default agent (Captain Clip).

  ```
  |||2700| write a long story bout a picture of a story where an artist draws a picture of a story about an artist being written by an author
  ```
  - sets the max response length to 2700. Also works like |||agent,setting:0.5,1000| just a number is always max response length.

  ```
    |||temperature:1.1| be more unpredictable, normalize probabilities by 10% after other samplers.
    ```
  - sets the temperature to 1.1. This works for any setting, e.g., top_p, min_p. supports :true :false. Overrides the params in setup.js.
  - Only persists in memory and used for the defaultClient set in setup.js. |||settings:set| are not used for secondary endpoints used like |||tgwchat|.
  ```
    |||re| what is this code doing? 
    ```
  - return copy at end of prompt inserted after user prompt.
  - sends the thing you copied last after "what is this code doing? \n \n", copied text here at the end of the user prompt" and sends the Captain Clip assistant in the system prompt.
  ```
    |||rf| what is in the rf agent? 
  ```
  - return last copy in system prompt inserted like an agent at the level rf is placed relative to other agents ex |frank,rf,tot| copied text comes after frank agent in the system prompt.
  

  ```
  |||memory:save| writes or overwrites an identity called memory with this text: " writes or overwrites an identity..."
  ```


  ```
  |||mem:save| SYSTEM: take on the role of {{character}}, description:  description.
  ```


    It's useful to save information like

  ```
  |||memory:save|thisFunction(variable){ return variable + variable * variable; }
  ```

  and then use it like

  ```
  |||coder,memory| describe the function of the code and suggest descriptive variable names. 
  ```
  ```
  |||memory| walk me through the expected output if "variable" is equal to 10. 
  ```

  ```
  |||memory:delete| removes memory, defaults will return when Clipboard Conqueror is restarted. 
  ```


  List is for knowing what is available. It will provide an easy to expand list of available agents.

  ```
  |||list|
  ```
  The list command sends a list of current agents in memory to the clipboard, ready to paste out immediately.

  ```
  |||mem,write|
  ```
  The write command will copy the entire prompt of all entered agent tags to the clipboard ready to paste, and then copy back under a new name or edited.

  ```
  |||agent:file|
  ```
  The file command saves that agent to the 0identities.json file. Currently only supports agents and will save settings values as agents if you tell it to.  Currently the only way to delete filed agents is to delete them from 0identites.json or delete the json entirely to restore defaults next run.

  ```
  |||code|| 
  ```
  By sending a second pipe "|" on the end, you avoid collisionss with "||" OR operators. Alternatively, you could change the invoke delimiter in setup.js (instruct.endTag)

  Currently after using a command that writes data from the application,"|||list|", "|||agent,write|", "|||help|", "|||introduction|", or "|||dw|" you must copy your next query twice before it sends to the LLM.




--------
OpenAi Compatible 
-----
  Clipboard Conqueror supports infinite configurable endpoints. You can add as many as you like. 
  CC supports multiple parameter sets to ease multiple backend configurations.

  It can support anything that takes either a string or "messages" openAI api style input, but currently doesn not support SSL properly. LMstudio and Koboldcpp's openai api endpoints return cryptic errors. Something about SSLv3 and a generic bad request refusal. Debugging things I didn't make is hard with the baby interrupting, I can't just think it out and put in the changes, I gotta dig. Any insights would be appreciated.

  TextGenerationWebUi does not need to launch with --API. Or I might have the openAI add on enabled and saved settings. The verbosity of TGWUI leaves something to be desired. Prefer KoboldCpp because there is better indication that the query is being processed, and how much longer that might take. Feedback and issues about compatibility are appreciated.

  Move your favorites to the top and invoke them by |||$| from top to |||$$$...| at bottom. Or just use the key names like |||kobold| or |||tgwchat|  

  ```
  |||$|this message will go to the first configured endpoint in setup.js or 0endpoints.json if settings files are enabled
  ```

  ```
  |||$$|this will go to the second configured endpoint
  ```
  ```
  |||tgwchat|this will go to the TextGenerationWebUi openAI endpoint.  (|||ooba| for standard completion isn't working as expected, it only sends back 16 tokens despite asking for more.)
  ```
  Add endpoints and parameters in settings.js or 0endpoints.json if settings files are enabled. File writing is off by default, the settings files are more for use with binaries.

  When using these commands, be aware that data may be sent to outside systems. This may be a breach of your company's data protection policy.

  |||$,set| will behave as expected and send to the compatible endpoint until |||set| to release. //todo: determine if this is broken.


  You can safely use any other command to query sensitive data, and depending on your configuration, gpt commands can be sent locally as well. 


super advanced save: 
---
``` 
|||CurrentText:save,re,LastCopy:save|CurrentText
``````
- if the re flag is set, saved agents come from the last copy. This allows saving an agent from the current text that is distinct from the lastCopy agent which comes from the last clipboard contents, and allows saving agents while making an initial query like:  


```
|||re,frank,dataCopiedLast:save| Hey get a load of this!
```

- This will save the last copy to the clipboard into dataCopiedLast and send the frank system agent and user "Hey get a load of this!" followed by the last copied text to the LLM. Note, tags between the | | parse left to right. It matters where re is placed

``` 
|||frank,dataCopiedLast:save,re| Hey get a load of this! 
```
- will save "Hey get a load of this!" to dataCopiedLast because re is not activated until after the :save.

```  
|||CurrentText,LastCopy| query combined next like this. 
```

System commands
---

```
||||System command sends before captain clip | "user query"
```
- note 4 "|" to send a custom system prompt with the default agent
```
|||writer| system command sends before writer| "user query"
```

This syntax lets you command the system directly at the same time you send as user. 

```
|||| assistant gives really weird bogus advice: | how can I become as pretty as OPs mom?
```
- not the advice I was expecting, I wasnt expecting "stalk her down and become her". WOW!

```
||||System: Command first before Clip agent.|  query from user
```

^^^^note 4 "|" , and the close on the end above but only 3, then agents|, then system, then closing "|" below.  

```
|||writer| Command First.| User: after agent writer
```


Clipboard Conqueror applies formatting like:
```
"prompt": "<|start_header_id|>system<|end_header_id|>\n\n{\"system\":\" Command First.\",\"writer\":\"Write a lengthy prose about user's topic. Do not wrap up, end, or conclude the narrative, write the next chapter.\\n \\n\"}<|eot_id|><|start_header_id|>user<|end_header_id|>\n\n User: after agent writer<|eot_id|><|start_header_id|>assistant<|end_header_id|>\n\n"
```

"system" is a configurable key in setup.js and should only be present when a quick prompt is specified and removed if it is empty.

```
|||re,frank|this text is invisible to :save| user query ~~~ and this text is invisible to save as well. 
```
instant system prompts like |||e ( *for empty prompt* )| off the cuff system prompt.| are preserved with |||set|.

|||set|
---

```
|||rf,frank,set,joe|these system commands persist| query goes out. 
```

- set will save all agents before it as a persistent default, and include any system command sent at this time. in this case joe does not persist with the next simple invoke ||| 

once set "|||"{query} will behave as 
```
|||(that last copy saved with rf),frank|these system commands persist|{query} 
```


until |||set| is copied again, clearing the set agents. 

While set, |||any,additional,agents| can be sent and add after the set agents, and will go along after the set agents.

|||rf,set| is extremely useful for repeated queries against the same copied data. 

while set ||||any| any replaces the old system instruction before agents this time only.

- again note 4 pipes before system insert. 


Multi agent chaining and complex agent workflows. 
---
Clipboard Conqueror is a no code and non code testing, basic multi-agent chat framework ready to operate on or in any context. 

CC supports chaining agents sequentially like:

```
|||agentFirst,@agentSecond,#@agentThird,#@@anotherAgentThirdandFourth,##@agentFourth,@@@c,@@@d| and on. 
```
Special initializers "! > } %" are supported when batching. 


"@" executes, and it is reccommended to use specifically targeted chaining agents which I have not developed yet. I'm hoping someone has used superAGI and can point me a direction.

"#" Skips execution, or whatever you like, as everything else in Clipboard Conqueror it can be adjusted to your satisfaction in setup.js.

I like to think of it like feeding a tape, so I can send in the manager every so often to keep track like ###@##@##@#@@@#manager, who knows what you will find with workflows like this that can be shifted and set up in moments and executed by small LLMs in minutes. 

If you're quick you can just paste out each step. 

"d" or "debug" like ,@@@@debug saves a growing output of each turn if not skipped like ##@#. this example returns only the third to final of the 6 total interactions. The final output is never captured, the first input can be captured like |||agent,@agent,d,@d| @ chains always execute second.


return the debug log by copying  |||dw| or |||debugWrite| and paste.  The first turn is the initial query followed by what this contains, and the final output is not contained with d.  "dw" returns the middle for debugging your bot interactions. 

"c" or "continue" works similarly to send the log internally to the LLM with minimal markup "</s>"  between messages to build more of a chatlog.  

endpoints defined in setup.js or 0endpoints.json. can be used and chained by name like |||@textGenWebUiChat|
```
|||@tgwchat,#@chatGPT3|initial query
```
In this case, Captain Clip will be sent first to Kobold with the initial query. The output from Kobold then goes to TextGenWebUi completions, and the out from there to ChatGPT 3.5 turbo though the openAI api. Here, there are no agents defined for the second and third queries. Add them like |||@tgwchat,#@chatGPT3,@writer| will send the writer agent to TextGenWebUi completions. If we added c,@@c then c is built up like a chatlog and sent in the system prompt.

Chaining Captain Clip or AGI will stop the chain of execution. (agents with instructions to write invokes cause the chain to stop)

```
|||frank, ! Frank,@abe,@%chatML, @! Abe,#@frank,#@%llama3 #@! Frank, kobold,#@kobold,@tgwchat,c,@@c|
```
This query will build a multiturn conversation, Frank's response(kobold api) to the initial query is sent to abe marked with chatML format(Text Gen Webui api), abe's response to the query is sent to frank(with llama 3 markup on kobold api), 


|||dw| will contain the c links from the end, showing the intermediary steps. 
- if you copy |||dw|, you will get back the middle conversation steps as carried by c. Or it's in the clipboard history as well, I never used that really, sorry clipboard history champs. This app absolutely pollutes it. I gotta rebuild in c# to fix that.
- |||dw| is a writing command so it causes the hang where you have to copy text with no invoke. I gotta figure this bug out...


"c" carries the chat context forward optionally like #@#@c.
"&" will set the history splitter to the target name like
```
|||cot, !Query Node, @! Rick Sanchez @& Rick's Inner thoughts| 
```
Will present the query node as a discrete turn labeled Rick's Inner thoughts in the c log. C is cleared at the end of execution but stored in dw until the next query.



Sending names like !Name @!Name, or setting any prompt segment like |||PROMPT:{{segment}}| will hold prompt format overrides, interfering with multiple backend support, use  noFormat: true as a key, (example: setup.js line 100) per endpoint, to prevent sending jinja or kobold adapters and preserve the default instruct format supplied by the backend from the model config when using multiple models with different instruct sets.

Handle % format changes first, like %alpaca !name or the format change overwrites the name change. 




Prompt Formats:
---
Change the instruction format like :
```
|||FORMAT|chatML
or
|||FORMAT|alpaca
etc.
```
Formats must exist in setup.js or 0formats.json, the name must match the object key. Files override setup.js when enabled, so if you use settings files, you have to delete or rename them to reflect changes in setup.js.
I added some extra complexity, I apologise for the bit of extra noise, but there are use cases.

When the format is changed, it persists across backends. This is to ease testing of multiple models with different formats. To sidestep this limit, edit the format in setup.js or 0formats.json and assign the correct one in the endpoint definition or 0endpoints.json.


Or you can set individual prompt segments like this:
```
|||PROMPT:startTurn|<|im_start|>
```
```
|||PROMPT:endSystem|<|im_end|>\n 
```
```
|||PROMPT:endUser|<|im_end|>\n
```
```
|||PROMPT:endTurn|<|im_end|>\n
```
```
|||PROMPT:systemRole|system\n
```
```
|||PROMPT:userRole|user\n 
```
```
|||PROMPT:assistantRole|assistant\n
```
these set up basic ChatML formatting, the rest are kind of extra. For alpaca I reccommend setting the format strings in the role positions. StartTurn starts all turns; system, user, and assistant.  
StartTurn is a bad place for "### Instruction:" as it goes before user and assistant as well.
```
|||PROMPT:prepend|You are a helpfull assistant\n\n 
```
- persistent context before agents
```
|||PROMPT:systemAfterPrepend| still before agents. 
```
- This is here for double system prompts, you can close the first and open the second here where prepend contains the meat of the hidden persistent system prompt. 
```
|||PROMPT:post| after agents. 
```
- I use this to close an open codeblock on on the system prompt. 

```
|||PROMPT:systemMemory| spot for persistent system context after agents
```
- Above set system prompt segments, below set user and asssistant prompt segments.
```
|||PROMPT:userMemory| 
```
- spot for persistent user context before user query
```
|||PROMPT:start|start of the AI response
```
- This defines the start of the AI response. If you desire pure text completion, save this in here and use empty prompts like "|||e|" Or steer it by sending agents and a user query.

and special for jinja formatter only:

```
|||PROMPT:special|.rstrip() //Probably not needed for typical use. Not sure what .rstrip() does. I think it removes whitespace at the end of the string, really I hate this behavior for CC. I want to know exactly what the machine sees. 

```
I think I missed a few. CC supports a lot of flexibility in prompt formats.
None of these are case sensitive. |||PROMPT:SySTEMmemOrY| is the same as |||PPROMPT:systemmemory|||. There are a few options to hit these as well, such as username or name, endturn or end, etc. I've hopefully reached easy to remember without adding confusion.


note: current behavior removes chatml markup "<|" any "|>" from the ai response to ease use of non chatML models with default settings. For the most part monster merge models respond very well, but will markup character dialog in a way I find undesirable. Comment line 24 "text = this.removeChatML(text);" in responsengine.js to stop this behavior. Response engine is ready for function calls, let me know what would be useful.

---
Installation:
---
Currently there are no built binaries and Node is required to run Clipboard Conqueror.

|||how to to install node for normies. Use markdown suitable for a .MD for links

1. Assumption: You are seeking instructions on how to install Node.js for someone with little technical knowledge and would like the explanation to be in a Markdown format suitable for a .md file.

    Step 1: Visit the official Node.js website [Get Node](https://nodejs.org/) and download the installer that corresponds to your operating system. Node 20 is sufficient.

    Step 2: Double-click on the downloaded installer file to start the installation process.

    Step 3: Follow the on-screen prompts to complete the installation. Ensure to check the box for "Add to PATH" during the installation to have Node.js available globally on your system.

    Step 4: Once installed, test Node.js by running the following command in your terminal or command prompt: `node -v`




2. Clipboard Conqueror is most powerful with [KoboldCPP](http://www.github.com/LostRuins/koboldcpp/releases/),or a kobold compatible API. [openAI compatible API](https://github.com/oobabooga/text-generation-webui) CC works with either or both! or just an openAI key. Or even more! I'd love to hear how you connect your choice of backend for a compatibility list and maybe adding your settings to the defaults.


    For macOS get KoboldAi, TextGenerationWebUi or anything that hosts a completion or chat api. //Notes below for linux and mac, thank Herro.


    a kobold or openAI compatible api must be running to use Clipboard Conqueror for free.
    I supply a sample batch file for loading a model with your settings file after you get kobold dialed in from the launcher. 

3. Kobold needs a model. I like GGUF because it is one file rather than a folder of mess.
   Here are my reccomendations 4/30/24:[Llama 3 GGUFs](https://huggingface.co/bartowski/Meta-Llama-3-8B-Instruct-GGUF) get one that fits in your ram with 1.5gb free for context and basic windows stuff. 

   CUDA0 buffer size =  7605.33 MiB : this is the memory size of the Q8 quant for Llama 3 8B

   CUDA0 KV buffer size =  1036.00 MiB 8192(8k) context. 

   With some extra stuff open(web browser, vsCode, etc) I'm at 11 GB vram utilized in total. Without using a graphics card, this would all be in regular ram.

    Most of my prompts are tuned against OpenHermes 2.5 Mistral 7b with chatML. Some against Llama 3 8B.
    any chatML model should work great out of the box. 
    Psyfighter2 works pretty well too, though it doesn't nail the instructions as well being a storytelling model. 
  

Finally, [download](https://github.com/aseichter2007/ClipboardConqueror/archive/refs/heads/main.zip) Clipboard Conqueror from this repository. 

windows:
---

run z-instalCC.bat

after it finishes run:

z-runCC.bat

Mac/Linux
---

y-linux-mac-install.sh
y-linux-mac-start-no-nodemon.sh

or just run from the folder:
npm i

npm start      
(windows)

or 

npm run linux for both linux and mac

Troubleshooting:
---

If Clipboard Conqueror closes on launch, ensure you have Node installed and have run an install.bat or .sh.

The most common issue with setup is people who expect they have node but do not. 

If Clipboard Conqueror seems unresponsive, close and open the console.  If you are running with nodemon, type rs in the console and hit enter to restart the app.

For API errors make sure Koboldcpp or your choice of backend is running, and that it is set as the defaultClient in setup.js. I always get impatient and beat the API to the ready mark. I should finish squasing the API error problems so it doesn't hang, but I gotta figure out why I can't hit LMstudio first.


If CC seems hung, copy text with no invoke and try again. When using Text Generation Webui, it's can be hard to tell if it's working. Consider asking for fewer tokens until you know it's working. 
Sometimes models take up to a few minutes to respond. If it is taking longer, make sure you aren't running out of memory. There is a setting in the nvidia control panel that controls how memory overflows are handled. The default setting starts offloading a before memory is all the way full, so I disable this, in favor of crashes over very slow generation. 

currently the entire settings for my app are in setup.js.
setup.js writes files for each type of setting. If formatting errors are introduced in those files, they are overwritten with the defaults. 


-----
Choosing A Model:
--------

The links below are to OpenHermes 2.5 Mistral 7B.

OpenHermes-2.5-Mistral 7b 16k.gguf supports 16384 context, a decent few pages. 

If it seems slow, reduce your context to 8k. If the problem persists, select a smaller Quantization.

hardware("token speed")  [fast = 20+ tokens/sec, medium =  ~<10 tokens/sec. slow = <2tokens/sec]* Lower on this chart is smarter. Partial offloading the video ram is possible but costs speed. 

```
In the world of inference, some macs can be medium with even very large models. Metal. 
```

Quant links:
---
16gb ram and no graphics card, or laptop with shared gfx memory(slow, notable quality loss): 

[Q3_K_M](https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-GGUF/blob/main/openhermes-2.5-mistral-7b.Q3_K_M.gguf)VRAM used: 5429.57 MB (model: 3301.56 MB, context: 2128.01 MB) + a bit for ingestion, use lower quants for less than  16gb  RAM consider Rocket 3B//untested


.

Less than 8gb gfx cards(fast-medium, notable quality loss): 

[Q3_K_M](https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-GGUF/blob/main/openhermes-2.5-mistral-7b.Q3_K_M.gguf)VRAM used: 5429.57 MB (model: 3301.56 MB, context: 2128.01 MB)


.

8gb gfx cards(medium, prompt ingestion might not fit in mem. If slow, consider as low as 4k context if faster, or partial offload a few layers to keep context processing fast): 

[Q5_K_M 16k context](https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-GGUF/blob/main/openhermes-2.5-mistral-7b-16k.Q5_K_M.gguf)VRAM used: 7691.57 MB (model: 5563.56 MB, 8k context: 2128.01 MB)//I think this data is for Q6


.

12gb gfx cards (fast): 

[Q8_0 16k context](https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-16k-GGUF/blob/main/openhermes-2.5-mistral-7b-16k.Q8_0.gguf) total VRAM used: 9333.84 MB (model: 7205.84 MB, 8k context: 2128.01 MB) 11413.84 MB (model: 7205.84 MB, 16k context: 4208.01 MB)

.

24gb vram(fast): 

[Q8_0 16k context](https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-16k-GGUF/blob/main/openhermes-2.5-mistral-7b-16k.Q8_0.gguf) total VRAM used: 9333.84 MB (model: 7205.84 MB, 8k context: 2128.01 MB) 11413.84 MB (model: 7205.84 MB, 16k context: 4208.01 MB)

.

32gb ram and not using graphicss card(slow): 

[Q8_0 16k context](https://huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-16k-GGUF/blob/main/openhermes-2.5-mistral-7b-16k.Q8_0.gguf)  RAM used: 9333.84 MB (model: 7205.84 MB, 8k context: 2128.01 MB) 11413.84 MB (model: 7205.84 MB, 16k context: 4208.01 MB)

other models:
---------
minimum hardware:[rocket_3B](https://huggingface.co/TheBloke/rocket-3B-GGUF) should be chatML I havent messed with it much.

[Nous-Hermes-2-SOLAR](https://huggingface.co/TheBloke/Nous-Hermes-2-SOLAR-10.7B-GGUF) total VRAM used: 11652.35 MiB (model: 8294.06 MiB, 16k context: 3358.29 MiB) This might be my new favorite. 

[Solar 10B](https://huggingface.co/TheBloke/SOLAR-10.7B-Instruct-v1.0-GGUF) this one is impressing me. solar-10.7b-instruct-v1.0.Q6_K.gguf total VRAM used: 10123.63 MiB (model: 8294.05 MiB, 8k context: 1829.58 MiB) Works great with default chatML instruct

[psyonic-cetacean](https://huggingface.co/TheBloke/psyonic-cetacean-20B-GGUF) psyonic-cetacean-20b.Q4_K_M.gguf total VRAM used: 22001.74 MiB (model: 11395.73 MiB, 8k context: 10606.00 MiB)
 

For large models, set the batch size lower in kobold to keep the working context memory requirements smaller. I like 128 these days. 5 threads on a 6 core system to preserve responsiveness.
         

  >I thought about recommending other models, but OpenHermes 2.5 is simply decent and fast, even tested on a friend's old 1080, under one minute for complex queries and with no gfx acceleration on 16gb ram its painfully slow to ingest, a few minutes for a large query and response.  smaller batch size helps you be sure its not hung up. 

  >let me know about your hardware and token speed and i will make this reflect the general experience better. 

  >Info for model selection. Preferred format chatML, but you can change the instructions in the settings.
  
  Model sizes(unquantized):
  ---
 - 3B needs at least 4GB RAM total ram + vram (gfx card must support cuda or the amd one so super old stuff isn't that useful)
 - 7B needs at least 8GB RAM
 - 13B needs at least 16GB RAM
 - 30B needs at least 32GB RAM
 - 65B needs at least 64GB RAM

  And they all need some space for the context. GPU offloading puts the layers of the model into the memory of your graphics card. Fitting the whole model into VRAM makes things way faster. 
  
  For reference, at 2048 context in Q4_0*, a 6GB Nvidia RTX 2060 can comfortably offload:
  - 32 layers with LLAMA 7B
  - 18 layers with LLAMA 13B
  - 8 layers with LLAMA 30B

 You can load the model in memory, see how much your final model memory cost is in the console, and get a rough estimate of the size of each layer by dividing the size in memory by the number of layers. Remember to leave room for the context, which can get big fast. At 8k context I think use over 5gb of memory with the Q8, just for the context alone.

>*Model bit depth is trade between output quality and output speed.  Generally, larger parameter number models are smarter and can follow more complex instructions.
KoboldCPP uses GGUF format, which are quantized from 16 bit to between 2 bit and 8 bit depending on model. (I like 8 bit if it fits in vram with room for 8k context.)
lower bits require less ram, but there is a drop in reasoning and writing quality, though even the Q2 was following instructions well. 

Not all models support chatML format, and most wont perform optimally without their expected format.

Large Language Models:
---

LLMs are powerful tools but it's important to understand how they work. The input text is vectorized and put through matrix transformations and a big complex vector is built, and then each word is added to that vector as it is chosen in turn one at a time, with some randomity to get better speech flavor, until the next probable token is a stop token or max length is exceeded.

In an LLM every word is a cloud of numbers that represent how that token relates to every other and some phrase structures or collections of tokens. By turning words into numbers, we can then beat them with math and determine which tokens probably are appropriate to go next.

It doesn't really reason, it doesn't really think, it amplifies patterns and guesses using probabilities and random, each next word chosen with such accuracy and literate complexity that kind of functionally it simulates having thought.  An important note: LLMs return a list of probable tokens and their probability, and after the LLM has done the math, one word is selected by user set rules from the returned set.  

LLM models don't make the choice, sampling happens after and then the machine is asked for the next tokens to choose from, ev-ery -to-ke-n - however the words are sliced.

It's weird, but they have no state, it's data-crunch-out every word in turn, no real consideration. 

Use them effectively within their limits to succeed in 2024.

You can go find the right data and paste the text at an LLM and it can use that data, but no LLM should be trusted implicitly, just as a first resort, right here aboard the Clipboard Conqueror.


Quantization:
-----
Here is the download on quantization as I understand it.

You take a 16 bit number, and you don't shorten it.

You collect all the numbers that are constituent or very near to the token vector, and you cut those off small and package them together in a table referenced by the full number

The collected tokens retain some information from their original vector, they arent simply collected, they are compressed with some loss.

Then you cut off bits from the full number's end but preserve its beginning and vector orientation, so rather than a rife bullet and bullseye you have instead a shotgun shell with shot to hit a wide target on the vector. The words still fly roughly the right direction, but there is more variance in how they land, leading to loss of which word was optimal and instead landing on a whole cloud of "should be close enough" Effectively the same words are presented at 2 bit and 16 bit when the samplers run, but they have less fidelity in the model, many words weight the same on the final selection instead of the natural best word having a highest value.


Because we choose from that selection randomly anyway, the detectable loss is very low, but lower bit depth is generalizing more words and concepts together more closely than 16 bit.

Think about a radius, a ray pointing from center out inside a sphere. Unquantized it is a line to a word. Quantization makes that ray become a cone with the wide base on the sphere's surface centered on the original vector point. Words inside the cone are treated like the same word, but that is slightly oversimplified.

extreme quantization works because even if you make the sphere sides a binary choice, you're still beating enough tokens against it that the result is narrowed to a small enough vector to hit the concepts, but it loses accuracy and ability to be specific other than by luck and elimination of actively poor words rather than choosing best like an unquantized or less compressed model.

Because 8Bit still carries enough data to maintain distinct accuracy even packaged, the loss is effectively negligible as the distinctions aren't as aggressively bundled and boiled down.

Base models vs Finetunes:
----
In the world of LLMs there are two kinds of models. 

Base models - these models are completion models, they respond well to: "sure, here is a code block containing fizzbuzz in javascript:" it will complete the statement you start.

Finetuned models can, depending on how they have been tuned, make sense of more direct orders: "write Fizzbuzz in javascript". Not all finetunes are instruct models, read model descriptions to learn what a model is designed for.

Finetuning typically means creating a lora, but often the entire model is merged with the lora for distribution rather than distributing the lora alone, I expect because loras will be model specific or wildly unpredictable when applied to different bases.

Base models are not fully cooked, they have some training room remaining to allow finetuning of the output. 

Finetunes are finished models that can't be further trained without detrimental effects. 

The models I have recommended are all finetunes, because you can speak to them more naturally and get good results. Base models take a little more thinking to interact with till you're used to it. 


Model Merges
---
Some models, "monster merges" are different model layers shuffled together with various levels of strategy and I think a bit of finetuning on top.

Other techniques average the weights of a model with another. 

Then there is distillation, which I have yet to dig into. 

Model merges often result in odd sizes, so not all models fit the typical 3/7/13/30/65 progression. 

M-O-E
---
Mixture of Experts models have many layers and gate which layers are used for each token. Each layer contains different combinations of "experts" tuned on different tasks. I believe Mixtral 8x7b has 256 layers or something and to save on compute at inference time many layers are skipped, different ones each token. This strategy should help specific accuracy by breaking the model into smaller pieces and training each for different knowledge sets. I think this also possibly reduces training memory requirements or could.

Linux/Mac Notes. 
----
  The notification when generation finished workes but there is no audible sound. Consider investigating how to define one in the toast notification config object in copyconqueror.js line 43.


Quick launch shortcuts:
---


I provide sampleLaunchKoboldBat.bat and hermes16.kcpps to ease making quick launch shortcuts. They need to be changed to match your system, and the bat expects to be in the same folder as both koboldcpp.exe and hermes16.kcpps.  hermes16.kcpps contains a full path that must match the model location, I recommend loading and saving the file to change the target. Also, lately I have found smaller batch sizes is better when I am pushing my memory limits, 512 and higher end up putting context on the hard drive at large contexts.

--------------------------------

Begin elevated computeration. 
--------------------------------

Copy this line:
```
|||introduction|
```
paste in a text field, a big one. Read the introduction. It's jam packed with information.
three pipes invokes the AI. If you want to skip the introduction you can get right to things like:
```
|||what is an inverse square root and how is it useful. 
```
Have fun and remember you can always ask for
```
|||help|
```


//I'll just leave this here https://www.reddit.com/r/bookmarklets/comments/d8pqe2/toggle_design_mode/
---

Settings Conqueror is poor and should be avoided.
---
 It will mess your settings up. Current defaults avoid writing files because my use case is hampered by the development impact of said files. Settings files and Settings Conqueror are more for use with binaries that I haven't got around to yet. 

---------------------------------
This application will get binaries when I am happy with it, for now it's a very basic GUI for changing the settings. 

Settings Conqueror is currently delayed while I think hard about how to make user definable function calling and how to make that a neat package that is easy to use. 


It also needs node, and can be run with the install and run batch files in the folder.


Bug Reports and Feature Requests:
---------------------------------
If CC seems hung, copy text with no invoke a couple times and try again. 

If you encounter any issues while using Clipboard Conqueror or have suggestions for future improvements, please report them via github or email me at "clipboard.aseichter2007@gmail.com" I will work diligently to address and resolve any concerns.

I'm chasing a bug where after |||list| or |||agent,write| the next copy is not parsed, but is stored, preventing the same thing being copied and invoking the AI.  Workaround: copy text without an invoke to clear the stored copy and allow a "fresh" copy that will activate the parsing engine. 

Saving agents like |||re,name:save|"more details" is likely to mess you up, it will save the last text you copied into "name" rather than "more details"

Please use Clipboard Conqueror responsibly and respect copyright and laws in your country while generating content. Misuse of this tool might lead to unintended consequences and breaches of privacy or intellectual property rights. I hold no responsibility for the data that passes through this tool on any system.  


Project License:
--

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Additional Terms:

While the MIT License permits free use, modification, and distribution, I kindly request that you refrain from creating works containing my verbatim code without permission from the original author (aseichter2007). In part because it's terrible code. You're welcome to bits of it, but please don't distribute it in full as your own work. If you have any inquiries regarding modifications or feature requests, please contact me at clipboard.aseichter2007@gmail.com or open an issue.

Your understanding and respect for these terms are appreciated.


Additional Resources:
[AMD GPU resources](https://llm-tracker.info/howto/AMD-GPUs)
[The HitchHiker's guide to LLMs](https://osanseviero.github.io/hackerllama/blog/posts/hitchhiker_guide/)

[LLMs, how do they work?](https://bbycroft.net/llm) this is a cool visualization of how the machine does the magic.

[OpenHermes 2.5 Mistral prompting ideas](https://www.reddit.com/r/LocalLLaMA/comments/18j59g1/you_are_a_helpful_ai_assistant/)]

This info belongs here somewhere.
// GSM8K is a dataset of 8.5K high-quality linguistically diverse grade school math word problems created by human problem writers

// HellaSwag is the large language model benchmark for commonsense reasoning.

// Truful QA: is a benchmark to measure whether a language model is truthful in generating answers to questions.

// Winogrande - Common sense reasoning
// `

1.	GRADE (Goal, Request, Action, Details, Example): Structures prompts to be goal-oriented and actionable.
2.	RODES (Role, Objective, Details, Example, Sense Check): Enhances precision and relevance with a final sense check.
3.	Chain of Thought (CoT): Encourages step-by-step articulation of reasoning processes.
4.	Zero-Shot and Few-Shots Learning: Prompts AI without or with minimal examples to demonstrate adaptability.
5.	ReAct (Reason and Act): Combines reasoning and task-specific actions in one prompt.
6.	Instruction Tuning: Fine-tunes AI on specific instructions for better direct response performance.
7.	Interactive Prompts: Engages AI in a dynamic back-and-forth interaction to refine outputs.
8.	TRACI (Task, Role, Audience, Create, Intent): Tailors prompts by considering task specifics and audience.
9.	TRAACI (Task, Role, Analyze, Audience, Create, Intent): Adds an analysis step to TRACI for deeper insight.
10.	Scaffolded Prompts: Provides a series of incremental prompts for complex or educational tasks.
11.	SMART (Specific, Measurable, Achievable, Relevant, Timebound): Applies goal-setting principles to prompt engineering.
12.	Prompt Chaining: Uses sequential prompts for complex or multistep tasks.
13.	Contextual Prompting: Incorporates rich context for more accurate and relevant responses.
14.	Contrastive Prompts: Uses contrasting examples to clarify what to do and what to avoid.
15.	Meta Prompts: Prompts about creating or optimizing other prompts.
16.	Dynamic Prompting: Adapts prompts based on real-time feedback or changes.
17.	Multimodal Prompts: Uses multiple types of data inputs to enrich AI interactions.
18.	Ethical Prompting: Ensures prompts adhere to ethical guidelines and cultural sensitivities.
19.	Hierarchical Prompting: Structures prompts from general to specific for layered information.
20.	Guided Imagery Prompts: Guides AI to generate detailed visual content or descriptions.
21.	Recursive Prompts: Uses output from one prompt as input for the next to refine responses.
22.	Adaptive Learning Prompts: Adjusts prompt complexity based on AI’s performance or user’s progress.
23.	Cross-Modal Prompts: Transforms inputs across different modalities (e.g., text to audio).
These summaries are designed to help you easily remember the essence of each prompting framework.

//todo: link assorted knowledge banks. 


dev:
https://www.npmjs.com/package/keypress


//access clipboard//done
//access api//done
//format query in optimal programmable format//done
//get tags for agent and memory//done
//use tags to fetch desired set//done
//setup special flag handler for command flags with no associated memory.//done
 I thing I have a bug to sort yet though, it exposes itself once in a while and I think it's here. 
//todo: notification instead of sound effects//done
//todo: finish saving objects to memory//done
//fast switch instruction sets //done
//todo: group chain interacting so you can batch like |||@summary,@writer|//done, way cooler than that.

//todo: openAI client, probably migrate a ton of logic out of textengine and into koboldinterface.js to make them interchangeable. //half bugged SSL and I havent found the right answer to inform me what I am missing. 

//todo: keyboard binding to activate ai on last clip without prompt. //maybe paid, I don't want to make it too easy to do all the linkedin tests, and a ready line to copy is the same.//done, |||on| //multiplatform esc key reading is tricker than I expected. 

//todo: /api/extra/abort on esc and return //waiting on backends coalesing and a good doc for openAI compatibles. also reading esc key is tricker than I expected, gotta find the right thing.

//todo: implement insertion after cursor and response streaming. //this would be easy in windows if I wasnt hung up on multiplatform support. 

//todo text to speech agent that can interact with the clipboard contents. //waiting on upstream that runs on my hardware without dinkin around or enough generosity to set up a closet server or at least new hard drives, I'm too full to experiment with a new OS. //kobold now supports whisper and SD. I gotta find enough peace to rewrite this entire app in c# to support audio and images.

//decline: use case? I guess return tokens like|||tokens| so you can see if it will fit... ok. undecline: todo: /api/extra/generate/check  //return in progress, useful for vlarge gens on slow mode
//todo: /api/extra/tokencount //should run against entered data and updates should be shown after setting mem or agent and on final send. //I'm gonna wait and do this after I figure out more completion backends and make it work for oogabooga and others.


//todo: implement some kind of update check and notification.//half, update bat.

//pass, just close CC it launches in one second//implement |||no| //uh oh, better comment needed. I should learn from this someday. Waaait, it's coming back to me. |||no| will disable parsing on the next run for transporting instructions, though its much easier to just error it off like "||| move this without invoking||| ||| " recommend extra at the end.
//this needs reworking. its setting off that write bug too.

//todo: savesettings and getsettings. overwrite settings like |||settings,write| to paste ' |||settings,save| `{ the settings serialized json }` ' which can be edited in place and copied to save the settings. //partial, agent save is pretty ready to pass in the right stuff, I just need to do the bits to make it go.

//todo: write agents or custom settings to file. //partial, agents, no settings writing yet.

//really waffling, its simply good like >user: //todo: per character rolling memory to allow more natural exchanges and enable rp.//decline for now. I should do a proper conversation builder.

//todo: settings bulk in and out //partial, prompt format switching is in, needs instructions switching to support more completion backends. 


//CC should not make outbound requests other than openAI, security is important. I'm thining about a branch without openAI just for data safety but until someone asks I won't split main. 

//todo: build agent portal with easy to copy and use workflow. 
//todo: mystery agent of the day. vulnerability: the description is visible in the kobold terminal
//does anyone really want this?

todo: a server for a mystery agent to play twenty questions against. If you guess the character you get points for the premium prompt store. Monthly tokens on a subscription, no need for phoning out, just copy from the page. Profit sharing intent, but core first.

//todo: Implement FunkyTown, you kids will never guess what this does. 

