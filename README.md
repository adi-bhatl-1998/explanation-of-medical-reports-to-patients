Many of us in our day to day life find it hard to understand the medical reports issued to us .
The aim of the project will be to create a model that can explain the medical reports generated by 
the doctors to a patient with as much ease as possible

The plan is to test out multiple llm which are trained on medical data , create an agent type of interface to communicate with the patients query ,
although I would like to be able to input the report image itself to the llm , the first functionality will be to input the patient text query  and receive the output from the llm . I beleive this kind of system can be deloyed for each doctor's where in it captures the doctors style of treatment , like personalized doctor report explanation or report explanation based on each kind of tests whichever is more suitable . 
will deploy it in the form of simple user interface that takes the input , and returns the output.

functionality :
1 the first functionality will be to input the patient text query  and receive the output from the llm
2 able to input the report image itself to the llm
3 Language translation just like how its enabled in Kissan gpt
4 research about the real word deployement problems that can effect the adoption of such a model 

Models under consideration:
https://huggingface.co/medicalai/ClinicalBERT/discussions
https://huggingface.co/docs/hub/repositories-pull-requests-discussions
https://huggingface.co/ThisIs-Developer/Llama-2-GGML-Medical-Chatbot?text=Hey+my+name+is+Mariama%21+How+are+you%3F
https://huggingface.co/medical-ner-proj/bert-medical-ner-proj
https://huggingface.co/Abdulkader/autotrain-medical-reports-summarizer-2484176581
https://huggingface.co/IndianaUniversityDatasetsModels/MIMIC-Medical-Report-Generator
https://huggingface.co/foundationmodels/MIMIC-medical-report/tree/main
Medplam 1 

dataset :
https://huggingface.co/datasets/IndianaUniversityDatasetsModels/Medical_reports_Splits
https://huggingface.co/datasets/IndianaUniversityDatasetsModels/MIMIC-medical-report
https://huggingface.co/datasets/IndianaUniversityDatasetsModels/Indiana_University_Medical_reports_original

further dataset searches are on going .

