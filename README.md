# Storyteller
In this study, we explore the fine-tuning of a
LLaMA-based language model to generate engaging and coherent
fantasy stories. Utilizing a curated dataset of fantasy literature,
we applied the Unsloth [3] framework to fine-tune the model,
experimenting with several training methodologies. The paper
details our approach, including data preprocessing, fine-tuning
configurations, and evaluation metrics, and provides a comparative analysis of the generated outputs. Our results demonstrate
the effectiveness of the model in capturing the unique stylistic
and thematic elements of fantasy narratives, offering insights
into optimizing large language models for genre-specific creative
applications.
# Access our models
Please check refers to our models on [Hugging Face](https://huggingface.co/Group-26)
You can try our model by downloading Ollama and run
'''
ollama run hf.co/Group-26/storyteller_v9:Q8_0
'''
to download and inference our best performance v9 model.

### Files in our project
    .
    ├── result                  # Results files
    ├── src                     # Source files used for generating data and fine-tuning
    ├── Report.pdf              # Complete report of this project
    └── README.md
