# Movie-Recommendation-System

The Movie Recommendation System recommends movies similar to a selected title using content-based filtering. It leverages textual data such as genres, cast, crew, and keywords to compute movie similarity, helping users discover new titles they may enjoy.

Project Insights :
1. Vectorization: Combined features (genre, cast, crew, keywords) into a single text field, and vectorized using CountVectorizer (Bag of Words).

2. Preprocessing:

    Removed duplicates and null values

    Parsed JSON fields from TMDB metadata

    Lowercased and stemmed keywords for normalization

3. Top Recommendations: Suggestions often included similar genres and actor collaborations, improving recommendation accuracy.

4. Limitations:

    Recommends similar movies, but not necessarily better ones
