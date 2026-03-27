Requirements:


\## Lista 1



* Readability  : the system have to check sentence length and its complexity
* Suggestion  : the system have to give suggestion on correction on weak part of the text
* Plot Coherence  : the system has to find the key facts of the text and check if there is coherence among it
* The system shall evaluate the readability of the text and provide a readability score by analyzing sentence length, word complexity, and text structure.
* The system shall detect sentence length problems by measuring the number of words in each sentence and identifying extremes.
* The system shall allow users to export the report by providing options in formats such as PDF, TXT, and DOCX.
* Character Interaction Map: A visual matrix showing which characters appear together and their distribution throughout the timeline.
* Sentiment/Tone Analysis: Tracking the emotional arc of scenes to ensure the "mood" aligns with the narrative intent.
* Count the occurrence of each word to detect and signal repetitions and overused vocabulary.
* The system should highlight paragraphs that could be improved, based on the previous analysis, and suggest improvements like vocabulary alternatives, dividing long phrases into shorter ones, formatting.



* Security: the user session have to be isolated of others session
* Language support: the system support text in many languages
* The system shall provide a simple and user friendly interface by allowing users to complete main actions (upload, analyze, export) in no more than 3 steps.
* The system shall ensure database security by storing data in an encrypted format and restricting access to authorized users only.
* Performance: The system must analyze a standard 100,000-word .docx or .txt manuscript and generate the final diagnostic report in under 360 seconds.
* Portability: The application must be fully containerized (e.g., using Docker) to allow seamless deployment and migration across major cloud providers (such as AWS or Google Cloud) without modifying the application source code.
* The system should allow users to share their work with other registered users.









\## Lista 2



* Repetition  : the system should check repetition words
* Layout of the text  : the system should control the organize of the text by checking the space between the lines and capitol letters and the start
* Comments  : the system should add commenting on the changed lines
* The system shall analyze the balance between dialogue and description by identifying dialogue segments and descriptive passages in the text.
* The system shall suggest synonyms by comparing words with a predefined dictionary or language database.
* Multi-Format Text Upload  : Support for various file types (.docx, .pdf, .txt) with preservation of chapter breaks.
* Pacing Heatmap  : An analysis of sentence and chapter lengths to identify "slow" or "rushed" sections of the story.
* Cliché \& Weak Verb Detection  : Highlighting passive voice, and tired metaphors that weaken the narrative.
* Spelling and grammar mistakes, according to the grammar and vocabulary of the selected language, in order to improve the objective correctness of the text.
* The system should provide a report including some metrics about the text uploaded, for example word and character counters, most used vocabulary, etc.



* Upload Limit: the dimension of the file should be at maximum 10 mb
* Native system: the system should work on all types of devices including hosted on web servers
* The system shall support scalability by handling texts up to 100,000 words without performance degradation.
* The system shall ensure high availability by maintaining at least 99% uptime per month.
* Usability: A first-time user must be able to successfully upload a manuscript and initiate the analysis report within 2 minutes of logging into the system, without referring to external documentation or help menus.
* The system should provide results in less than 5 seconds for texts up to 50000 words.
* The system should allow users to automatically translate the uploaded text into another language.



\## Lista 3

* Uploading  : the system should be able to allow the user to upload and edit narrative text files
* Summary of the text  : the system suggest to generate a summary of the whole text with clue points
* Comparison  : the system allow user with clear vision to compare the old and the new edited version
* The system shall analyze lexical variety by calculating the ratio of unique words to total words in the text.
* The system shall calculate a readability index by applying standard readability formulas to match the target audience level.
* The system shall generate a summary of the analysis by highlighting key findings before exporting the full report.
* Repetition \& Redundancy Tracker  : Identification of overused words, phrases, and unintended echoes within paragraphs.
* Lexical Variety Score  : Calculation of unique vocabulary usage to assess the richness and sophistication of the prose.
* Automated Summary Report  : Generation of a PDF dashboard summarizing key metrics, "red flag" warnings, and specific suggestions for improvement.
* Check how many chars belong to dialogs between superscripts and how many belong to descriptions.



* File format: the formats allowed are txt docx
* The system shall be accessible through standard web browsers by supporting browsers such as Chrome, Firefox, and Edge.
* The system shall ensure data security by encrypting user data using standard encryption protocols (e.g., HTTPS).
* The system shall support concurrent usage by allowing at least 100 users to use the system at the same time without performance issues.
* Security (Data Privacy): All uploaded manuscripts must be encrypted in transit using TLS 1.2 (or higher) and encrypted at rest using the AES-256 encryption standard to protect the author's intellectual property.
* The system should have a dynamic and animated UI.
* The system should provide a registration system, allowing users to login and signin.



\## Lista 4



* Dictionary  : the system allows the explanation of complicated words written by professional authors
* Text to voice including all language  : the system should allow to transform the text into voice in all language just by pressing a bottom showed up the text
* The system shall analyze the text and detect repeated words and expressions by counting their frequency and identifying those above a defined threshold.
* The system shall provide suggestions to improve narrative quality by analyzing detected issues and generating relevant recommendations.
* The system shall detect grammar issues by using predefined grammar rules and language processing techniques.
* The system shall allow users to upload documents by supporting file formats such as PDF, TXT and DOCX.
* Dialogue-to-Description Ratio  : A visual breakdown of "showing vs. telling" by measuring the balance of spoken text versus prose.
* Readability Indexing  : Automated scoring to ensure the text matches the intended target audience's level.
* The system should allow for user text upload, both as a "copy and paste" and .txt files (in case of big texts).
* After the upload the system should check the following functionalities.



* Summary Format: the summary generated should be at maximum 10 lines
* The system shall generate the analysis report within 5 seconds for texts up to 50,000 words.
* The system shall ensure reliability by completing at least 95% of analysis requests without errors.
* The system shall ensure compatibility by supporting at least 3 file formats (e.g., PDF, DOCX, TXT) for input and output.
* Scalability: The system must support up to 500 concurrent text analysis requests while continuing to meet the processing time defined in the Performance requirement.
* Extensibility: The system must utilize a modular architecture (e.g., via APIs or microservices) ensuring that new analytical metrics or language rulesets can be deployed independently without requiring recompilation of the core text-parsing engine.



