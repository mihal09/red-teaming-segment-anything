# red-teaming-segment-anything
Repository contains code used in our analyses of the robustness of Segment Anything model.
The technical report can be seen in the attached pdf (TODO).

### Repository contents
Repository contains 2 notebooks:
- sam_style_transfer.ipynb - experiments to assess the quality of generated masks under different weather conditions.
- TODO - experiments to check whether LangSAM (version of Segment Anything with text prompts input) can unintentionally classify celebrities when prompted with a full name.

### Motivation
Given the increasing adoption of foundation models in various critical applications, there is
a pressing need to assess their robustness. As the Segment Anything model holds potential
application in the development of autonomous cars, our experiments evaluate the model’s
resilience to segmentation of street photographs captured under diverse weather conditions.
Additionally, as the model was trained on various datasets, we examine its capacity to
classify celebrity faces. This inquiry is crucial, as it underscores potential privacy concerns
and misuse implications associated with unintended classification.

### Used code repositories
Our code uses parts of these repositories:
- SAM: https://github.com/facebookresearch/segment-anything
- LangSAM: https://github.com/luca-medeiros/lang-segment-anything
- Multiweather city dataset: https://github.com/vnmusat/multi-weather-city

### Ethical principals
Our research adheres to ethical principles and we expect all users to employ it responsibly
and only for noble intentions.


