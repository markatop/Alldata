# Exploring-Skill-Transfer-of-Mandarin-based-Speech-Misunderstanding-on-Chinese-VPA-data
All the experimental data and results in the paper "Exploring Skill Transfer of Mandarin-based Speech Misunderstanding on Chinese VPA" are shown in this project, including the Chinese Mandarin test audio for speech recognition, transcription test results, Baidu DuSmart Speaker skill data, etc.
# Mandarin Test Audio
Composed of two folders (Mandarin Pronunciation and Mandarin Words), which contain 1,088 pronunciations and 13,863 words respectively, to test the speech recognition rate of Chinese VPA and the ability to understand the meaning of commonly used words. The following table shows their constituent information.
<table>
<thead>
  <tr>
    <td>Audio Set</td>
    <td>Composition</td>
    <td>Quantity</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="4">Mandarin Pronunciation</td>
    <td>Single Syllable</td>
    <td>21</td>
  </tr>
  <tr>
    <td>Two Syllables</td>
    <td>798</td>
  </tr>
  <tr>
    <td>Three Syllables</td>
    <td>214</td>
  </tr>
  <tr>
    <td>Overall-read Syllables</td>
    <td>55</td>
  </tr>
  <tr>
    <td rowspan="3">Mandarin Words</td>
    <td>Two-word Words</td>
    <td>13,371</td>
  </tr>
  <tr>
    <td>Three-word Words</td>
    <td>374</td>
  </tr>
  <tr>
    <td>Four-word Words</td>
    <td>118</td>
  </tr>
</tbody>
</table>

# DuerOS Transcription Results
We use DuerOS black box transcription service to test the speech recognition ability of Baidu VPA. We show all the transcription results of the two audio sets after testing, and each folder contains three files: transcriptional correct data, incorrect data, and unrecognized (no transcription results returned) data.

# Comparison

In order to find out whether the system misunderstandings in DuSmart Speaker also exist in other Chinese VPAs, we choose another three popular device "Xiaomi AI Speaker", "Alibaba TmallGenie" and "HUAWEI Celia" for comparative verification. The following table shows the recognition results, the number represents the percentage that make the same mistake as DuerOS.

<table>
<thead>
  <tr>
    <td colspan="2">Baidu DuSmart</td>
    <td>Xiaomi Speaker</td>
    <td>Alibaba TmallGenie</td>
    <td>HUAWEI Celia</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">Pronunciation</td>
    <td>Incorrect(31)</td>
    <td>87.10%(27)</td>
    <td>90.32%(28)</td>
    <td>83.87%(26)</td>
  </tr>
  <tr>
    <td>Unrecognized(27)</td>
    <td>77.78%(21)</td>
    <td>66.67%(18)</td>
    <td>81.48%(22)</td>
  </tr>
  <tr>
    <td rowspan="2">Words</td>
    <td>Incorrect(858)</td>
    <td>67.83%(582)</td>
    <td>66.20%(568)</td>
    <td>56.76%(487)</td>
  </tr>
  <tr>
    <td>Unrecognized(33)</td>
    <td>51.52%(17)</td>
    <td>3.03%(1)</td>
    <td>54.55%(18)</td>
  </tr>
  <tr>
    <td colspan="2">Overall Similarity</td>
    <td>68.18%</td>
    <td>64.59%</td>
    <td>58.27%</td>
  </tr>
</tbody>
</table>

# Baidu Skills
We crawl 2,746 skills in the current [Baidu skills market](https://dumall.baidu.com/skill), including skill name, developer type, developer name, sample sentences and skill description. [Accessed 02-2023]. After the completion of data cleansing, we carry out a similarity comparison of skill names.

# User Study
We recruit 300 volunteers with at least one Baidu VPA on [Credamo](https://www.credamo.com//#/) to fill in the questionnaires we designed. We submit the detailed content of the questionnaire and the results of 300 questionnaires that we have adopted. Respondents' information and data analysis can be viewed in our paper.
