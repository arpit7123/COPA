# COPA

COPA.zip contains:

     a) copa_with_qs_and_ks.json file which contains a copa problem and automatically extracted knowledge sentences corresponding to the copa problems. It contains an array of objects where each object follows the template below.
     
```javascript
{
    "alt2_k_sents": [
      {
        "url": "",
        "text": ""
      },....
    ],
    "alternative2": "",
    "alternative1": "",
    "alt1_k_sents": [
      {
        "url": "",
        "text": ""
      },....
    ],
    "relation": "cause",
    "premise": "",
    "answer": "1",
    "queries_alt1": [
      "",....
    ],
    "queries_alt2": [
      "",....
    ],
    "id": "1"
  }
  ```

     b) copa_sents directory in which each file represents a copa sentence (premise + an alternative)
     c) copa_sents_qasrl directory in which each file represents the qasrl output of each file in copa_sents directory
     d) k_sents_qasrl* directories in which each file represents a knowledge sentence
     e) k_sents_qasrl*_out directories in which each file represents a knowledge sentence's qasrl output
