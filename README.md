# Spectrograms of Myanmar Speech

Spectrograms of Myanmar consonant and vowel audios that I recorded at University of Computer Studies Banmaw (UC Banmaw), Banmaw, Kachin State, Myanmar, November 2018. For the 22 consonants and 12 vowels, I prepared audio files by recording 45 female and 37 male speakers, including native speakers as well as other national ethnic races such as Kachin, Shan, and Rakhine, using a MacBook Air built-in microphone. The spectrograms of the audio files were extracted using the Sound eXchange (SoX, Swiss
Army knife of sound processing programs) command line utility. I used these spectrograms for the Transfer Learning experiments.  

Please note recording was done inside a hall and containing some noises such as mouse click sound. 

# မြန်မာလို အကျဉ်းချုံးရှင်းပြရရင်  
ဒီ repository မှာ တင်ပေးထားတဲ့ ဖိုင်တွေက၊ မြန်မာ ဗျည်းနဲ့သရ အသံတွေကို [spectrogram](https://en.wikipedia.org/wiki/Spectrogram) ဂရဖ်အဖြစ်ပြောင်းပြီးတော့ Transfer Learning approach နဲ့ speech classification experiment တွေအတွက် သုံးခဲ့တဲ့ ဖိုင်တွေပါ။ Recording ကို လုပ်ခဲ့တာက ကွန်ပျူတာတက္ကသိုလ် ဗန်းမော်မှာပါ။ အဲဒါကြောင့် ရှမ်း၊ ကချင်၊ ဗမာ၊ ရခိုင်၊ ပလောင်၊ လားဟူ၊ ဂေါ်ရခါး စသည်ဖြင့် လူမျိုးလည်း စုံပါတယ်။ 2018 ခုနှစ် နိုဝင်ဘာလမှာ Deep Learning Summer School ရဲ့ နောက်ဆက်တွဲအဖြစ် တရက်ပိုယူပြီးတော့ Transfer Learning Workshop မှာ အခုတင်ပေးထားတဲ့ အထဲက spectrogram ဖိုင်တချို့ကို အသုံးပြူပြီးတော့ transfer learning experiment ဒီမိုလုပ်ပြခဲ့ပါတယ်။  

မဥဥခင် (Faculty of Advanced Science and Technology, [Kumamoto University](https://ewww.kumamoto-u.ac.jp/en/), Japan) ရဲ့ မဟာဘွဲ့သုတေသနရဲ့ တစိတ်တပိုင်းအဖြစ် အခုတင်ပေးထားတဲ့ spectrogram ဖိုင်အားလုံးကို အသုံးပြုခဲ့ပါတယ်။ စာတမ်းကိုလည်း တင်ပေးပါမယ်။ အသံဖိုင်တွေက ခန်းမကျယ်ကြီးထဲမှာ သွင်းထားတာက တကြောင်း၊ MacBook Air ရဲ့ built in mic ကို သုံးထားတာမို့ noise တစ်ချို့လည်း ပါပါတယ်။ သို့သော် ဖိုင်အရေအတွက်ကလည်း experiment တစ်ခုလုပ်ဖို့ အတွက်တော့ မနည်းပါဘူး။ မြန်မာ ဗျည်းနဲ့သရ အသံတွေရဲ့ spectrogram တွေကို စိတ်ပါဝင်စားသူတွေအတွက် လေ့လာနိုင်ဖို့ အတိုင်းအတာတစ်ခုအထိ အထောက်အကူဖြစ်ပါလိမ့်မယ်။  

# Files and Folders   

consonant/ (spectrograms of 22 classes of Myanmar consonant sounds, 4,395 jpg files)  
vowel/ (spectrograms of 12 classes of Myanmar vowel sounds, 1,345 jpg files)  
ot-data/ (spectrograms of Myanmar consonant and vowel sounds for open-test)  
ot-data/consonant/ (440 jpg files)  
ot-data/vowel/ (120 jpg files) 

wave/ (main folder of original 16Khz mono wave files)   
wave/consonant/ (4,395 wave files)  
wave/vowel/ (1,345 wave files)  
wave/ot-data/consonant/ (440 wav files)  
wave/ot-data/vowel/ (120 wav files)  

# Classes of Myanmar Consonant

| Class ID  | Consonant |
| --------- |---------- | 
| 1  | က |
| 2  | ခ |
| 3  | ဂ၊ ဃ |
| 4  | င |
| 5  | စ |
| 6  | ဆ |
| 7  | ဇ၊ ဈ |
| 8  | ည၊ ဉ |
| 9  | တ၊ ဋ |
| 10 | ဌ၊ ဎ  |
| 11 | ဍ၊ ဎ၊ ဒ၊ ဓ |
| 12 | ဏ၊ န|
| 13 | ပ |
| 14 | ဖ |
| 15 | ဗ၊ ဘ |
| 16 | မ |
| 17 | ယ၊ ရ |
| 18 | လ၊ ဠ|
| 19 | ဝ |
| 20 | သ |
| 21 | ဟ |
| 22 | အ |

# Classes of Myanmar Vowel

| Class ID  | Vowel |
| --------- |---------- |
| 1 | အာ |
| 2 | အိ |
| 3 | အီ |
| 4 | အု |
| 5 | အူ |
| 6 | အေ|
| 7 | အဲ |
| 8 | အော့|
| 9 | အော်|
| 10 | အံ |
| 11 | အား|
| 12 | အက်|

# Example Spectrograms of Myanmar Consonants

Class 1 (က)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/consonant/1/1_1/2018-11-12-13:44:08.16khz.mono.jpg" alt="Class-1" width="400x" height="256x" />
</p>

Class 2 (ခ)  

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/consonant/2/2_1/2018-11-12-14:16:00.16khz.mono.jpg" alt="Class-2" width="400x" height="256x" />
</p>

Class 3 (ဂ၊ ဃ)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/consonant/3/3_1/2018-11-12-14:45:35.16khz.mono.jpg" alt="Class-3" width="400x" height="256x" />
</p>

Class 4 (င)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/consonant/4/4_1/2018-11-12-15:04:37.16khz.mono.jpg" alt="Class-4" width="400x" height="256x" />
</p>

# Example Spectrograms of Myanmar Vowels

Class 1 (အာ)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/1/2018-11-13-19:54:57.16khz.mono.jpg" alt="Class-1" width="400x" height="256x" />
</p>

Class 2 (အိ)  

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/2/2_2/2018-11-14-00:28:27.16khz.mono.jpg" alt="Class-2" width="400x" height="256x" />
</p>

Class 3 (အီ)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/3/3_1/2018-11-13-19:56:53.16khz.mono.jpg" alt="Class-3" width="400x" height="256x" />
</p>

Class 4 (အု)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/4/4_1/2018-11-14-00:30:27.16khz.mono.jpg" alt="Class-4" width="400x" height="256x" />
</p>

Class 5 (အူ)  

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/5/5_1/2018-11-13-19:59:57.16khz.mono.jpg" alt="Class-5" width="400x" height="256x" />
</p>

Class 6 (အေ)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/6/6_1/2018-11-13-20:01:29.16khz.mono.jpg" alt="Class-6" width="400x" height="256x" />
</p>

Class 7 (အဲ)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/7/7_2/2018-11-14-00:34:51.16khz.mono.jpg" alt="Class-7" width="400x" height="256x" />
</p>

Class 8 (အော့)  

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/8/8_2/2018-11-14-00:36:14.16khz.mono.jpg" alt="Class-8" width="400x" height="256x" />
</p>

Class 9 (အော်)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/9/9_1/2018-11-13-20:34:36.16khz.mono.jpg" alt="Class-9" width="400x" height="256x" />
</p>

Class 10 (အံ)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/10/10_1/2018-11-14-00:21:06.16khz.mono.jpg" alt="Class-10" width="400x" height="256x" />
</p>

Class 11 (အား)  

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/11/11_1/2018-11-14-00:40:10.16khz.mono.jpg" alt="Class-11" width="400x" height="256x" />
</p>

Class 12 (အက်)

<p align="center">
<img src="https://github.com/ye-kyaw-thu/Spectrograms-of-Myanmar-Speech/blob/master/vowel/12/12_1/2018-11-13-20:23:53.16khz.mono.jpg" alt="Class-12" width="400x" height="256x" />
</p>

# Acknowledgement

Following students and teachers of [University of Computer Studies Banmaw](http://ucsbanmaw.moe.edu.mm/) contributed for Myanmar consonant and vowel sound recording !  

မသဇင်ကို၊ မဖော်မြန်းသင့်နူး၊ မယဉ်မာမြင့်၊ မထက်ထက်အောင်၊ မချောစု၊  
မ
