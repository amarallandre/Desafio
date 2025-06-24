# 🔊 Text-to-Speech - Azure

## 🎯 Objetivo
Transformar o trecho da música em fala com **voz neural** do Azure.

## 📝 Texto utilizado
```
Imagine all the people living life in peace.
```

## 💡 SSML usado
```xml
<speak version="1.0" xml:lang="en-US">
  <voice name="en-US-JennyNeural">
    Imagine <break time="200ms"/> all the people <break time="300ms"/> living life in peace.
  </voice>
</speak>
```

## 🎧 Voz escolhida
- `en-US-JennyNeural` (voz feminina natural)

## 📄 Arquivos gerados
- `imagine_tts.mp3`
- `exemplo_ssml.xml`

## 🤖 Resultado
Voz natural, com pausas bem definidas, entonação emocional e boa compreensão.