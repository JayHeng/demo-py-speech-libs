# demoPySpeechLibs
Demonstrate speech related python libraries (standard/third-party)

<table><tbody>
    <tr>
        <th style="width: 100px;">Library</th>
        <th style="width: 350px;">Description</th>
        <th style="width: 50px;">Stars</th>
        <th style="width: 80px;">demo status</th>
    </tr>
    <tr>
        <td colspan="4" align="center">Standard</td>
    </tr>
    <tr>
        <td><a href="https://docs.python.org/2/library/wave.html">wave</a></td>
        <td>读写.wav格式音频文件，设置基本音频参数（comptype, framerate, nchannels, frames, sampwidth）</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://docs.python.org/2/library/sndhdr.html">sndhdr</a></td>
        <td>获取声音文件(.aiff/.au/.voc/.wav/.8svx/.sb/...)的基本音频参数（type, sampling_rate, channels, frames, bits_per_sample）</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://docs.python.org/2/library/audioop.html">audioop</a></td>
        <td>提供对音频文件（线性PCM/A律/u律/ADPCM...）的丰富操作（avg、max、格式之间互转等）</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://docs.python.org/2/library/ossaudiodev.html">ossaudiodev</a></td>
        <td>访问（读写）兼容<a href="http://www.opensound.com/pguide/oss.pdf">Open Sound System</a>标准的音频文件（A律/u律/ADPCM...）</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://docs.python.org/2/library/sunau.html">sunau</a></td>
        <td>读写Sun AU格式音频文件，设置基本音频参数（comptype, framerate, nchannels, frames, sampwidth）</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://docs.python.org/2/library/winsound.html">winsound</a></td>
        <td>提供Windows平台的音频播放接口（PlaySound()、MessageBeep()）</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td colspan="4" align="center">third-party</td>
    </tr>
    <tr>
        <td><a href="http://people.csail.mit.edu/hubert/pyaudio/">PyAudio</a></td>
        <td>录制和播放.wav格式音频，设置基本音频参数（comptype, framerate, nchannels, frames, sampwidth） -- 源自<a href="http://www.portaudio.com/">PortAudio</a></td>
        <td><a href="https://github.com/jleb/pyaudio/stargazers"><img src="https://img.shields.io/github/stars/jleb/pyaudio.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="http://pydub.com/">Pydub</a></td>
        <td>音频文件的丰富操作</td>
        <td><a href="https://github.com/jiaaro/pydub/stargazers"><img src="https://img.shields.io/github/stars/jiaaro/pydub.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></td>
        <td>支持多引擎（CMU Sphinx/Google Speech Recognition/MS Bing Voice Recognition/IBM Speech to Text/...）的语音识别，如将麦克风语音输入/音频文件(.wav/.aiff/.flac/...)识别为文字等</td>
        <td><a href="https://github.com/Uberi/speech_recognition/stargazers"><img src="https://img.shields.io/github/stars/Uberi/speech_recognition.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/bambocher/pocketsphinx-python">PocketSphinx-python</a></td>
        <td>将麦克风语音输入/音频文件识别为文字，关键词识别等 -- 源自<a href="https://github.com/cmusphinx/pocketsphinx">CMU Sphinx之PocketSphinx</a></td>
        <td><a href="https://github.com/bambocher/pocketsphinx-python/stargazers"><img src="https://img.shields.io/github/stars/bambocher/pocketsphinx-python.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="">pyTTS</a></td>
        <td>将文字转换成语音在线播放，于2005年停更 -- 源自<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/ee125663(v=vs.85)">Microsoft Speech API (SAPI5)</a></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/RapidWareTech/pyttsx">pyttsx</a></td>
        <td>pyTTS项目的延续，主要支持python 2.x，于2012年停更</td>
        <td><a href="https://github.com/RapidWareTech/pyttsx/stargazers"><img src="https://img.shields.io/github/stars/RapidWareTech/pyttsx.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/nateshmbhat/pyttsx3">pyttsx3</a></td>
        <td>将pyttsx项目升级支持python 3.x，同时也兼容python 2.x</td>
        <td><a href="https://github.com/nateshmbhat/pyttsx3/stargazers"><img src="https://img.shields.io/github/stars/nateshmbhat/pyttsx3.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="http://librosa.github.io/librosa/">LibROSA</a></td>
        <td></td>
        <td><a href="https://github.com/librosa/librosa/stargazers"><img src="https://img.shields.io/github/stars/librosa/librosa.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></td>
        <td></td>
        <td><a href="https://github.com/jameslyons/python_speech_features/stargazers"><img src="https://img.shields.io/github/stars/jameslyons/python_speech_features.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/worldveil/dejavu">dejavu</a></td>
        <td>音频指纹识别</td>
        <td><a href="https://github.com/worldveil/dejavu/stargazers"><img src="https://img.shields.io/github/stars/worldveil/dejavu.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/danilobellini/audiolazy">AudioLazy</a></td>
        <td>音频DSP处理</td>
        <td><a href="https://github.com/danilobellini/audiolazy/stargazers"><img src="https://img.shields.io/github/stars/danilobellini/audiolazy.svg"></a></td>
        <td></td>
    </tr>
    <tr>
        <td><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></td>
        <td>音频特征提取</td>
        <td><a href="https://github.com/tyiannak/pyAudioAnalysis/stargazers"><img src="https://img.shields.io/github/stars/tyiannak/pyAudioAnalysis.svg"></a></td>
        <td></td>
    </tr>
</table>

### 参考文档
> 1. [哪些 Python 库让你相见恨晚？](https://www.zhihu.com/question/24590883)
> 2. [Python资源大全中文版](https://github.com/jobbole/awesome-python-cn)
> 3. [awesome-python-scientific-audio
](https://github.com/faroit/awesome-python-scientific-audio)

