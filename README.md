# Multi-relational Stacking Ensemble Recommender System using Cinematic Experience										

- Cheonsol Lee submitted short paper in [https://ieeexplore.ieee.org/abstract/document/9736528](https://ieeexplore.ieee.org/abstract/document/9736528), [Code](https://github.com/cheonsol-lee/bigcomp_2022_multi_graph)
- Reference code: [https://github.com/zhoujf620/Motif-based-inductive-GNN-training](https://github.com/zhoujf620/Motif-based-inductive-GNN-training)
- Author's Paper link: [https://arxiv.org/pdf/1706.02263v2.pdf](https://arxiv.org/pdf/1706.02263v2.pdf)
- Reference code: [https://github.com/zhoujf620/Motif-based-inductive-GNN-training](https://github.com/zhoujf620/Motif-based-inductive-GNN-training)


## Dependencies

* PyTorch 1.2+
* DGL 0.5 (nightly version)

## Data

Movie data
- Rotten Tomatoes data : [https://www.kaggle.com/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset](https://www.kaggle.com/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset)

Training set for BERT
- Sentiment Analysis : [https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews](https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews)
- Emotion Analysis : [https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp](https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp)


## How to run

- grid_search_final.ipynb


## Results

|Dataset|Our code <br> best of epochs|
|:-:|:-:|
|Rotten Tomatoes|0.8070|
