# Fake News Detection for German Fake News
Our project for the course "Transformer-based Natural Language Processing"

Used Data Set: 
  Mainly FANG-Covid* and some own scrapped Fake News from Correctiv Factchecking and GermanFakeNC**
  We added articles from Bild Zeitung, Volksverpetzer and news in comprehensible language to class True to archive more diversity and increase difficulty. Other souces in this class are mostly trust-worphy newspapers as Süddeutsche Zeitung or Zeit.

For Fake News Detection we are comparing seven models:
1. Baseline BERT Model
2. Feature only Model
3. Fusion Models:
  3.1. CLS BERT Embedding concat Feature Embedding
  3.2. Last 4 hidden layers of BERT Embedding concat Feature Embedding
  3.3. CLS BERT attention Feature Embedding
  3.4. Last 4 hidden layers of BERT BERT Embedding attention Feature Embedding
  3.5. CLS Embedding of last 4 hidden layers concat Feature Embedding concat Text Embedding
  
Further Experiments
- Statistical Analysis of featues in the feature model
- SHAP Analysis of most important featues in the feature model
- Drill-down analysis for missclassied samples in different souces















<sup><sub> * FANG-Covid
J. Mattern, Y. Qiao, E. Kerz, D. Wiechmann, and M. Strohmaier, “Fang-covid: A new large-
scale benchmark dataset for fake news detection in german,” in Proceedings of the Fourth
Workshop on Fact Extraction and VERification (FEVER), 2021, pp. 78–91.
**. Vogel and P. Jiang, “Fake news detection with the new german dataset "germanfakenc",”
in Digital Libraries for Open Knowledge - 23rd International Conference on Theory
and Practice of Digital Libraries, TPDL 2019, Oslo, Norway, September 9-12, 2019,
Proceedings, 2019, pp. 288–295. [Online]. Available: https://doi.org/10.1007/978-3-030-
30760-8_25
</sub></sup>
