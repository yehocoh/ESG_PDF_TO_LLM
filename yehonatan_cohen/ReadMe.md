
Project Description:

This project involves extracting text from PDF files and classifying sentences within Environmental, Social, and Governance (ESG) documents. The process and results are outlined below:

1. Text Extraction:
   - I created an initial code notebook where I implemented the extraction of text from PDF files, which is attached for reference.

2. Sentence Classification:
   - Several additional notebooks are attached that detail the steps taken to classify the sentences in the ESG documents.

3. Model Performance and Validation:
   - Using the `re` (regular expressions) library, the highest validation accuracy achieved was 0.39. This validation was obtained via a request from GPT-4.
   - Due to constraints, the GPT-4 model was applied to only the first 500 documents.

4. Alternative Methods Explored:
   - I have included samples illustrating the usage of various alternative methods, with relevant observations:
     1. OpenAI API via LangChain: The accuracy might have been higher, but this method was not included in the final validation due to payment limitations.
     2. Alpaca Llama Model: The experiment with this model yielded only one classification result; hence, it was deemed unsuitable for further use.
     3. Hugging Face (HF) Models via LangChain:** Both validation results were inferior to the `re` library, and the execution time was considerably prolonged, despite attempts to optimize it with parallel processing.
