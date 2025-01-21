# ALP Matematika Diskrit - Implementasi Teori Graf Menggunakan Python
1. Tujuan
- Kode ini dibuat untuk mempermudah Anda membuat graf (graph), menambahkan simpul (node) dan sisi (edge), memvisualisasikan hubungan antar node, serta menghitung berbagai properti graf seperti jalur terpendek, sentralitas, dan lain-lain.
---
2. Syarat menjalankan kode
Sebelum menjalankan kode ini, pastikan Anda memiliki Python dan dua pustaka berikut yang diinstal:
- `networkx`
- `matplotlib`
Untuk menginstalnya, gunakan perintah:
```bash
pip install networkx matplotlib
```
---
3. Langkah menjalankan kode:
- Salin kode ke dalam file Python, misalnya `graf.py`
- Jalankan file tersebut menggunakan perintah:
```bash
python graf.py
```
- Hasil akan ditampilkan di terminal, dan graf akan divisualisasikan melalui jendela matplotlib.
---
4. Fitur-fitur
- Fitur utama
- Menambahkan Simpul dan Sisi:
Menambah simpul (node) dan sisi (edge) dengan bobot (weight) tertentu.
- Visualisasi Graf:
Graf akan divisualisasikan dengan simpul dan sisi yang terhubung.
- Menemukan Jalur Terpendek:
Jalur terpendek antara dua simpul akan ditampilkan dan divisualisasikan.
- Fitur tambahan
- Menghitung Properti Graf:
Seperti sentralitas, koefisien klaster, diameter graf, komponen terhubung, dan lain-lain.
---
5. Penjelasan function
- Fitur utama
- `add_node(node)` - Menambah simpul ke graf. Contoh: `graf.add_node(1)`
- `add_edge(node1, node2, weight=None)` - Menambah sisi dengan bobot antara dua simpul. Contoh: `graph.add_edge(1, 2, weight=4.5)`
- `visualize_graph()` - Menampilkan graf dengan simpul dan sisi.
- `shortest_path(source, target)` - Menghitung jalur terpendek dari simpul awal ke simpul tujuan.
- `visual_shortest_path(start, end)` - Menampilkan jalur terpendek di graf dengan warna khusus (misalnya merah).
- Fitur tambahan
- `degree_centrality()` - Menghitung derajat sentralitas setiap simpul (pentingnya simpul dalam graf).
- `clustering_coefficient()` - Menghitung koefisien klaster untuk mengetahui tingkat hubungan antar simpul.
- `graph_diameter()` - Menghitung diameter graf, yaitu jarak terjauh antar simpul.
- `connected_components()` - Menampilkan kelompok simpul yang saling terhubung dalam graf.
--- 
6. Contoh Output
- Fitur utama
- `add_node(node)`
- Output: No output, but the graph will now contain the specified node.
- `add_edge(node1, node2, weight=None)`
- Output: No output, but the graph will now contain the specified edge with the weight.
- `visualize_graph()`
- Output: A plot showing all nodes and edges of the graph.
- `shortest_path(source, target)`
- Output:
```plaintext
[1, 3, 5] (if such a path exists).
```
- `visual_shortest_path(start, end)`
- Output: A plot showing the graph with the shortest path highlighted in red.
- Fitur tambahan
- `degree_centrality()`
- Output:
```plaintext
{1: 0.75, 2: 0.5, 3: 0.75, 4: 0.5, 5: 0.25}
```
- `clustering_coefficient()`
- Output:
```plaintext
{1: 0.333, 2: 0, 3: 0.333, 4: 0, 5: 0}
```
- `graph_diameter()`
- Output:
```plaintext
3 (if the graph is connected).
```
- `connected_components()`
- Output:
```plaintext
[[1, 2, 3, 4, 5]] (if all nodes are connected).
```
--- 
7. Kesimpulan
- Kode ini adalah alat yang efektif untuk menganalisis graf secara visual dan numerik. Dengan fitur yang disediakan, dapat membantu untuk lebih mudah dalam memahami struktur graf, memvisualisasikan jalur, dan menghitung berbagai metrik penting dengan mudah dengan menggunakan bahasa pemrograman Python.






