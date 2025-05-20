# BRSpeech DF
A Deep Fake Synthetic Speech Dataset for Portuguese Zero-Shot TTS

## About it


This work introduces the first publicly available dataset explicitly designed for audio deepfake detection in Brazilian Portuguese, addressing a significant gap in annotated resources for low-resource languages. By contributing high-quality synthetic and real speech data in a linguistically underrepresented context, this dataset supports the development of more robust, multilingual, and equitable detection systems in the broader field of speech forensics and security.

## Real speaker and transcription

<table>
  <tr>
    <td>
     Speaker 11247
      <audio controls>
        <source src="https://ia601900.us.archive.org/17/items/11247-10229-000009-0001-1/11247_10229_000009-0001%20%281%29.mp4" type="audio/mpeg">
      </audio>
    </td>
    <td>
     O rio sem horizonte, sem limite, como uma grande pasta cinzenta, ligava-se ao céu baixo e denso. O desenho apagara-se, a bruma mascarava os perfis das coisas, e o colorido surgia com a sombra numa sublime desforra. Por toda a parte, manchas esplêndidas se apagavam.
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
     Speaker 12114
      <audio controls>
        <source src="https://ia601900.us.archive.org/17/items/11247-10229-000009-0001-1/12114_10229_000018-0001.mp4" type="audio/mpeg">
      </audio>
    </td>
    <td>
     Enquanto outra música, outra dança, invadia o cenário. Era a valsa alemã, clara, larga, fluente como um rio. Na sala, os pares voavam no frenesi, e entre estes se foi a amiga de Maria. Fora havia mais luar, as sombras minguando se resumiam mais fixas.
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
     Speaker 12287
      <audio controls>
        <source src="https://ia601900.us.archive.org/17/items/11247-10229-000009-0001-1/12287_12742_000020-0001.mp4" type="audio/mpeg">
      </audio>
    </td>
    <td>
     O seu olhar recolhido e como concentrado em pensamentos muito fundos, o nariz de pura raça israelita, a boca descaída na sua eterna curva sarcástica, o beiço inferior muito recurvo e muito pendente, e a sua estranha pera de Mephistóferes.
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
     Speaker 12626
      <audio controls>
        <source src="https://ia601900.us.archive.org/17/items/11247-10229-000009-0001-1/12626_10229_000021-0001.mp4" type="audio/mpeg">
      </audio>
    </td>
    <td>
     Ele deitou-se de manso e pôs-se à espera de que a noite avançasse. Tornava-se-lhe o sangue impetuoso de desejos, e na mente devódica passavam perturbadoras miragens sensuais. Levantou-se sorrateiro e, apenas aluminado pela frouxa luz do alcaldeíro de azeite que estava na sala,
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
     Speaker 12670
      <audio controls>
        <source src="https://ia601900.us.archive.org/17/items/11247-10229-000009-0001-1/12670_13396_000029.mp4" type="audio/mpeg">
      </audio>
    </td>
    <td>
     Tudo passara, na dissolvência dos sonhos, na voragem dos anos. Ilusões patrióticas e entusiasmo pelos gozos instáveis tragaram-os o tempo impassivelmente.                                                              
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
     Speaker 13063
      <audio controls>
        <source src="https://ia601900.us.archive.org/17/items/11247-10229-000009-0001-1/13063_13511_000048-0001.mp4" type="audio/mpeg">
      </audio>
    </td>
    <td>
     Via naquele fato esfarrapado de escovado a luta de uma alma que arcava com a miséria, de um homem que aspirava à decência e que prosseguia temeroso, como conhecendo que a vestimenta o degradava.
    </td>
  </tr>
</table>


## Comparison of models
### Male Speaker ID 12287

<table>
  <tr>
    <td>
      <audio controls>
        <source src="https://ia800408.us.archive.org/14/items/12287-real-1/12287_real%20%281%29.mp4" type="audio/mpeg">
      </audio>
      <p>Ground Truth</p>
    </td>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/14/items/12287-yourtts/12287_f5tts.ia.mp4" type="audio/mpeg">
      </audio>
      <p>F5TTS</p>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="https://ia800408.us.archive.org/14/items/12287-real-1/12287_xtts%20%281%29.mp4" type="audio/mpeg">
      </audio>
      <p>XTTS</p>
    </td>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/14/items/12287-yourtts/12287_fish.ia.mp4" type="audio/mpeg">
      </audio>
      <p>Fish-Speech</p>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="https://ia800709.us.archive.org/14/items/12287-yourtts/12287_toucan.ia.mp4" type="audio/mpeg">
      </audio>
      <p>ToucanTTS</p>
    </td>
    <td>
      <audio controls>
        <source src="https://ia800709.us.archive.org/14/items/12287-yourtts/12287_yourtts.ia.mp4" type="audio/mpeg">
      </audio>
      <p>YourTTS</p>
    </td>
  </tr>
</table>

### Female Speaker ID 7925

<table>
  <tr>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/3/items/7925-yourtts/7925_real.mp4" type="audio/mpeg">
      </audio>
      <p>Ground Truth</p>
    </td>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/3/items/7925-yourtts/7925_f5tts.mp4" type="audio/mpeg">
      </audio>
      <p>F5TTS</p>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/3/items/7925-yourtts/7925_xtts.mp4" type="audio/mpeg">
      </audio>
      <p>XTTS</p>
    </td>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/3/items/7925-yourtts/7925_fish.mp4" type="audio/mpeg">
      </audio>
      <p>Fish-Speech</p>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/3/items/7925-yourtts/7925_toucan.mp4" type="audio/mpeg">
      </audio>
      <p>ToucanTTS</p>
    </td>
    <td>
      <audio controls>
        <source src="https://ia600709.us.archive.org/3/items/7925-yourtts/7925_yourtts.mp4" type="audio/mpeg">
      </audio>
      <p>YourTTS</p>
    </td>
  </tr>
</table>
