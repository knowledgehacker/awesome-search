# Awesome-search

I've been building e-commerce search applications for almost ten years. Below you can find a list of (some) publications, conferences and books that inspire me. Grouped by topic.

### Topics
- [General, fun, philosophy](#general-fun-philosophy)
- [Types of search](#types-of-search)
- [Search UX](#search-ux) 
- [Spelling correction](#spelling-correction) 
- [Synonyms](#synonyms) 
- [Suggestions](#suggestions) 
- [BERT](#bert) 
- [Spacy](#spacy) 
- [Word2Vec](#word2vec) 
- [Collocations, common phrases](#collocations-common-phrases)
- [Graphs/Taxonomies/Knowledge Graph](#graphstaxonomiesknowledge-graph) 
- [Query understanding](#query-understanding)
- [Learning to rank](#learning-to-rank)
- [Other, Search](#other-search) 
- [Other, Algorithms](#other-algorithms)
- [Tracking, profiling, GDPR, Analysis](#tracking-profiling-gdpr-analysis) 
- [Testing and metrics](#testing-and-metrics) 
- [Conferences](#conferences) 
- [Books](#books) 
- [Management, Search Team](#management-search-team)
- [Personalies and influencers](#personalies-and-influencers) 
- [Query Understanding by Daniel Tunkelang](#query-understanding-by-daniel-tunkelang)
- [Videos](#videos)
- [Usecases](#usecases)

## General, fun, philosophy

* [Falsehoods Programmers Believe About Search](https://opensourceconnections.com/blog/2019/05/29/falsehoods-programmers-believe-about-search/)
* [Ethical Search: Designing an irresistible journey with a positive impact](https://medium.com/empathyco/fooddiscovery-2-ethical-search-designing-an-irresistible-journey-with-a-positive-impact-cc921c07a5a8)
* [Humans Search for Things not for Strings](https://www.linkedin.com/pulse/humans-search-things-strings-andreas-wagner/)
* [On Semantic Search](https://medium.com/modern-nlp/semantic-search-fuck-yeah-e371c0f639d)
* [Feedback debt: what the segway teaches search teams](https://opensourceconnections.com/blog/2020/03/19/feedback-debt/)
* [Supporting the Searcher’s Journey: When and How](https://medium.com/@dtunkelang/supporting-the-searchers-journey-when-and-how-568e9b68fe02)
* [Search: Intent, Not Inventory](https://medium.com/@dtunkelang/search-intent-not-inventory-289386f28a21)
* [Shopping is Hard, Let’s go Searching!](https://medium.com/@dtunkelang/shopping-is-hard-lets-go-searching-f61f3d5764d3)
* [Search Optimization 101 – How do I know that my search is broken?](https://blog.supahands.com/2020/07/08/how-do-i-know-that-my-search-is-broken/)

## Types of search

* Etsy. [Targeting Broad Queries in Search](https://codeascraft.com/2015/07/29/targeting-broad-queries-in-search/)
* [How Etsy Uses Thermodynamics to Help You Search for “Geeky”](https://codeascraft.com/2015/08/31/how-etsy-uses-thermodynamics-to-help-you-search-for-geeky/)
* Daniel Tunkelang.
[Broad and Ambiguous Search Queries](https://medium.com/@dtunkelang/broad-and-ambiguous-search-queries-1bbbe417dcc)

## Search UX 

### Baymard's guides

* [Deconstructing E-Commerce Search: The 12 Query Types](https://baymard.com/blog/ecommerce-search-query-types)
* [Autodirect or Guide Users to Matching Category](https://baymard.com/blog/autodirect-searches-matching-category-scopes)
* [13 Design Patterns for Autocomplete Suggestions (27% Get it Wrong)](https://baymard.com/blog/autocomplete-design)
* [E-Commerce Search Needs to Support Users’ Non-Product Search Queries (15% Don’t)](https://baymard.com/blog/support-non-product-search)
* [Search UX: 6 Essential Elements for ‘No Results’ Pages](https://baymard.com/blog/no-results-page)
* [Product Thumbnails Should Dynamically Update to Match the Variation Searched For (54% Don’t)](https://baymard.com/blog/color-and-variation-searches)
* [Faceted Sorting - A New Method for Sorting Search Results](https://baymard.com/blog/faceted-sorting)
* [The Current State of E-Commerce Search](https://baymard.com/blog/external-article-state-of-ecommerce-search)
* [E-Commerce Sites Need Multiple of These 5 ‘Search Scope’ Features](https://baymard.com/blog/search-scope)
* [E-Commerce Search Field Design and Its Implications](https://baymard.com/blog/search-field-design)
* [E-Commerce Sites Should Include Contextual Search Snippets (96% Get it Wrong)](https://baymard.com/blog/search-snippets)
* [E-Commerce Search Usability: Report & Benchmark](https://baymard.com/blog/ecommerce-search-report-and-benchmark)
* [Six ‘COVID-19’ Related E-Commerce UX Improvements to Make](https://baymard.com/blog/covid-19-ux-improvements)

## Spelling correction

* Peter Norvig. ["How to Write a Spelling Corrector"](http://norvig.com/spell-correct.html). Classic publication. 
* Daniel Tunkelang. ["Spelling Correction"](https://queryunderstanding.com/spelling-correction-471f71b19880)
* [A simple spell checker built from word vectora](https://blog.usejournal.com/a-simple-spell-checker-built-from-word-vectors-9f28452b6f26)
* A closer look into the spell correction problem: [1](https://medium.com/@searchhub.io/a-closer-look-into-the-spell-correction-problem-part-1-a6795bbf7112), [2](https://medium.com/@searchhub.io/a-closer-look-into-the-spell-correction-problem-part-2-introducing-predict-8993ecab7226), [3](https://medium.com/@searchhub.io/a-closer-look-into-the-spell-correction-problem-part-3-the-bells-and-whistles-19697a34011b), [preDict](https://github.com/searchhub/preDict)
* [Deep Spelling](https://machinelearnings.co/deep-spelling-9ffef96a24f6)
* [Modeling Spelling Correction for Search at Etsy](https://codeascraft.com/2017/05/01/modeling-spelling-correction-for-search-at-etsy/)
* Wolf Garbe. Author of [Sympell](https://github.com/wolfgarbe/symspell). [1000x Faster Spelling Correction algorithm](https://medium.com/@wolfgarbe/1000x-faster-spelling-correction-algorithm-2012-8701fcd87a5f), [Top highlight SymSpell vs. BK-tree: 100x faster fuzzy string search & spell checking](https://towardsdatascience.com/symspell-vs-bk-tree-100x-faster-fuzzy-string-search-spell-checking-c4f10d80a078), [Fast Word Segmentation of Noisy Text](https://towardsdatascience.com/fast-word-segmentation-for-noisy-text-2c2c41f9e8da)
* [Chars2vec: character-based language model for handling real world texts with spelling errors and](https://hackernoon.com/chars2vec-character-based-language-model-for-handling-real-world-texts-with-spelling-errors-and-a3e4053a147d)
* JamSpell, spelling correction taking into account surrounding context - [library](https://github.com/bakwc/JamSpell), (in russian) [Исправляем опечатки с учётом контекста](https://habr.com/ru/post/346618/)
* [Embedding for spelling correction](https://towardsdatascience.com/embedding-for-spelling-correction-92c93f835d79)
* [A simple spell checker built from word vectors](https://blog.usejournal.com/a-simple-spell-checker-built-from-word-vectors-9f28452b6f26)
* [What are some algorithms of spelling correction that are used by search engines?](https://www.quora.com/String-Searching-Algorithms/What-are-some-algorithms-of-spelling-correction-that-are-used-by-search-engines-For-example-when-I-used-Google-to-search-Google-imeges-it-prompted-me-Did-you-mean-Google-images/answer/Wolf-Garbe)
* [Moman](https://github.com/jpbarrette/moman) - lucene/solr/elasticsearch spell correction/autocorrect is actually powered by this library.
* [Query Segmentation and Spelling Correction](https://towardsdatascience.com/query-segmentation-and-spelling-correction-483173008981)
* [How search|hub.io changed the way of working for Site Search Consultants
](https://medium.com/@searchhub.io/how-search-hub-io-changed-the-way-of-working-for-site-search-consultants-17a3d618e09)
* [Applying Context Aware Spell Checking in Spark NLP](https://medium.com/spark-nlp/applying-context-aware-spell-checking-in-spark-nlp-3c29c46963bc)
* [Autocorrect in Google, Amazon and Pinterest and how to write your own one](https://towardsdatascience.com/autocorrect-in-google-amazon-and-pinterest-and-how-to-write-your-own-one-6d23bc927c81)

## Synonyms

* [Boosting the power of Elasticsearch with synonyms](https://www.elastic.co/blog/boosting-the-power-of-elasticsearch-with-synonyms)
* [Real Talk About Synonyms and Search](https://medium.com/@dtunkelang/real-talk-about-synonyms-and-search-bb5cf41a8741)
* [Synonyms in Solr I — The good, the bad and the ugly](https://medium.com/empathyco/synonyms-in-solr-i-the-good-the-bad-and-the-ugly-efe8e437a940)
* [Synonyms and Antonyms from WordNet](https://medium.com/@tameremil/synonyms-and-antonyms-from-wordnet-778f6274fb09)
* [Synonyms and Antonyms in Python](https://towardsdatascience.com/synonyms-and-antonyms-in-python-a865a5e14ce8)
* [Dive into WordNet with NLTK](https://medium.com/parrot-prediction/dive-into-wordnet-with-nltk-b313c480e788)
* [Creating Better Searches Through Automatic Synonym Detection](https://lucidworks.com/post/search-automatic-synonym-detection/)
* [Multiword synonyms in search using Querqy](https://sharing.luminis.eu/blog/multiword-synonyms-in-search-using-querqy/)
* [How to Build a Smart Synonyms Model](https://blog.kensho.com/how-to-build-a-smart-synonyms-model-1d525971a4ee)

## Suggestions

* Giovanni Fernandez-Kincade. 
[Bootstrapping Autosuggest](https://medium.com/related-works-inc/bootstrapping-autosuggest-c1ca3edaf1eb), [Building an Autosuggest Corpus, Part 1](https://medium.com/related-works-inc/building-an-autosuggest-corpus-part-1-3acd26056708), [Building an Autosuggest Corpus, Part 2](https://medium.com/related-works-inc/building-an-autosuggest-corpus-nlp-d21b0f25c31b), [Autosuggest Retrieval Data Structures & Algorithms](https://medium.com/related-works-inc/autosuggest-retrieval-data-structures-algorithms-3a902c74ffc8), [Autosuggest Ranking](https://medium.com/related-works-inc/autosuggest-ranking-d8a3242c2837)
* [13 Design Patterns for Autocomplete Suggestions](https://baymard.com/blog/autocomplete-design)
* [On two types of suggestions](https://web.archive.org/web/20181207194952/https://www.searchblox.com/autosuggest-search-query-based-vs-content-based)
* [Improving Search Suggestions for eCommerce](https://medium.com/empathyco/improving-search-suggestions-for-ecommerce-cb1bc2946021)
* [Autocomplete Search Best Practices to Increase Conversions](https://lucidworks.com/post/autocomplete-search-increase-conversions/)
* Nielsen Norman Group: [Site Search Suggestions](https://www.nngroup.com/articles/site-search-suggestions/)
* [Why we’ve developed the searchhub smartSuggest module and why it might matter to you](https://www.linkedin.com/pulse/why-weve-developed-searchhub-smartsuggest-module-might-andreas-wagner/)


## BERT

* [Understanding BERT and Search Relevance](https://opensourceconnections.com/blog/2019/11/05/understanding-bert-and-search-relevance/)
* [Google is improving web search with BERT – can we use it for enterprise search too?](https://www.linkedin.com/pulse/google-improving-web-search-bert-can-we-use-too-mickel-gr%C3%B6nroos/)

## Spacy

[Awesome Spacy](https://github.com/frutik/awesome-spacy) - Natural language upderstanding, content enrichment etc.

## Word2Vec

* [Word2Vec For Phrases — Learning Embeddings For More Than One Word](https://towardsdatascience.com/word2vec-for-phrases-learning-embeddings-for-more-than-one-word-727b6cf723cf)
* [Gensim Word2Vec Tutorial](http://kavita-ganesan.com/gensim-word2vec-tutorial-starter-code/#.XV-wnJMzbUL)
* [How to incorporate phrases into Word2Vec – a text mining approach](http://kavita-ganesan.com/how-to-incorporate-phrases-into-word2vec-a-text-mining-approach/#.XV-wnJMzbUL)
* [Word2Vec — a baby step in Deep Learning but a giant leap towards Natural Language Processing](https://medium.com/explore-artificial-intelligence/word2vec-a-baby-step-in-deep-learning-but-a-giant-leap-towards-natural-language-processing-40fe4e8602ba)
* [How to Develop Word Embeddings in Python with Gensim](https://machinelearningmastery.com/develop-word-embeddings-python-gensim/)

## Collocations, common phrases

* [Automatically detect common phrases – multi-word expressions / word n-grams – from a stream of sentences.]( https://radimrehurek.com/gensim/models/phrases.html)
* [The Unreasonable Effectiveness of Collocations](https://opensourceconnections.com/blog/2019/05/16/unreasonable-effectiveness-of-collocations/)

## Graphs/Taxonomies/Knowledge Graph

* [Knowledge graphs applied in the retail industry](https://towardsdatascience.com/knowledge-graphs-applied-in-the-retail-industry-ecac4e7baf8)
  
  Knowledge graphs are becoming increasingly popular in tech. We explore how they can be used in the retail industry to enrich data, widen search results and add value to a retail company.  
  
* [Search query expansion with query embeddings](https://bytes.grubhub.com/search-query-embeddings-using-query2vec-f5931df27d79)

* [Awesome Knowledge Graphs](https://github.com/frutik/awesome-knowledge-graphs)


## Query understanding

* Daniel Tunkelang [Query Understanding](https://queryunderstanding.com/introduction-c98740502103). 
* [Query Understanding, Divided into Three Parts](https://medium.com/@dtunkelang/query-understanding-divided-into-three-parts-d9cbc81a5d09)
* [Search for Things not for Strings](https://medium.com/@searchhub.io/humans-search-for-things-not-for-strings-5dd115d95986)
* Understanding the Search Query. [Part 1](https://towardsdatascience.com/understanding-the-search-query-part-i-632d1b323b50), [Part 2](https://medium.com/analytics-vidhya/understanding-the-search-query-part-ii-44d18892283f), [Part 3](https://medium.com/@sonusharma.mnnit/understanding-the-search-query-part-iii-a0c5637a639) 

#### Query segmentation

* Paper [Unsupervised Query Segmentation Using only Query Logs ](https://www.microsoft.com/en-us/research/wp-content/uploads/2011/01/pp0295-mishra.pdf)
* Paper [Towards Semantic Query Segmentation](https://arxiv.org/pdf/1707.07835.pdf)

## Learning to Rank

* [How is search different than other machine learning problems?](https://opensourceconnections.com/blog/2017/08/03/search-as-machine-learning-prob/)
* [Reinforcement learning assisted search ranking](https://medium.com/sajari/reinforcement-learning-assisted-search-ranking-a594cdc36c29)
* [When to use a machine learned vs. score-based search ranker](https://towardsdatascience.com/when-to-use-a-machine-learned-vs-score-based-search-ranker-aa8762cd9aa9)


## Other, Search

* [Why is it so hard to sort by price?](https://medium.com/@dtunkelang/why-is-it-so-hard-to-sort-by-price-2a5e63899233)
* [Faceted Sorting](https://baymard.com/blog/faceted-sorting)
* [E-commerce Search Re-Ranking as a Reinforcement Learning Problem](https://towardsdatascience.com/e-commerce-search-re-ranking-as-a-reinforcement-learning-problem-a9d1561edbd0)

## Other, Algorithms

* [Locality Sensitive Hashing](https://towardsdatascience.com/understanding-locality-sensitive-hashing-49f6d1f6134)
* [Minhash](http://ekzhu.com/datasketch/minhash.html)
* [Better than Average: Sort by Best Rating](https://www.elastic.co/blog/better-than-average-sort-by-best-rating-with-elasticsearch)
* [How Not To Sort By Average Rating](https://www.evanmiller.org/how-not-to-sort-by-average-rating.html)
* [The influence of TF-IDF algorithms in eCommerce search](https://medium.com/empathyco/the-influence-of-tf-idf-algorithms-in-ecommerce-search-e7cb9ab8e662)
* [One hot encoding](https://medium.com/fintechexplained/nlp-text-data-to-numbers-d28d32294d2e)
* [Keyword Extraction using RAKE](https://codelingo.wordpress.com/2017/05/26/keyword-extraction-using-rake/)
* [Yet Another Keyword Extractor (Yake)](https://github.com/LIAAD/yake)

## Tracking, profiling, GDPR, Analysis

* [Anonymisation: managing data protection risk (code of practice)](https://ico.org.uk/media/1061/anonymisation-code.pdf)
* [The Anonymisation Decision-Making Framework](https://ukanon.net/wp-content/uploads/2015/05/The-Anonymisation-Decision-making-Framework.pdf)
* [98 personal data points that Facebook uses to target ads to you](https://www.washingtonpost.com/news/the-intersect/wp/2016/08/19/98-personal-data-points-that-facebook-uses-to-target-ads-to-you/)
* [Opportunity Analysis for Search](https://www.linkedin.com/pulse/opportunity-analysis-search-daniel-tunkelang/)

## Testing and metrics

* [A/B Testing for Search is Different](https://medium.com/@dtunkelang/a-b-testing-for-search-is-different-f6b0f6f4d0f5)
* [Discounted cumulative gain](https://en.wikipedia.org/wiki/Discounted_cumulative_gain)
* [Demystifying nDCG and ERR](https://opensourceconnections.com/blog/2019/12/09/demystifying-ndcg-and-err/)
* Evaluating Search (by Daniel Tunkelang) [Measure It](https://medium.com/@dtunkelang/evaluating-good-search-part-i-measure-it-5507b2dbf4f6), [Measuring Searcher Behavior](https://medium.com/@dtunkelang/evaluating-search-measuring-searcher-behavior-5f8347619eb0), [Using Human Judgement](https://medium.com/@dtunkelang/evaluating-search-using-human-judgement-fbb2eeba37d9)
* [When There’s No Conversion Rate](https://medium.com/@dtunkelang/when-theres-no-conversion-rate-67a372666fed)
* [Choosing your search relevance evaluation metric](https://opensourceconnections.com/blog/2020/02/28/choosing-your-search-relevance-metric/)
* [How to Implement a Normalized Discounted Cumulative Gain (NDCG) Ranking Quality Scorer in Quepid](https://opensourceconnections.com/blog/2018/02/26/ndcg-scorer-in-quepid/)
* [5 Right Ways to Measure How Search Is Performing](https://opensourceconnections.com/blog/2020/05/11/5-right-ways-to-measure-search/)
* [Measuring Search: Metrics Matter](https://medium.com/@jamesrubinstein/measuring-search-metrics-matter-de124c2f6f8c)


## Conferences

* [Activate](https://www.activate-conf.com/)
* [Berlin buzzword](berlinbuzzwords.de)
* [Haystack](https://haystackconf.com/)
* [Elastic{ON}](https://www.elastic.co/elasticon/)
* [MIX-CAMP E-COMMERCE SEARCH](http://www.mices.co)

## Books

* [AI-powered search](https://www.manning.com/books/ai-powered-search)
* [Relevant Search](https://www.manning.com/books/relevant-search)
* [Deep Learning for search](https://www.manning.com/books/deep-learning-for-search)
* [Interactions with search systems](https://www.cambridge.org/core/books/interactions-with-search-systems/5B3CF5920355A8B09088F2C409FFABDC)
* [Embeddings in Natural Language Processing. Theory and Advances in Vector Representation of Meaning](http://josecamachocollados.com/book_embNLP_draft.pdf)
* [Search User Interfaces](http://www.searchuserinterfaces.com)
* [Search Patterns](https://searchpatterns.org/)

## Management, Search Team

* [Search is a Team Sport](https://medium.com/search-in-21st-century/search-is-a-team-sport-400eecdfe736)
* [Thoughts about Managing Search Teams](https://medium.com/@dtunkelang/thoughts-about-managing-search-teams-f8d2f54fbed7)
* [Building an Effective Search Team: the key to great search & relevancy](https://opensourceconnections.com/blog/2020/05/14/building-an-effective-search-team-the-key-to-great-search-relevancy/)
* [Interview Questions for Search Relevance Engineers, Data Scientists, and Product Managers](https://medium.com/@dtunkelang/interview-questions-for-search-relevance-engineers-and-product-managers-7a1b6b8cacea)
* [Query Triage: The Secret Weapon for Search Relevance](https://medium.com/@jamesrubinstein/query-triage-the-secret-weapon-for-search-relevance-1a02cdd297ed)

## Personalies and influencers

* [Daniel Tunkelang (he is God of Search)](https://medium.com/@dtunkelang)
* [Max Irwin](https://twitter.com/binarymax)
* [Doug Turnbull](https://twitter.com/softwaredoug)
* [Baymard’s Institute](https://baymard.com/blog)

## Usecases

* Airbnb - [Machine Learning-Powered Search Ranking of Airbnb Experiences](https://medium.com/airbnb-engineering/machine-learning-powered-search-ranking-of-airbnb-experiences-110b4b1a0789)
* Airbnb - [Listing Embeddings in Search Ranking](https://medium.com/airbnb-engineering/listing-embeddings-for-similar-listing-recommendations-and-real-time-personalization-in-search-601172f7603e)
* Skyscanner - [Learning to Rank for Flight Itinerary Search](https://hackernoon.com/learning-to-rank-for-flight-itinerary-search-8594761eb867)
* [Search at Slack](https://slack.engineering/search-at-slack-431f8c80619e)

## Query Understanding by Daniel Tunkelang
   Better search through query understanding.
   
* [An Introduction](https://queryunderstanding.com/introduction-c98740502103)
* [Language Identification](https://queryunderstanding.com/language-identification-c1d2a072eda)
* [Character Filtering](https://queryunderstanding.com/character-filtering-76ede1cf1a97)
* [Tokenization](https://queryunderstanding.com/tokenization-c8cdd6aef7ff)
* [Spelling Correction](https://queryunderstanding.com/spelling-correction-471f71b19880)
* [Stemming and Lemmatization](https://queryunderstanding.com/stemming-and-lemmatization-6c086742fe45)
* [Query Rewriting: An Overview](https://queryunderstanding.com/query-rewriting-an-overview-d7916eb94b83)
* [Query Expansion](https://queryunderstanding.com/query-expansion-2d68d47cf9c8)
* [Query Relaxation](https://queryunderstanding.com/query-relaxation-342bc37ad425)
* [Query Segmentation](https://queryunderstanding.com/query-segmentation-2cf860ade503)
* [Query Scoping](https://queryunderstanding.com/query-scoping-ed61b5ec8753)
* [Entity Recognition](https://queryunderstanding.com/entity-recognition-763cae840a20)
* [Taxonomies and Ontologies](https://queryunderstanding.com/taxonomies-and-ontologies-8e4812a79cb2)
* [Autocomplete](https://queryunderstanding.com/autocomplete-69ed81bba245)
* [Autocomplete and User Experience](https://queryunderstanding.com/autocomplete-and-user-experience-421df6ab3000)
* [Contextual Query Understanding: An Overview](https://queryunderstanding.com/contextual-query-understanding-65c78d792dd8)
* [Session Context](https://queryunderstanding.com/session-context-4af0a355c94a)
* [Location as Context](https://queryunderstanding.com/geographical-context-77ce4c773dc7)
* [Seasonality](https://queryunderstanding.com/seasonality-5eef79d8bf1c)
* [Personalization](https://queryunderstanding.com/personalization-3ed715e05ef)
* [Search as a Conversation](https://queryunderstanding.com/search-as-a-conversation-bafa7cd0c9a5)
* [Clarification Dialogues](https://queryunderstanding.com/clarification-dialogues-69420432f451)
* [Relevance Feedback](https://queryunderstanding.com/relevance-feedback-c6999529b92c)
* [Faceted Search](https://queryunderstanding.com/faceted-search-7d053cc4fada)
* [Search Results Presentation](https://queryunderstanding.com/search-results-presentation-7d6c6c384ec1)
* [Search Result Snippets](https://queryunderstanding.com/search-result-snippets-e8c447950219)
* [Search Results Clustering](https://queryunderstanding.com/search-results-clustering-b2fa64c6c809)
* [Question Answering](https://queryunderstanding.com/question-answering-94984185c203)
* [Query Understanding and Voice Interfaces](https://queryunderstanding.com/query-understanding-and-voice-interfaces-6cd60d063fca)
* [Query Understanding and Chatbots](https://queryunderstanding.com/query-understanding-and-chatbots-5fa0c154f)

## Videos

* [Relevant Facets](https://www.youtube.com/watch?v=W8DJYfAKKLA)

## Other awesome stuff

* [Awesome Knowledge Graphs](https://github.com/frutik/awesome-knowledge-graphs)
* [Awesome time series](https://github.com/frutik/awesome-timeseries)
* [Awesome Spacy](https://github.com/frutik/awesome-spacy)
