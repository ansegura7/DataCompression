# Data Compression
Project in which we explore different algorithms and compression approaches such as Huffman coding or entropy change. The distribution of the symbols of the compressed files (image, electronic book, etc.) is also analyzed.

## Example
<details open>
<summary>1. <a href="https://ansegura7.github.io/DataCompression/pages/SymbolsDistribution.html" >Symbols Distribution</a></summary>
<ul>
	<li>Bytes Distribution</li>
	<li>Entropy</li>
</ul>
</details>
<details>
<summary>2. <a href="https://ansegura7.github.io/DataCompression/pages/TextCompression.html" >Text Compression</a></summary>
<ul>
	<li>NPL Preprocessing Approach</li>
    <li>Semantic Compression</li>
</ul>
</details>
<details>
<summary>3. <a href="https://ansegura7.github.io/DataCompression/pages/HuffmanCode.html" >File Compression</a></summary>
<ul>
	<li>Huffman Code from Scratch</li>
	<li>Compress Image with Huffman Code</li>
	<li>Compress Text file with Huffman Code</li>
	<li>Decompress file with Huffman Code</li>
</ul>
</details>
<details>
<summary>4. <a href="https://ansegura7.github.io/DataCompression/pages/CompressionAndEntropy.html" >Compression & Entropy</a></summary>
<ul>
	<li>Compression with current Entropy</li>
	<li>Changing Entropy for higher Compression</li>
	<li>Restoring Entropy to Decompression</li>
</ul>
</details>

## Data
PNG images and plain textbook of different sizes and different languages (English and Spanish).

## Python Dependencies
```
    import io
    import math
    import timeit
    import numpy as np
    import pandas as pd
    from collections import Counter
    from PIL import Image
    from scipy.stats import entropy
    import seaborn as sns
    import matplotlib.pyplot as plt
```

## Contributing and Feedback
Any kind of feedback/criticism would be greatly appreciated (algorithm design, documentation, improvement ideas, spelling mistakes, etc...).

## Authors
- Created by Andrés Segura Tinoco
- Created on June 17, 2019

## License
This project is licensed under the terms of the MIT license.
