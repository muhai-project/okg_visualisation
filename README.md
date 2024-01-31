# Visualizing Social Debates on Inequality from a Large Social Media Knowledge Graph

## Contributors: Alkım Belevi, Evy Beijen, Mona Borth, Celeste Tacconi

Submitted on: 2024-01-31

Social media platforms such as Twitter have become spaces for societal and political dialogue. However,
existing strategies for analyzing such discourse often fail to capture the fine-grained opinions and contextual intricacies present in social media exchanges. We wished to address this limitation by employing
the Observatory Knowledge Graph (OKG) (Blin, I., Stork, L., Spillner, L., Santagiustina, C.: OKG: A
Knowledge Graph for Fine-grained Understanding of Social Media Discourse on Inequality. In: K-CAP
’23: Knowledge Capture Conference 2023, Pensacola, FL, USA, pp. 1–13. ACM, New York (2023). DOI:
https://doi.org/10.1145/3587259.3627557) as a base for our visualizations, capturing patterns and their intricacies related to inequality. The OKG enables fine-grained and contextual analyses as it captures semantic
structures and is designed to aid researchers in understanding online discussions on inequalities along with
relations between entities such as people, places, events, or organizations. To interact with this information,
we used SPARQL queries to extract key characteristics, sentiments, and contextual information from the
OKG. By visualizing the information, we aimed to extract meaningful insights from our dataset, bridging
the gap between complex data and interpretable information.

The social media data about inequality was extracted from the Twitter platform through the “academictwitteR” R library (Blin et al., 2023), using the Full-Archive API V2 with the query parameters “(inequality
OR inequalities)lang:en.” This forms a sample of 62015 tweets published from May 30th to August 27th,
2020, and the OKG contains both metadata and linguistic information about the tweets of this sample. The
visualizations of the OKG data are presented in this document, including brief interpretations and the R
code used to create them.