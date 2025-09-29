🧴Analysis of Chemical Components (Cosmetics Project)



📌 Project Overview

This project explores the chemical composition of cosmetic products and visualizes their similarity using machine learning techniques. By applying one-hot encoding and t-SNE (t-distributed stochastic neighbor embedding), I created a low-dimensional representation of cosmetic items, making it easier to compare products based on their ingredients.

🔧 What I Did

Imported and cleaned the dataset (cosmetics.csv).

Filtered the data for Moisturizers and specifically for those suitable for dry skin.

Preprocessed the ingredients:

Converted ingredient lists to lowercase.

Tokenized them into individual components.

Built a document-term matrix using one-hot encoding.

Applied t-SNE for dimensionality reduction to 2D space.

Created an interactive visualization with Bokeh to map cosmetic items:

Each point represents a product.

Products closer together share more similar chemical compositions.

Added hover tools to display product details and ingredients.

📊 What I Found

The t-SNE map grouped together products with similar formulations.

Items that appeared close on the map often shared key active ingredients.

Example: Color Control Cushion Compact SPF 50+ and BB Cushion Hydra Radiance SPF 50 appeared near each other because they share several similar moisturizing and sun-protective components.

🚀 Key Learnings

Gained hands-on experience with text tokenization, one-hot encoding, and document-term matrices.

Learned how t-SNE can be used for visualizing high-dimensional data.

Built an interactive visualization pipeline with Bokeh for better interpretability
