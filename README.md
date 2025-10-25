🤖 TASK 4: AI Recommendation System

An intelligent movie recommendation engine implementing collaborative filtering algorithms to suggest content based on user preferences.

 🚀 Features
- User-Based Filtering - Personalized recommendations
- Rating Analysis- Pattern recognition in user ratings
- Similarity Scoring - Cosine similarity algorithms
- Multi-user Support - Handles multiple user profiles
- Real-time Suggestions - Instant recommendation generation

 💻 Tech Stack
- Java 8+
- Custom recommendation algorithms
- Data structure optimization
- Statistical analysis

 📊 Sample Data Structure
java
User1: Movie1=5.0, Movie2=3.0, Movie3=4.5
User2: Movie1=4.0, Movie2=2.0, Movie4=3.5
User3: Movie2=4.0, Movie4=4.5, Movie5=5.0

DEMO OUTPUT

AI RECOMMENDATION SYSTEM - TASK 4
=================================
RECOMMENDATIONS:
• User1 → Movie4, Movie5 (85% match)
• User2 → Movie3, Movie5 (78% match) 
• User3 → Movie1, Movie3 (82% match)
USAGE
SimpleRecommender.generateForUser(1);
SimpleRecommender.showAllRecommendations();
