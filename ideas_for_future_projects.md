docker-compose which will setup a streamlit app (as a demo, once backend is confirmed to be working it can be swiched to Flask or Django) and vector database (Qdrant)
inside there will be an option to submit documents for a embedding and save to vector DB
then user can ask what they want

Potential use cases (maybe create multiple apps which contain the same base logic?)
- Submitt long contracts so that user can ask about specifications? Maybe use different LLM with domain specific knowledge as a backend?
- Submit research papers, or include some integration with https://arxiv.org/?
- Submit code documentation ?
- Scrape financial data from public sources (KRS, bankier, biznesradar) so that user can compare companies on some deeper level ?
- Assistant (this will scrape data from RSS feeds and save those to vector DB), will accept voice commands and will be able to respond also using voice

 **Idea of this project is to get proficient with creating RAGs** with both, models avaiable through apis and custom huggingface models.