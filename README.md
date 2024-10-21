# An-AI-Chatbot-Fine-Tuned-for-Medical-Queries
Final Project of 11785 deep learning CMU

conclusion

1. Professional areas need more man-machine collaboration
2. The importance of experts evaluation for medical Chatbots
3. Compare with RAG methods, in the future


# abstract

This paper details the baseline model selection, fine-tuning process,
evaluation methods, and the implications of deploying more accurate
LLMs in healthcare settings. As large language models (LLMs)
are increasingly employed to address diverse problems, including
medical queries, concerns about their reliability have surfaced. A
recent study by Long Island University highlighted that LLMs often
perform poorly in medical contexts, potentially leading to harmful
misguidance for users. To address this, our research focuses on fine-
tuning the Llama 2 7B, a transformer-based, decoder-only model,
using transcripts from  patient-doctor interactions. Our objective
was to enhance the model’s accuracy and precision in responding
to medical queries. We fine-tuned the model using a supervised
approach, emphasizing domain-specific nuances captured in the
training data. In the best scenario, model result should be reviewed
and evaluated by real medical experts. Due to resource constraint,
the performance of the fine-tuned model was evaluated using text
similarity metrics. The fine-tuned model demonstrated significant
improvements across all key dimensions except GPT-4’s evaluation.
For the evaluations of the ChatGPT4 are quite different from the
quantitative results, here, we not only suggest, but also propose that,
the result should be evaluated by human medical experts
