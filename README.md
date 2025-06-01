# Supplementary Materials for "30DayGen: Leveraging LLMs to Create Content Corpora for Niche Domains"

This repository contains supplementary materials for our paper, "30DayGen: Leveraging LLMs to Create Content Corpora for Niche Domains"

## Repository Structure

- **/prompts**: Contains the full text of Large Language Model (LLM) prompts used for various stages of the 30DAYGEN system, including:
  - `webpage_filtering_prompt.txt`: LLM prompt for filtering relevant webpages.
  - `challenge_extraction_prompt.txt`: LLM prompt for extracting and formatting challenges.
  - `duplicate_judgment_prompt.txt`: LLM prompt for identifying duplicate challenges.
  - `search_validation_prompt.txt`: LLM prompt for validating search results at runtime.
- **/data_lists**: Contains lists used in the data collection and evaluation processes:
  - `collection_search_queries.txt`: The 25 web search queries used to collect initial webpages.
  - `blocked_base_domains.txt`: List of base domains blocked during web collection.
  - `evaluation_search_queries.txt`: The 100 search queries used for the runtime search evaluation.

## Contact

Email: franklin.zhang@bellevuecollege.edu
