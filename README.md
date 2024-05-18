# Financial Entity Recognition with spaCy

## Overview

This project focuses on developing a custom Natural Language Processing (NLP) pipeline using the spaCy `en_core_web_sm` model. The pipeline is designed to accurately identify and extract company names, stock symbols, indexes, and stock exchanges from financial text data. 

## Features

- **Custom NLP Pipeline**: Utilizes spaCy's `en_core_web_sm` model for accurate financial entity recognition.
- **Entity Ruler**: Developed an entity ruler with special case handling to improve the model's accuracy in financial text analysis.
- **Custom Component**: Implemented a custom spaCy component to remove unwanted entities, ensuring cleaner and more relevant data output.
- **Visualization**: Leveraged spaCy's `displacy` for real-time visualization of named entities, providing clear insights into extracted financial entities.
