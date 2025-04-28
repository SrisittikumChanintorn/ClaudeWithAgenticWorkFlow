# AgenticWorkflow - Tree of Thought Analysis with Reflection 

## Project Overview 📚

AgenticWorkflow implements an advanced analytical framework using Tree of Thought methodology enhanced with reflection techniques. This project leverages Claude models from Anthropic to perform deep, multi-perspective analysis of complex questions through structured branching and reflection.

## Core Concept: Tree of Thought with Reflection 🧠

### Tree of Thought (ToT) Approach 🌳
The Tree of Thought methodology starts with a root question that branches into multiple perspectives. Each perspective is then further analyzed through sub-branches that focus on specific aspects of the initial branch. This creates a comprehensive analytical structure where:

1. The "First question ( Root )"  defines the overall analysis scope
2. Primary branches represent major analytical perspectives
3. Sub-branches explore specialized dimensions within each perspective
4. Each branch receives tailored prompt instructions specific to its analytical focus

### Reflection Enhancement ✔️
The reflection technique enriches the Tree of Thought approach by:

1. Reviewing initial perspective outputs for accuracy and completeness
2. Identifying potential gaps or weaknesses in the reasoning
3. Refining arguments to increase clarity and professionalism
4. Adding nuance before the perspective informs sub-branches
5. Ensuring each analytical thread maintains high quality throughout the tree

This combined approach ensures that each branch not only addresses its designated perspective but does so with refined reasoning and enhanced analytical depth.

## Architecture 🛠️

### Primary Branches 🌿
- **Domestic Market Competition**: Analyzes competitive dynamics between Chinese and Thai businesses
- **Consumer Behavior**: Examines shifts in Thai consumer preferences and spending patterns

### Sub-Branches 🍃

**Domestic Market Competition:**
- Price Undercutting: Effects on Thai producers and vulnerable sectors
- Market Share Losses: Displacement of local products and survival strategies
- Innovation and Quality Improvement: Need for innovation and R&D investments

**Consumer Behavior:**
- Demand for Cheaper Goods: Shifting preferences and impact on local brands
- Disposable Income and Spending Patterns: Changes in consumer purchasing power
- Brand Loyalty and Perception: Erosion of loyalty and perception of Chinese products

### Workflow Process ⚙️ 

1. Initial perspectives are generated for primary branches
2. Reflection is applied to these perspectives for refinement
3. Sub-branch analyses are created using the refined perspectives
4. Selected sub-branch outputs are combined
5. A final conclusion synthesizes all insights

## Case Study: Analysis of Chinese Price War Impact on Thailand's Economy

This project analyzes the question: **"What is the potential impact of Chinese price war on Thailand economy?"**

The analysis is structured as follows:

1. **Root Question**: The potential impact of Chinese price war on Thailand's economy
   
2. **Primary Branch #1: Domestic Market Competition**
   - Initial analysis of competitive dynamics
   - *Reflection applied*
   - Sub-branches analyze:
     - Price undercutting effects on Thai producers
     - Market share losses across different sectors
     - Innovation requirements to maintain competitiveness

3. **Primary Branch #2: Consumer Behavior**
   - Initial analysis of shifting consumer dynamics
   - *Reflection applied*
   - Sub-branches analyze:
     - Changes in demand for cheaper goods
     - Effects on disposable income and spending patterns
     - Impacts on brand loyalty and perception
  
4. **Conclusion Generation**: 
   - Selected sub-branch insights are aggregated
   - Comprehensive conclusion synthesizes all perspectives
   - Balanced assessment of positive and negative impacts

This structured approach allows for comprehensive analysis of complex economic dynamics from multiple angles while maintaining analytical rigor through reflection processes.

## ✅ Benefits 

- **Comprehensive Analysis**: Examines issues from multiple specialized perspectives
- **Enhanced Reasoning**: Reflection stages improve quality of analysis
- **Structured Approach**: Tree of Thought methodology provides clear organization
- **Customizable Depth**: Branches can be added or removed based on analytical needs
- **Developer Control**: Manual curation of which sub-branches to include in final analysis
- **Perspective Isolation**: Each perspective receives specialized prompt instructions
- **Improved Output Quality**: Reflection processes refine and enhance initial analyses

## 🚀 Applications

While the example implementation analyzes Chinese price war impacts on Thailand's economy, this framework can analyze any complex question requiring multi-perspective thinking, including:

- Economic policy analysis
- Market entry strategy development
- Competitive landscape assessment
- Social impact studies
- Risk analysis for investment decisions
- Policy consequence evaluation
  

## Project Structure 📁


```bash
.
├── agentic_workflow.py        # Core functions for ToT and reflection
├── main.py                    # Main script to run the analysis
├── README.md                  # Project documentation
└── requirements.txt           # Project dependencies
```


## Setup 🛠️

1. Clone this project to your repository:

2. Create Virtual Environment (optional but recommended)
```bash
python -m venv venv
```

3. Activate Virtual Environment (venv) or Select Python Interpreture 📦 
   
```bash
source venv/bin/activate  # On MacOS use this
venv\Scripts\activate     # On Windows use this 
```

4. Install dependencies ⬇️
```bash
pip install -r requirements.txt
```

5. Configure API key 🔑
   
###### Edit `main.py` with your API key

6. Run the analysis ▶️

```bash
python main.py
```
    

## Example Analysis & Output 📊

### Input Query:

**What is the potential impact of Chinese price war on Thailand economy?**


### Output Summary:

Based on comprehensive analysis through our Tree of Thought with Reflection methodology, here are the key conclusions about the potential impacts of a Chinese price war on Thailand's economy:

1. **Shifting brand loyalty**: There's likely to be a significant erosion of loyalty to Thai brands, especially in price-sensitive categories. This shift may be more pronounced among younger consumers and for non-essential goods.

2. **Evolving perception of Chinese products**: Initial skepticism about the quality of cheaper Chinese goods may give way to a more positive perception if these products prove to offer good value for money.

3. **Value redefinition**: The influx of lower-priced Chinese products may redefine what Thai consumers consider "good value," potentially setting new expectations across various product categories.

4. **Segmented impact**: The effects on brand loyalty and perception will likely vary across different consumer segments, product categories, and generations.

5. **Cultural influence**: Increased exposure to Chinese brands could extend beyond purchasing decisions to influence broader consumer trends and preferences in Thailand.

6. **Trust and safety concerns**: Initial worries about the safety and reliability of Chinese products may be a hurdle, particularly in sensitive categories like food and children's products.

7. **Nationalistic vs. pragmatic choices**: Some consumers may experience tension between supporting local brands out of national pride and the practical appeal of lower prices.

8. **Opportunity for brand reinvention**: Thai brands may need to emphasize qualities beyond price (e.g., local heritage, sustainability, customer service) to maintain consumer loyalty.

9. **Long-term perception changes**: The shift in brand loyalty and perception is likely to be gradual, influenced by factors such as product performance and government policies.

10. **Economic and cultural implications**: These changes in consumer behavior could have broader impacts on the Thai economy and potentially on cultural identity tied to local brands and products.

These conclusions suggest a complex and evolving landscape for consumer behavior in Thailand, with significant implications for both local and Chinese brands, as well as for the broader economic and cultural dynamics in the country.

