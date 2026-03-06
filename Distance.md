---

## 1. Euclidean Distance (L2)

![Image](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/formula-of-euclidean-distance-1624039148.png)

![Image](https://study.com/cimages/multimages/16/2d_dist36bce0f6-0757-465d-bea9-864208c795ec.png)

![Image](https://upload.wikimedia.org/wikipedia/commons/5/55/Euclidean_distance_2d.svg)

![Image](https://cdn.prod.website-files.com/5ef788f07804fb7d78a4127a/623c68cda43982d04d80a752_Engati-Euclidean-distance%20%281%29.jpg)

**What it is**
Straight-line geometric distance between two vectors.

**Formula**

```
d = √Σ(xi − yi)²
```

**When to use**

* Continuous numeric features
* Data where magnitude matters

**Where used**

* KNN
* K-means clustering
* Computer vision

---

## 2. Squared Euclidean Distance

![Image](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/formula-of-euclidean-distance-1624039148.png)

![Image](https://www.researchgate.net/publication/8152781/figure/fig1/AS%3A601607607681065%401520445839960/Box-and-the-Euclidean-metrics-in.png)

![Image](https://images.contentstack.io/v3/assets/bltac01ee6daa3a1e14/bltbfd3d7e3452e01c7/65de3a8c6e7edb400cb4f753/img_blog_image2_inline.png?auto=webp\&disable=upscale\&width=1024)

![Image](https://www.maartengrootendorst.com/images/posts/2021-01-02-distances/header.png)

**What it is**
Euclidean distance without square root.

**Formula**

```
d = Σ(xi − yi)²
```

**When to use**

* When computation speed matters
* Optimization algorithms

**Where used**

* K-means objective function
* gradient optimization

---

## 3. Manhattan Distance (L1)

![Image](https://ars.els-cdn.com/content/image/3-s2.0-B9780128038185000093-f09-18-9780128038185.jpg)

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Manhattan_distance.svg/1280px-Manhattan_distance.svg.png)

![Image](https://uploads-cdn.omnicalculator.com/images/manhattan_distance.png?enlarge=0\&format=jpeg\&width=425)

![Image](https://upload.wikimedia.org/wikipedia/commons/0/08/Manhattan_distance.svg)

**What it is**
Distance moving only horizontally and vertically.

**Formula**

```
d = Σ |xi − yi|
```

**When to use**

* High dimensional data
* Sparse vectors

**Where used**

* Recommendation systems
* NLP sparse vectors

---

## 4. Minkowski Distance

![Image](https://www.researchgate.net/publication/349155159/figure/fig1/AS%3A989596292767746%401612949550717/Three-typical-Minkowski-distances-ie-Euclidean-Manhattan-and-Chebyshev-distances.png)

![Image](https://www.researchgate.net/publication/356201507/figure/fig4/AS%3A1104195264495618%401640272074166/Graphical-visualisation-of-different-L-p-norms-L-0-norms-which-is-not-a-norm-by.png)

![Image](https://www.researchgate.net/publication/38073005/figure/fig2/AS%3A216367547588655%401428597451677/Determination-of-optimal-p-values-for-Minkowski-distance.png)

![Image](https://iq.opengenus.org/content/images/2019/01/opengenus_minkowshi_distance.png)

**What it is**
Generalized distance function.

**Formula**

```
d = ( Σ |xi − yi|^p )^(1/p)
```

**When to use**

* When experimenting with different norms

**Where used**

* KNN distance selection

---

## 5. Chebyshev Distance

![Image](https://iq.opengenus.org/content/images/2018/12/distance.jpg)

![Image](https://miro.medium.com/v2/resize%3Afit%3A774/1%2AX8eikEPs0YcCCOuTMCuXeQ.png)

![Image](https://www.researchgate.net/publication/313830476/figure/fig10/AS%3A11431281286790624%401730149895451/Chebyshev-distances-on-a-two-dimensional-grid-The-Chebybshev-distances-from-point-0-0.tif)

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Minkowski_distance_examples.svg/250px-Minkowski_distance_examples.svg.png)

**What it is**
Maximum difference across dimensions.

**Formula**

```
d = max(|xi − yi|)
```

**When to use**

* Movement restricted to maximum step

**Where used**

* chess engines
* grid navigation

---

## 6. Cosine Distance

![Image](https://storage.googleapis.com/lds-media/images/cosine-similarity-vectors.original.jpg)

![Image](https://blogs.sas.com/content/iml/files/2019/08/cosSim1.png)

![Image](https://www.tigerdata.com/_next/image?q=75\&url=https%3A%2F%2Fimages.ctfassets.net%2Fnpizagvkn99r%2F2O5wFXxCUEZsSoxqWBpPG6%2Ff7e2b6c16fd5fc22a1730319687f8c53%2FCosine_Similarity_unrelated__opposite__similar.png%3Ffm%3Djpg%26fl%3Dprogressive\&w=1920)

![Image](https://www.researchgate.net/publication/329812352/figure/fig3/AS%3A941735651844135%401601538684893/Comparison-between-textual-visual-embedding-spaces-obtained-by-training-the-model-with.png)

**What it is**
Measures angle between vectors.

**Formula**

```
cos(θ) = (A·B) / (||A|| ||B||)
distance = 1 − cos(θ)
```

**When to use**

* When direction matters more than magnitude

**Where used**

* NLP embeddings
* semantic search
* vector databases

---

## 7. Correlation Distance

![Image](https://study.com/cimages/multimages/16/Pos-neg_correlation.PNG)

![Image](https://www.researchgate.net/publication/281144685/figure/fig1/AS%3A284493740036099%401444840001298/The-scatter-plot-of-cosine-similarity-x-axis-vs-our-measures-of-similarity-for-all.png)

![Image](https://ichef.bbci.co.uk/images/ic/1200xn/p0f9ffl0.png)

![Image](https://ichef.bbci.co.uk/images/ic/480x270/p0fc85br.png)

**What it is**
Measures linear relationship.

**Formula**

```
distance = 1 − correlation
```

**When to use**

* When scale differences exist

**Where used**

* time series
* gene expression analysis

---

## 8. Canberra Distance

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AFTVRr_Wqz-3_k6Mk6G4kew.png)

![Image](https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs44147-024-00535-2/MediaObjects/44147_2024_535_Fig11_HTML.png)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AUBVod31pjOcv41LJrBC7lg.jpeg)

![Image](https://ars.els-cdn.com/content/image/1-s2.0-S0031320323003473-gr8.jpg)

**What it is**
Weighted distance emphasizing small values.

**Formula**

```
d = Σ |xi − yi| / (|xi| + |yi|)
```

**When to use**

* Sparse data
* ecological measurements

**Where used**

* bioinformatics
* ecology

---

## 9. Bray–Curtis Distance

![Image](https://www.researchgate.net/publication/358810048/figure/fig3/AS%3A11431281180004824%401691466262416/Comparison-of-Bray-Curtis-dissimilarities-abundance-data-obtained-for-within-hour.png)

![Image](https://www.researchgate.net/publication/261292482/figure/fig2/AS%3A214137549398017%401428065778323/A-Bray-Curtis-distance-similarity-matrix-was-calculated-based-on-the-pairwise-taxonomic.png)

![Image](https://www.researchgate.net/publication/332372268/figure/fig2/AS%3A746861002518528%401555076947186/Ordination-of-the-Bray-Curtis-dissimilarity-matrix-for-all-022-mm-fraction-samples-A.png)

![Image](https://www.researchgate.net/publication/319855922/figure/fig4/AS%3A539703393951744%401505686724834/NMDS-visualizations-of-beta-diversity-analysis-using-the-Bray-Curtis-metric-separating.png)

**What it is**
Measures dissimilarity between compositions.

**Formula**

```
d = Σ|xi − yi| / Σ(xi + yi)
```

**When to use**

* proportional data

**Where used**

* ecology
* environmental science

---

## 10. Mahalanobis Distance

![Image](https://blogs.sas.com/content/iml/files/2012/02/mahal.png)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AGtfO1qTWSMP00msR6uQVlA.png)

![Image](https://www.researchgate.net/publication/372404218/figure/fig2/AS%3A11431281175041110%401689563542785/Threshold-estimation-The-relative-Mahalanobis-distance-map-is-first-calculated-and-its.png)

**What it is**
Distance considering feature correlation.

**Formula**

```
d = √((x − μ)^T S⁻¹ (x − μ))
```

**When to use**

* correlated features

**Where used**

* anomaly detection
* multivariate statistics

---

## 11. Hamming Distance

![Image](https://upload.wikimedia.org/wikipedia/commons/b/bf/Hamming_distance_4_bit_binary.svg)

![Image](https://miro.medium.com/0%2ATZDsUKARxXly8nHR.png)

![Image](https://i.sstatic.net/4QxEO.png)

![Image](https://gateoverflow.in/?qa=blob\&qa_blobid=7616886882799752356)

**What it is**
Counts differing positions.

**Formula**

```
d = number of positions where xi ≠ yi
```

**When to use**

* binary data

**Where used**

* coding theory
* error detection

---

## 12. Jaccard Distance

![Image](https://www.researchgate.net/publication/359408000/figure/fig4/AS%3A1136725929795588%401648027989296/enn-diagram-showing-Jaccard-similarity-indexes-and-overlap-of-frequently-reported-wild.png)

![Image](https://miro.medium.com/1%2AXiLRKr_Bo-VdgqVI-SvSQg.png)

![Image](https://storage.googleapis.com/lds-media/images/jaccard_similarity.width-1200.jpg)

![Image](https://www.researchgate.net/publication/363760835/figure/fig5/AS%3A11431281278807852%401726762988848/A-visualization-of-the-Jaccard-index-or-Intersection-over-Union-IoU-The-two-ellipses.png)

**What it is**
Measures similarity between sets.

**Formula**

```
J = |A ∩ B| / |A ∪ B|
distance = 1 − J
```

**When to use**

* set comparison

**Where used**

* document similarity
* recommendation

---

## 13. Dice Distance

![Image](https://miro.medium.com/v2/resize%3Afit%3A1168/1%2AvbO6lIOpn0CVOcHiCWETgQ.png)

![Image](https://www.researchgate.net/publication/360537157/figure/fig2/AS%3A1159300701519879%401653410234632/A-Sorensen-Dice-similarity-coefficient-DICE-and-B-mean-symmetric-surface-distance.png)

![Image](https://www.researchgate.net/publication/360274971/figure/fig3/AS%3A11431281213081241%401702956528094/Calculation-of-segmentation-quality-metrics-Dice-similarity-coefficient-a-and.tif)

![Image](https://www.researchgate.net/publication/361107322/figure/fig5/AS%3A1163842784636929%401654493151527/Most-commonly-used-overlap-based-segmentation-metrics-a-the-Dice-Similarity.png)

**What it is**
Another set similarity measure.

**Formula**

```
Dice = 2|A∩B| / (|A| + |B|)
```

**When to use**

* text similarity

**Where used**

* NLP
* image segmentation

---

## 14. Rogers–Tanimoto Distance

![Image](https://www.researchgate.net/publication/238340755/figure/fig1/AS%3A298791514198018%401448248856339/Binary-vectors-A-schematic-representation-of-the-binary-vectors-employed-in-this-work-as.png)

![Image](https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs13321-015-0069-3/MediaObjects/13321_2015_69_Fig1_HTML.gif)

![Image](https://www.researchgate.net/publication/40846565/figure/fig6/AS%3A282026340044802%401444251727106/Example-calculation-of-Tanimoto-coefficient-Example-of-calculation-of-the-Tanimoto.png)

![Image](https://media.springernature.com/lw1200/springer-static/image/art%3A10.1186%2Fs13321-018-0302-y/MediaObjects/13321_2018_302_Figa_HTML.png)

**What it is**
Binary similarity measure penalizing mismatches.

**Formula**

```
d = 2(b + c) / (a + 2(b + c) + d)
```

**When to use**

* binary attributes

**Where used**

* pattern recognition

---

## 15. Russell–Rao Distance

![Image](https://www.researchgate.net/publication/221569940/figure/fig3/AS%3A394057076494348%401470961936814/Average-MoJoFM-using-JaccardJ-Jaccard-NMJNM-and-Russell-RaoRR.png)

![Image](https://i.sstatic.net/L5o4Y.png)

![Image](https://media.springernature.com/m685/springer-static/image/art%3A10.1038%2Fs43247-025-02309-x/MediaObjects/43247_2025_2309_Fig1_HTML.png)

![Image](https://www.jacc.org/cms/asset/edf5f107-d10b-448b-9290-cf73dfcddb04/ga1.jpg)

**What it is**
Measures shared positive features.

**Formula**

```
distance = (n − a) / n
```

**When to use**

* binary feature datasets

**Where used**

* pattern recognition

---

## 16. KL Divergence

![Image](https://images.squarespace-cdn.com/content/v1/54e50c15e4b058fc6806d068/1494398217552-EC6J4VA3MU2PZKI4UKKM/optimizing-our-ad-hoc-function.png)

![Image](https://www.researchgate.net/publication/376424825/figure/fig4/AS%3A11431281233605257%401712075757087/KL-divergence-comparison-among-four-generated-trajectory-datasets-and-the-original.ppm)

![Image](https://www.researchgate.net/publication/349283782/figure/fig2/AS%3A990741849444355%401613222672730/sual-representation-of-the-Kullback-Leibler-divergence-The-dashed-line-corresponds-to.ppm)

![Image](https://datumorphism.leima.is/wiki/machine-learning/basics/assets/kl-divergence/two-gaussians.png)

**What it is**
Difference between probability distributions.

**Formula**

```
KL(P||Q) = Σ P(x) log(P(x)/Q(x))
```

**When to use**

* comparing distributions

**Where used**

* language models
* VAEs

---

## 17. Jensen–Shannon Distance

![Image](https://www.researchgate.net/publication/24304762/figure/fig3/AS%3A669496750657564%401536631872958/The-Jensen-Shannon-divergence-z-red-solid-curve-as-a-function-of-the-normalized.png)

![Image](https://www.researchgate.net/publication/350070173/figure/fig3/AS%3A11431281390396105%401745266065830/JS-divergence-vs-KL-divergence.tif)

![Image](https://www.researchgate.net/publication/24304762/figure/fig8/AS%3A669496754839552%401536631873031/The-Jensen-Shannon-divergence-z-solid-curve-of-a-pair-of-sliding-windows-of-length-n.png)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AWdGwh4qFm3tXQn2DRftdnA.png)

**What it is**
Symmetric KL divergence.

**Formula**

```
JS(P,Q) = ½ KL(P||M) + ½ KL(Q||M)
```

**When to use**

* stable distribution comparison

**Where used**

* topic modeling

---

## 18. Wasserstein Distance

![Image](https://media.licdn.com/dms/image/v2/D4D22AQFD5dreT6UcCA/feedshare-shrink_800/B4DZUjTB9jGcAo-/0/1740053946819?e=2147483647\&t=P2myzWXuxdeWPkGnw9sQYFwU-TiTANEeY5UaD-Da-7c\&v=beta)

![Image](https://www.jeremykun.com/img/2018/screen-shot-2018-03-03-at-6-11-00-pm.png)

![Image](https://alexhwilliams.info/itsneuronalblog/code/ot/example_1d_transport_plan.png)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AhAyXrelK7JEDV8mimoOspg.png)

**What it is**
Cost to move probability mass.

**Formula**

Conceptually:

```
minimum cost to transform distribution P to Q
```

**When to use**

* generative model evaluation

**Where used**

* GANs
* optimal transport

---

## 19. Levenshtein Distance

![Image](https://www.clear.rice.edu/comp130/12spring/editdist/distance_matrix_ex2.png)

![Image](https://www.ideserve.co.in/learn/img/editDistance_0.gif)

![Image](https://uipath.com/cdn-cgi/image/format%3Dauto/https%3A//marketplace-cdn.uipath.com/images/user_images/7be7477a-e38e-4b1c-9497-bb0b8433994b.jpg)

![Image](https://devopedia.org/images/article/213/5510.1567535069.svg)

**What it is**
Minimum edits between strings.

**Formula**

```
min(insert, delete, replace)
```

**When to use**

* string similarity

**Where used**

* spell checking
* search engines

---

## 20. Jaro–Winkler Distance

![Image](https://www.researchgate.net/publication/316681173/figure/fig2/AS%3A534810407575552%401504520145083/Jaro-Winkler-Distance-Algorithm.png)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AxC3MqiB1Sv1zAi5JA075ew.jpeg)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2A0efk-HIrKHqv_uimWWwhDQ.jpeg)

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2Aeyki8Hy6OAZenY3sJPw3Tg.jpeg)

**What it is**
Improved string similarity for short text.

**Formula**

Based on matching characters and prefix bonus.

**When to use**

* name matching

**Where used**

* record linkage
* data deduplication

---
