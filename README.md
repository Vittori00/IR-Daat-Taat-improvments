# IR-Daat-Taat-Improvement

## Overview

This project focuses on enhancing the efficiency and effectiveness of Boolean query processing in Information Retrieval (IR) systems by implementing and comparing two primary strategies: Term-at-a-Time (TAAT) and Document-at-a-Time (DAAT).

In IR systems, processing Boolean queries efficiently is crucial for retrieving relevant documents from large datasets. TAAT and DAAT are two fundamental strategies employed for this purpose:

- **Term-at-a-Time (TAAT):** Processes one term's posting list at a time, accumulating scores for documents containing that term.
- **Document-at-a-Time (DAAT):** Processes documents one at a time, considering all query terms simultaneously to compute relevance scores.

This project implements both TAAT and DAAT strategies, evaluates their performance, and explores potential improvements to optimize query processing.

## Features

- **Implementation of TAAT and DAAT:** Provides a comparative analysis of both strategies in terms of efficiency and effectiveness.
- **Performance Metrics:** Measures and reports on key metrics such as processing time and retrieval accuracy for each method.
- **Optimization Techniques:** Explores various optimization methods to enhance the performance of TAAT and DAAT algorithms.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Vittori00/IR-Daat-Taat-improvments.git
   cd IR-Daat-Taat-improvments
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Prepare the Dataset:**
   Ensure your dataset is in the appropriate format and located in the designated directory.

2. **Run the Jupyter Notebook:**
   Open and execute the `IR project.ipynb` notebook to perform the analysis and view results.

## Results

The project provides a detailed comparison of TAAT and DAAT strategies, including performance metrics and insights into their respective advantages and limitations. Optimization techniques are also evaluated to determine their impact on query processing efficiency.

