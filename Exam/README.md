# NLP Mid-term Exam

This repository contains the mid-term exam for NLP.

The questions and the data will be made available to you at 10:00 on Thu 23 Oct 2025 via the Jupyter Notebook named "exam.ipynb" and the data used in the exam named `test_predictions.csv`, respectively.

All the logistical details, rules, and guidelines pertaining to the exam are stated below.

Additionally, to iron out critical logistical aspects, such as execution environment setup, sharing of high-level rules, and submission process of your solved exam, we would like each of you to participate in a dry run of the exam. Please see the [dry-run instructions](#Dry-run-Instructions) section at the bottom of this document for details.

## Conda Environment
We have prepared a conda environment, named `exam`, with all the Python packages that you might need for the exam. You can install it with the following command:   
`conda env create -f env.yml`

Once installed, to activate the environment, please use `conda activate exam`. To use it in Jupyter, please initiate Jupyter from a terminal with `exam` as the active conda environment. You can add it to jupyter enviroment by `python -m ipykernel install --user --name=exam --display-name "nlp25-exam"`

You are also of course welcome to install any additional package to the aforementioned conda environment.   


## Timeline
**Exam date:** Thu 23 Oct 2025   
**Exam start:** 10:00 (CET/UTC+2h)   
**Exam end:** 13:00 (CET/UTC+2h)   
**Later submissions will not be accepted!**

## High-level Guidelines and Rules

1. You should be connected to the eduroam network for the duration of the exam and are not allowed to use VPNs or Hotspots. Electronic devices other than your computer — including iPads, tablets, mobile phones, etc. — are strictly prohibited throughout the entire exam.
2. You can use all the online resources you want, except for communication tools (emails, web chats, forums, phone, etc.). And we will be monitoring the network for any unusual activity. For the MCQ part, you are only allowed access to your lecture slides and your self-crafted notes prepared before the exam, but no other resources. Notes may be kept either on paper or on your laptop, but not on any other electronic devices. For the coding part, you can use all the online resources you want, except for communication tools (emails, web chats, forums, phone, etc.). You may use AI-based chat assistants (e.g., ChatGPT, Gemini, Claude, etc.); however, you cannot prompt them to directly give you a solution. You must cite any conversations you have had with GenAI tools under the corresponding question. We recommend that you share a link to your chat with the chat model. If sharing a link is not possible, you may paste the content of your conversation instead. For details, see [this BrightSpace Announcement](https://brightspace.au.dk/d2l/le/news/184554/125780/view?ou=184554).
3. You may not ask AI models for the full solution or the set of steps to solve a question. If you know the steps, then you are allowed to ask how to solve a specific step. However, if the question specifies those steps, then you cannot ask the model how to solve them.
4. Announcements during the exam, if any, will be made under the *"Announcements"* section of [this Google document](https://docs.google.com/document/d/1kxqWgRJzLxqCzMKI5LK9_rt8modDNURijXmXJv_xOhw/edit?usp=sharing). **It is your responsibility to check the announcements regularly to ensure you do not miss any updates.**  
5. You have to open "exam.ipynb" in Jupyter, edit it, and submit a fully run and evaluated notebook with your solutions.
6. You have *3 hours* to solve the exam and upload your solved iPython (.ipynb) notebook.
7. We have prepared a conda environment with all the necessary Python packages. If not done already, you can install it with the following command:   `conda env create -f env.yml`
8. You are allowed to use any built-in Python library that comes with Anaconda.
9. You are allowed to use any IDE or online coding platform. However, please make sure to **disable any automatic code completion features** as well as **any AI agent modes within the IDE**. If you want to use AI tools, you must access them **through the browser**. For details, see [this BrightSpace Announcement](https://brightspace.au.dk/d2l/le/news/184554/125780/view?ou=184554). Asking Google or any other search engine is not allowed if an AI overview is displayed that can directly provide you with an answer. It is your responsibility to ensure that your searches do not include any AI-generated overviews.
10. There are two main parts: **MCQ** and **Coding**. The Coding part contains four tasks. Each main task, as well as each task within the Coding part, is **independent**, and you may attempt them in any order.
11.  In the coding part, there is a part about a brief introduction and loading the dataset. Make sure to go through and run this part first. For the remaining three tasks, you may complete them in any order you prefer — just make sure to manage your time wisely.
12.  For questions containing the **/Discuss:/** prefix, answer not with code, but with a textual explanation (in markdown).
13.  Don't forget to add a textual description of your thought process, the assumptions you made, and your results!
14.  Please write all your comments in English, and use meaningful variable names in your code.
15. We suggest that you not obsess over small details in the beginning, and try to complete as many tasks as possible during the first 2 hours. Then, go back to the obtained results, write meaningful comments, and debug your code if you have found any glaring mistakes.
16. Fully read the instructions for each question before starting to solve it to avoid misunderstandings, and remember to save your notebook often!
17. We will **not run your notebook for you**! Rather, we will grade it as is, which means that only the results contained in your evaluated code cells will be considered, and we will not see the results in unevaluated code cells. Thus, be sure to hand in a **fully run and evaluated notebook**.
18. Remember, this is not a homework assignment -- **no teamwork allowed!**

## Submission
* You will have until 13:00 (strict deadline) to turn in your submission. **Late submissions will not be accepted.**

* Overall, you need to submit your .ipynb file through WiseFlow. According to the system requirements, you must upload both a PDF file and the .ipynb file as attachments. We will evaluate the .ipynb file.  Where you (1) upload a PDF file and (2) your solved .ipynb notebook as the appendix/supplementary material.

* We will not evaluate the PDF file, but the system requires that you must upload a PDF file. Therefore, we recommend converting your .ipynb file to PDF and uploading that version, just in case of any unexpected .ipynb file corruption. This is not mandatory—the choice is up to you.
  
* It is your responsibility to ensure that your .ipynb file is complete and includes all code, outputs, and your discussions. We will not run your code, so please make sure that all results are fully rendered in your submission.

## Dry-run Instructions

Complete the following steps for a smooth exam experience on the day of the exam:
1. Carefully read and familiarize yourself with all the aforementioned rules and instructions.
2. Set up the `exam` [conda environment](#Conda-Environment).
3. Execute all the cells of `exam_dryrun.ipynb` in Jupyter with `exam` as the active conda environment. On successful execution, it should print **'Package import test successful!'** without throwing any errors.
