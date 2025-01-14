## How to cite 
If you use the *QRCD* dataset in your research, please cite both of the following references:
* Rana Malhas and Tamer Elsayed. Official Repository of Qur’an QA Shared Task. https://gitlab.com/bigirqu/quranqa. February 2022. 
* Rana Malhas and Tamer Elsayed. AyaTEC: Building a Reusable Verse-Based Test Collection for Arabic Question Answering on the Holy Qur’an. ACM Transactions on Asian and Low-Resource Language Information Processing (TALLIP), 19(6), pp.1-21, 2020.

## Format Structure of the QRCD Dataset

```
{
  "pq_id": "38:41-44_105",
  "passage": "واذكر عبدنا أيوب إذ نادى ربه أني مسني الشيطان بنصب وعذاب. اركض برجلك هذا مغتسل بارد وشراب. ووهبنا له أهله ومثلهم معهم رحمة منا وذكرى لأولي الألباب. وخذ بيدك ضغثا فاضرب به ولا تحنث إنا وجدناه صابرا نعم العبد إنه أواب.",
  "surah": 38,
  "verses": "41-44",
  "question": "من هو النبي المعروف بالصبر؟",
  "answers": [
    {
      "text": "أيوب",
      "start_char": 12
    }
  ]
}
{
  "pq_id": "74:32-48_330",
  "passage": "كلا والقمر. والليل إذ أدبر. والصبح إذا أسفر. إنها لإحدى الكبر. نذيرا للبشر. لمن شاء منكم أن يتقدم أو يتأخر. كل نفس بما كسبت رهينة. إلا أصحاب اليمين. في جنات يتساءلون. عن المجرمين. ما سلككم في سقر. قالوا لم نك من المصلين. ولم نك نطعم المسكين. وكنا نخوض مع الخائضين. وكنا نكذب بيوم الدين. حتى أتانا اليقين. فما تنفعهم شفاعة الشافعين.",
  "surah": 74,
  "verses": "32-48",
  "question": "ما هي الدلائل التي تشير بأن الانسان مخير؟",
  "answers": [
    {
      "text": "لمن شاء منكم أن يتقدم أو يتأخر",
      "start_char": 76
    },
    {
      "text": "كل نفس بما كسبت رهينة",
      "start_char": 108
    } 
  ]
}
```
