# Hearing Double: AI-Enhanced Retrieval of Personal Audio Archives and the Reshaping of Cultural Narratives 
---

**Authors:**
Dr. David Dunkley Gyimah, Reader/Associate Professor, Cardiff School of Journalism, Media and Culture
José Velázquez, MA, Archivist and Multimedia Producer, University of Pablo de Olavide (Associate Lecturer)

---

**Abstract:**
This paper examines historically important personal sound archives by exploring their phenomenological meaning, symbolic interpretation, their influence on how listeners perceived the world through sound recordings from the 1990s, and their contemporary impact. Integral to reclaiming the archive and making it accessible, advanced technical procedures were deployed using AI, namely Retrieval Augmented Generation (RAG), which the team regards will have a profound impact for audio producers beyond its application to this event.

Before becoming an academic, Reader Dr. David Dunkley Gyimah was a freelance BBC radio presenter and producer for London’s only talk radio show for Black Londoners in the early 1990s. Recordings of BBC GLR’s show were discarded by the station, but thirty years later duplicates were uncovered in Dr. Gyimah’s garage. The tapes were submitted to FIAT/IFTA’s Save our Archives and chosen for being historically important in a global competition. They featured rare interviews with figures such as Fela Kuti, the father of Afrobeat who denounces the music. Lord Herman Ouseley's newly elected position as the first Black person to head up Britain's Commission for Racial Equality, and his descriptions of his feelings and what was at stake for race relations, were significant, as was Nelson Mandela's 70th Birthday Tribute concert at Wembley Stadium – poignant as the BBC celebrated 40 years of Live Aid.

The show was the first to be presented by second-generation Brits whose beliefs and attitudes were different to their parents, and as such, these archives offer rich insights into their phenomenology and lived experiences. This unique perspective meant that while an audience's decoding of radio (sound) is generally thought as imperceptible, the show's production methods significantly interrogated this process. It was made for a specific audience (Black listeners) but also needed to appeal to a wider demographic, so its creators intentionally utilised W.E.B. Du Bois’ "double consciousness", balancing their self-perception with the perceptions of non-Black listeners.

Integral to making the tapes accessible to the public involved a technical approach from José Velázquez, encompassing advanced digitisation techniques for legacy media formats and, Retrieval-Augmented Generation (RAG) architecture within a bespoke Media Asset Management (MAM) system. RAG allows for a specific, and nuanced engagement with the historical tapes, as a solution which goes beyond this archival project and has the potential to be transformative for anyone accessing audio media, such as podcasts.

Further access is being considered for a modular exhibition design, where art meets technology (Figure 1). This design incorporates time-based media installations, utilising single-board computers (SBCs) and custom API development for dynamic content delivery and secure playback management. The project thereby highlights sound's potent role in research, revealing histories, shaping identity, and contributing to interdisciplinary research methodologies through its sonic dimensions.

---

**Keywords:** #AudiovisualArchives, #DigitalPreservation, #BlackBritishHistory, #MediaArt, #Installation, #RetrievalAugmentedGeneration (RAG), #MediaAssetManagement (MAM), #SingleBoardComputers (SBCs), #DIY, #APIDevelopment, #CulturalMemory, #SoundStudies, #AudioAccessibility.

---

## 1. Introduction: The Imperative of Preserving and Reclaiming Sonic Heritage

Cultural heritage, in its myriad forms, serves as a vital link between past, present, and future generations. While tangible heritage often takes precedence in preservation efforts, intangible forms, particularly sound archives, hold immense power in conveying lived experiences, societal shifts, and cultural nuances. However, the preservation and accessibility of such sonic heritage, especially that which exists on obsolescent physical formats, present significant challenges. This paper delves into a specific case study: the 'lost' audio archives of a groundbreaking BBC radio show from the early 1990s. It explores not only the historical and cultural significance of these recordings but also details an innovative, AI-enhanced technical solution for their reclamation, preservation, and public access. We argue that the integration of Artificial Intelligence (AI), specifically **Retrieval-Augmented Generation (RAG)**, within Digital Asset Management (DAM) systems is not merely a technical advancement but a profound enabler for reshaping how we experience, preserve, and share cultural heritage in a digital world.

---

## 2. "Hearing Double": A Unique Voice in Black British History

The genesis of this project lies in the rediscovery of audio tapes from a BBC GLR (Greater London Radio) talk show, produced and presented by Dr. David Dunkley Gyimah in the early 1990s. This program was unique for its time, being London's only talk radio show specifically catering to **Black Londoners**. Despite its historical significance, the original station discarded its recordings. Remarkably, thirty years later, duplicate tapes were discovered in Dr. Gyimah’s private collection. Recognizing their unparalleled historical value, these tapes were submitted to FIAT/IFTA’s global "Save our Archives" competition, where they were selected as historically important.

The content of these tapes offers an invaluable window into a pivotal moment in **Black British history**. They include rare interviews with iconic figures such as **Fela Kuti**, the legendary father of Afrobeat, who provocatively discusses his views on the genre. Also featured are critical discussions with **Lord Herman Ouseley**, following his groundbreaking appointment as the **first Black head of Britain's Commission for Racial Equality**, capturing his initial sentiments and the immense stakes for race relations in the UK. Furthermore, the archives contain poignant reflections on **Nelson Mandela's 70th Birthday Tribute concert at Wembley Stadium**, drawing parallels with the BBC's own 40th anniversary celebration of Live Aid.

