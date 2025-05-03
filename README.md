# HSL844_2024-25
# Scope Ambiguity Experiment in Assamese

This repository contains all code and data for Experiment 1A on scope ambiguity in Assamese, replicating Gaurav et al. (2024).

## Files

### Code (HTML exports)
- **GPT4_control.html**  
  Code used to generate “control” responses from GPT-4.  
- **GPT4_test.html**  
  Code used to generate the “test” (scope-ambiguity) responses from GPT-4.  
- **IndicGPT2_control.html**  
  Code used to generate “control” responses from the AI4Bharat Indic-GPT2 model.  
- **IndicGPT2_test.html**  
  Code used to generate the “test” responses from the AI4Bharat Indic-GPT2 model.

> These are Word-exported HTMLs of the scripts you ran—they include all prompts, model calls, and output‐parsing logic.

### Data
- **input_assamese_sentence.csv**  
  The 152 Assamese sentences you created and translated (one per row), plus any metadata. This is the primary stimulus set for your human and model evaluations.
- **exp1b_base_dataset.csv**  
  The original English stimuli (153 sentences) used in Gaurav et al. (2024) for Experiment 1B. Sourced from the [McGill-NLP/scope-ambiguity](https://github.com/McGill-NLP/scope-ambiguity) repository.

## Usage

1. Open the HTML scripts in your browser to review and re-run the data-collection code.  
2. Load the `.csv` files into your analysis notebooks for statistical testing and plotting.

---

**Reference**  
Gaurav, A., et al. (2024). _Scope ambiguity in large-scale language models_. In *Proceedings of XYZ*.  
