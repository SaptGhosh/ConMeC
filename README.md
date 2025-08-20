# ConMeC-Common-Noun-Metonymy-Corpus

The repository accompanies our NAACL 2025 publication "ConMeC: A Dataset for Metonymy Resolution with Common Nouns"

**Dataset Access:**
The dataset can be downloaded directly from Hugging Face: https://huggingface.co/datasets/Rey97/ConMeC

**What is ConMeC?**
ConMeC is the first large-scale, systematically annotated dataset focused on common noun metonymy. It is designed to support tasks in metonymy resolution, figurative language understanding, and LLM evaluation.

Each instance includes:
	•	A full sentence
	•	The target noun
	•	A binary label indicating whether the noun is used metonymically (1) or literally (0)
	•	Metonymy category tags (container, producer, product, location, causer, possessed)
  •	Preceeding and suceeding sentences for additional context
  •	Document URL and title

**Example**
Target Word: stadium
Sentence: "he said as the **stadium** cheered, ""It's the bottom of the 7th, the last chance to order beer."
Label: Metonymic
Category: Location