What makes this archive particularly compelling is the perspective from which the show was conceived and presented. It was pioneered by second-generation British individuals whose beliefs and attitudes diverged significantly from those of their immigrant parents. Consequently, these recordings provide rich insights into their phenomenology and lived experiences, offering a distinct narrative voice often absent from mainstream historical records. While the decoding of radio sound is often considered an imperceptible process for audiences, the show's production methods deliberately interrogated this notion. Recognizing its dual purpose – to serve a specific Black audience while also appealing to a broader demographic – the creators intentionally employed **W.E.B. Du Bois’ concept of "double consciousness."** This involved a conscious balancing act between their self-perception and the perceptions of non-Black listeners, a critical approach that shaped the show's content and delivery, and which provides a powerful framework for interpreting its historical impact.

---

## 3. Using Retrieval-Augmented Generation (RAG) for Nuanced Access

Making these invaluable, legacy audio archives accessible to the public required a robust and innovative technical approach. José Velázquez led the development of a comprehensive strategy that began with advanced digitisation techniques for the original tape formats. However, the sheer volume and unstructured nature of audio data necessitated a more intelligent system for content discovery and nuanced engagement. This led to the implementation of a **Retrieval-Augmented Generation (RAG) architecture within a bespoke Media Asset Management (MAM) system**.

### 3.1. RAG at Work: Intelligent Information Retrieval

Our approach aligns with the evolving landscape of Digital Asset Management (DAM) systems, which are moving beyond simple content repositories to become sophisticated platforms for intelligent information retrieval. The core of this transformation lies in the integration of RAG architectures, enabling DAM systems to process natural language queries and provide contextually relevant information, significantly boosting asset discoverability and operational efficiency.

The process of ingesting and preparing the audio assets for RAG involved several crucial steps:

* **Asset Ingestion and Processing:** During this stage, the audio content from the digitised tapes was systematically processed. This involved high-fidelity audio transcription to convert spoken words into text. Beyond transcription, the system performed analysis to extract key metadata, identify speakers, segment discussions by topic, and capture temporal information.
* **Vector Embeddings and Vector Databases:** The processed information (transcripts, metadata, and derived semantic insights) was then transformed into high-dimensional numerical representations known as **vector embeddings**. These embeddings capture the semantic essence of the audio content – its true meaning, context, and relationships with other information within the archive. Unlike conventional databases, these vector embeddings are stored in a specialized **Vector Database**, optimized for efficient storage and querying of these high-dimensional data points. This allows the system to find and retrieve assets based on their genuine meaning, not just keywords.
* **Natural Language Query Interface:** Users interact with this intelligent MAM system through a query interface that supports natural language. This allows for complex, nuanced questions such as: "Show me all discussions from the early 90s about the impact of racism on community organizing in London among Black British youth." Crucially, this query is not sent directly to a generative AI model. Instead, it first queries the Vector Database to identify and retrieve semantically relevant context based on the user's natural language input and the asset's pre-computed vector embeddings. This initial contextualisation provides the subsequent AI processing with the specific information needed to produce accurate and relevant responses, mitigating the risk of hallucinations.
* **Large Language Models (LLMs):** The retrieved context, combined with the original user query, is then sent to a **Large Language Model (LLM)**. The LLM processes this combined input, leveraging its extensive knowledge and analytical capabilities to formulate an AI-driven answer, which is subsequently relayed to the user. This iterative process ensures that the generated responses are not only coherent but also firmly grounded in the authentic content of the historical audio archive.

### 3.2. Advantages for Cultural Heritage

The integration of RAG into the MAM system offers several profound advantages for managing and interpreting cultural heritage:

* **Accelerated Information Retrieval:** It significantly reduces the time typically spent on manual review or basic keyword searches, allowing researchers, educators, and the public to quickly unearth specific discussions, perspectives, or events within the vast archive.
* **Enhanced Asset Discoverability:** The semantic search capabilities enable the discovery of content that might otherwise be unlocatable through traditional metadata or keyword-based methods. This is particularly vital for audio, where the nuances of speech and conversation are easily missed by simple indexing.
* **Improved Decision-Making and Curation:** Immediate access to contextual information supports better decisions regarding content utilization, exhibition design, and strategic planning for cultural dissemination.
* **Increased Operational Efficiency:** Automates complex processes of asset comprehension and retrieval, freeing up human expertise for deeper analysis and interpretation.
* **Reduced AI Hallucinations:** By grounding LLM responses in verified archival content retrieved from the Vector Database, the system minimises the generation of factually incorrect or invented information, a critical concern in heritage contexts where accuracy and authenticity are paramount.

---

## 4. Public Engagement and Future Directions: Art Meets Technology

Beyond the immediate technical challenges of preservation and retrieval, a key objective of this project is to make these invaluable archives accessible to the public in engaging and meaningful ways. To this end, further access is being considered through a modular exhibition design, conceptualized as a space where **"art meets technology"** (Figures 1 and 2). This design envisions dynamic time-based media installations, leveraging readily available **single-board computers (SBCs)** and custom API development for flexible, secure content delivery and playback management. This approach not only democratizes access to the technology but also allows for adaptable exhibition configurations.

<img width="800" height="464" alt="image" src="https://github.com/user-attachments/assets/49fb76c3-4de1-4f56-ae1e-1020e70a2b37" />

Figure 1. Art meets Technology.


<img width="1352" height="582" alt="image" src="https://github.com/user-attachments/assets/535686a4-043a-41d7-a91c-e8a59c14b9ff" />

Figure 2. The AI-enhanced Archive.





