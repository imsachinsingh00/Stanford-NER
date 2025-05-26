# Stanford Named Entity Recognition (NER)

This project demonstrates the use of the Stanford NER tool for extracting named entities from text files. Named Entity Recognition (NER) identifies proper names such as people, organizations, and locations in text.

## 📁 Project Structure

- `Standford_NER.ipynb`: Jupyter notebook showcasing how to use the Stanford NER model.
- `demofile2.txt` and `demofile2 (1).txt`: Sample input text files for entity recognition.

## 🚀 How to Run

1. Clone this repository or download the ZIP.
2. Ensure Java is installed on your system.
3. Download the Stanford NER models from the [official website](https://nlp.stanford.edu/software/CRF-NER.html).
4. Update the path to the NER model JAR and classifier in the notebook.
5. Run `Standford_NER.ipynb` to test the model on example text.

## 🧾 Requirements

- Python 3.x
- Jupyter Notebook
- Java (required by Stanford NER)

## 📝 Example

Sample text input:
```
Barack Obama was born in Hawaii. He was elected president in 2008.
```

Output (Entities identified):
- Person: Barack Obama
- Location: Hawaii
- Date: 2008

## 📌 Notes

Make sure to set the correct path to `stanford-ner.jar` and the classifier model in the notebook.

## 📄 License

MIT License.
