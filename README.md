# ConMeC-Common-Noun-Metonymy-Corpus

The repository accompanies our NAACL 2025 publication "ConMeC: A Dataset for Metonymy Resolution with Common Nouns"

**Dataset Access:**<br>
The dataset can be downloaded directly from Hugging Face: https://huggingface.co/datasets/Rey97/ConMeC

**What is ConMeC?**<br>
ConMeC is the first large-scale, systematically annotated dataset focused on common noun metonymy. It is designed to support tasks in metonymy resolution, figurative language understanding, and LLM evaluation.

Each instance includes:<br>
	•	A full sentence<br>
	•	The target noun<br>
	•	A binary label indicating whether the noun is used metonymically (1) or literally (0)<br>
	•	Metonymy category tags (container, producer, product, location, causer, possessed)<br>
  •	Preceeding and suceeding sentences for additional context<br>
  •	Document URL and title

**Example**<br>
Target Word: stadium<br>
Sentence: "he said as the **stadium** cheered, ""It's the bottom of the 7th, the last chance to order beer."<br>
Label: Metonymic<br>
Category: Location
