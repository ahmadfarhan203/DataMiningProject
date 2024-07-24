# DataMiningProject
Analysis of Extra Virgin Olive Oil Dataset with Decision Based Tree Classification
# Summary:
This project aims to analyze and classify virgin and organic olive oils. During the data collection phase, the chemical and physical properties of different olive oil types were examined. The collected data went through data cleaning and preprocessing stages. Subsequently, Decision Tree Classifier and Gaussian Mixture Model were used to classify the olive oils. The performance of the models was evaluated, and the results were able to accurately identify the significant differences between virgin and organic olive oils. This study aims to provide useful information to olive oil producers and consumers in determining the quality and type of products.

# Objective:
The primary objective of this project is to classify virgin and organic virgin olive oils based on their chemical components. The project aims to accurately identify and classify the types of olive oil. This classification process will play a crucial role in determining the quality of olive oils and in marketing strategies.

# Methods Used:

    Decision Tree Classifier: Decision trees classify data by splitting it into branches. In this project, decision trees were used to identify differences between types of olive oil.
    Gaussian Mixture Model (GMM): GMM classifies data by modeling it with normal distributions. The distribution of different types of olive oil was examined based on their chemical components.

# Methodology:
Dataset Information:
Initially, the dataset consists of the following columns:

    ID
    Region
    Area
    Palmitic (*)
    Palmitoleic (*)
    Stearic (*)
    Oleic (*)
    Linoleic (*)
    Linolenic (*)
    Arachidic (*)
    Eicosenoic (*)
    Other
    There are a total of 572 samples.

# Fatty Acids:
The areas marked with (*) in the dataset are fatty acids typically found in olive oil:

    Palmitic Acid: A saturated fatty acid, with no double bonds in the carbon chain. It constitutes approximately 7.5-20% of the total fatty acid content in olive oil.
    Palmitoleic Acid: A monounsaturated fatty acid, constituting about 0.3-3.5% of the total fatty acid content.
    Stearic Acid: A saturated fatty acid, constituting about 0.5-5% of the total fatty acid content.
    Oleic Acid: The most abundant fatty acid in olive oil, constituting about 55-83% of the total fatty acid content. It is a monounsaturated fatty acid.
    Linoleic Acid: A polyunsaturated fatty acid with two or more double bonds in the carbon chain, constituting about 3-21% of the total fatty acid content.
    Linolenic Acid: Another polyunsaturated fatty acid, constituting about 0.2-1.5% of the total fatty acid content.
    Arachidic Acid: A saturated fatty acid, constituting less than 1% of the total fatty acid content.
    Eicosenoic Acid: A monounsaturated fatty acid, constituting less than 1% of the total fatty acid content.
