# Automated Terminal

This is a automated terminal which takes a voice commands from user and perform the task.

here is the project link : https://youtu.be/q2ZVndN1yxo

## Required packages

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install pyaudio
pip install SpeechRecognition
pip install gTTS
pip install subprocess
pip install playsound
pip install webbrowser
```

# Voice command
## 0) Choose commands
```bash 
1) terminal
2) play music
3) search web
4) find location
```
![image](https://user-images.githubusercontent.com/97884409/152349675-ebc24518-266c-4978-b2c7-de5d06c9e275.png)

## 1) For Terminal
```bash
1) 'change directory to <directoryName>'
2) 'go back' <-- it is used to one step back to the directory 
3) 'create a directory <dirname>',
4) 'create a file <filename>',
5) 'change permission for directory <dirname>'
6) 'change permission for file <filename>'
7) 'show list directory'
8) 'show me free space',df
9) 'show me use space' ,du commands
10) 'install Python module <moduleName>'
11) 'What is my ip'
12) 'rout <(www.google.com)>'
13) 'scan <(www.facebook.com)>'
14) 'remove file <filename>'
15) 'remove directory <directoryname>'
16) 'install package <packagename>'
17) 'update me'
18) 'upgrade me'
19) 'what is date today'
20) 'show directory', --> this is a "ls " commands

```
![image](https://user-images.githubusercontent.com/71899603/152358944-e75940a3-1e5a-4d73-80b6-83fc064549d4.png)
![image](https://user-images.githubusercontent.com/71899603/152358980-20686c99-dd3e-49e5-a857-33acb59758aa.png)
![image](https://user-images.githubusercontent.com/71899603/152359007-ae16c152-359d-438e-b828-65caec1edc52.png)

## 2) Play Music
```bash
Newton = 'speak the song that you like most...'
User = '...'
```
![image](https://user-images.githubusercontent.com/97884409/152358282-432908ee-cd13-4485-868f-564c1b93da88.png)
![image](https://user-images.githubusercontent.com/97884409/152358291-af58cf44-af10-4982-9c11-e1fb2e980303.png)
## 3) Web Searching
```bash
Newton = 'what do you want to search for...'
User = '...'
```
![image](https://user-images.githubusercontent.com/97884409/152360220-9171c187-5314-46ff-8dc7-3e57050679bd.png)
![image](https://user-images.githubusercontent.com/97884409/152360048-47e888a4-296f-4a67-b7c4-221da0aa57f7.png)

## 4) find location
```bash
Newton = 'Which location do you want to search...'
User = '...'
```
![image](https://user-images.githubusercontent.com/71916090/152360791-0576ed35-a7d2-4756-a3a4-9f110ff73faa.png)
![image](https://user-images.githubusercontent.com/71916090/152360835-4bc95992-478e-4a11-a1ce-96dd573c4efe.png)


  
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
