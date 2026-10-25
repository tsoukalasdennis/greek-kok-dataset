# Greek KOK Datasets & Assets

### **Repository structure**
```text
├── 📄 questions_car.json     
├── 📄 questions_moto.json    
├── 📄 questions_truck.json   
├── 📄 questions_bus.json     
└── 📁 assets/
    └── 📁 images/            
        ├── 📁 car/
        ├── 📁 truck/
        └── 📁 bus/
```
### **JSON structure - with example**
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
A small demo is available on GitHub Pages to preview the dataset: [Greek KOK dataset demo](https://tsoukalasdennis.github.io/greek-kok-dataset-demo/)

### **Data Accuracy** 
This dataset was collected through automated web scraping and reviewed against official KOK PDFs. Despite this review, it may still contain typographical or formatting errors, incorrect answers, duplicate questions, or omissions. It is not an official source; please verify important information against current official materials.
