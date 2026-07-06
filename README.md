# Greek KOK Datasets & Assets

##repo structure
```text
├── 📄 questions_car.json     
├── 📄 questions_moto.json    
├── 📄 questions_truck.json   
├── 📄 questions_bus.json     
└── 📁 assets/
    └── 📁 images/            
        ├── 📁 car/
        ├── 📁 moto/
        ├── 📁 truck/
        └── 📁 bus/
```
##json structure (with example)
```json
{
  "id": "q_001",
  "question": "Ποια είναι η σημασία του σήματος αυτού:",
  "correct_answer": "Τέλος αποκλειστικής διελεύσεως λεωφορείων ή τρόλεϊ.",
  "distractors": [
    "Αποκλειστική διέλευση λεωφορείων ή τρόλεϊ.",
    "Απαγορεύεται η διέλευση λεωφορείων ή τρόλεϊ."
  ],
  "image_path": "assets/images/bus/q_001.jpg"
}
```
**Data Accuracy:** This dataset is derived from automated web scraping. Consequently, it may contain typographical or syntax errors, incorrect answers, duplicate questions, or omissions.
