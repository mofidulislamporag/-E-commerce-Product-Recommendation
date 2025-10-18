# E-commerce Product Recommendation System

A comprehensive product recommendation system using Association Rule Mining and Deep Learning (Autoencoders) to provide personalized recommendations for e-commerce customers.

## 📋 Project Overview

This project implements multiple recommendation algorithms to suggest products to users based on their demographics, behavior, and purchase history. The system combines traditional association rule mining with modern deep learning techniques to create a robust hybrid recommendation engine.

## 🚀 Features

- **Association Rule Mining**: Discover patterns in customer behavior using Apriori algorithm
- **Deep Learning Autoencoder**: Learn user embeddings for similarity-based recommendations
- **Collaborative Filtering**: Recommend based on similar users' preferences
- **Hybrid Recommendation**: Combine multiple approaches for improved accuracy
- **Business Insights**: Analyze customer segments and purchasing patterns
- **Model Evaluation**: Compare different recommendation strategies

## 📊 Dataset

The project uses a Kaggle synthetic e-commerce dataset containing:
- **1,000 users** with detailed profiles
- **Demographic information**: Age, Gender, Location, Income
- **Behavioral data**: Purchase frequency, Time spent on site, Pages viewed
- **Purchase history**: Total spending, Average order value, Product category preferences
- **Interests**: User interests and preferences



### Key Sections

1. **Data Exploration**: Understand the dataset and distributions
2. **Association Rule Mining**: Generate customer behavior patterns
3. **Deep Learning**: Build and train autoencoder for user embeddings
4. **Collaborative Filtering**: Implement user similarity recommendations
5. **Hybrid System**: Combine multiple approaches
6. **Evaluation**: Compare recommendation accuracy
7. **Business Insights**: Extract actionable findings

## 🔧 Algorithms Implemented

### 1. Association Rule Mining
- **Algorithm**: Apriori
- **Purpose**: Discover frequent itemsets and association rules
- **Metrics**: Support, Confidence, Lift
- **Output**: Customer behavior patterns and product associations

### 2. Deep Learning Autoencoder
- **Architecture**: Encoder-Decoder with dropout layers
- **Layers**: Input(11) → Dense(128) → Dense(64) → Embedding(32) → Dense(64) → Dense(128) → Output(11)
- **Purpose**: Learn compressed user representations
- **Training**: 100 epochs with early stopping

### 3. Collaborative Filtering
- **Approach**: User-based collaborative filtering
- **Similarity Metric**: Cosine similarity on user embeddings
- **Recommendation**: Based on similar users' preferences

### 4. Hybrid Recommendation
- **Combination**: Weighted average of association rules and collaborative filtering
- **Weights**: 70% association rules, 30% collaborative filtering
- **Advantage**: Leverages both behavioral patterns and user similarities

## 📈 Results

### Recommendation Accuracy
| Method | Accuracy | Description |
|--------|----------|-------------|
| Collaborative Filtering | ~00% | Based on user similarity |
| Hybrid Approach | ~60% | Combined methods |

### Key Findings
- **High-value customers** tend to prefer Electronics and Apparel
- **Urban users** show higher spending patterns
- **Technology enthusiasts** frequently purchase Electronics
- **Strong associations** between user demographics and product preferences

## 💡 Business Applications

1. **Personalized Marketing**: Target users with relevant product recommendations
2. **Customer Segmentation**: Identify high-value customer groups
3. **Inventory Planning**: Stock products based on predicted demand
4. **User Engagement**: Improve customer experience with tailored suggestions
5. **Sales Optimization**: Increase conversion rates through relevant recommendations



## 📊 Visualizations

The project includes comprehensive visualizations:
- Customer demographic distributions
- Purchase behavior patterns
- Association rule analysis
- Model training progress
- Recommendation accuracy comparisons
- Business insights dashboards

## 🔮 Future Enhancements

- [ ] Real-time recommendation API
- [ ] Integration with actual e-commerce platform
- [ ] A/B testing framework
- [ ] Additional deep learning models (RNN, Transformer)
- [ ] Multi-modal recommendations (images, text)
- [ ] Explainable AI for recommendations

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:

- Bug fixes
- New features
- Performance improvements
- Additional algorithms
- Documentation enhancements



## 🙏 Acknowledgments

- Dataset inspired by real e-commerce patterns
- MLxtend library for association rule mining
- TensorFlow/Keras for deep learning implementation
- Scikit-learn for machine learning utilities

## 📞 Contact

For questions or suggestions, please contact:
- **Md Mafidul Islam** - [mofidulislamporag@gmail.com]

**⭐ Don't forget to star this repository if you find it helpful!**
