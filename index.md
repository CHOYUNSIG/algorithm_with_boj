---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
banner:
    image: "/assets/images/banners/home.jpeg"
---

## 1. 패러다임

<pre class="mermaid">
    graph LR
    
    Paradigm --> #divide_and_conquer
    Paradigm --> #dp
    Paradigm --> #bruteforcing
    Paradigm --> #greedy
    #bruteforcing --> #backtracking

    #backtracking[#백트래킹]
    #bruteforcing[#브루트포스 알고리즘]
    #divide_and_conquer[#분할 정복]
    #dp[#다이나믹 프로그래밍]
    #greedy[#그리디 알고리즘]
</pre>

<br>

## 2. 자료구조

<pre class="mermaid">
    graph LR

    #data_structures --> Linear
    #data_structures --> Non-Linear
    Linear --> Array
    Linear --> #linked_list
    Array --> #stack
    Array --> #queue
    Array --> #string
    #queue --> #deque
    Non-Linear--> #trees
    Non-Linear --> #graphs
    Non-Linear --> #linked_list
    #trees --> #priority_queue
    #trees --> #tree_set
    #trees --> #segtree
    #hashing --> #hash_set

    #data_structures[#자료 구조]
    #deque[#덱]
    #graphs[#그래프 이론]
    #hash_set[#해시를 사용한 집합과 맵]
    #hashing[#해싱]
    #linked_list[#연결 리스트]
    #priority_queue[#우선순위 큐]
    #queue[#큐]
    #segtree[<a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>]
    #stack[#스택]
    #string[#문자열]
    #tree_set[#트리를 사용한 집합과 맵]
    #trees[#트리]
</pre>

<br>

## 3. 알고리즘

### 3-0. 기초

<pre class="mermaid">
    graph LR

    #sorting --> #binary_search
    #graph_traversal --> #bfs
    #graph_traversal --> #dfs
    #recursion --> #dfs

    #bfs[#너비 우선 탐색]
    #binary_search[#이분 탐색]
    #dfs[#깊이 우선 탐색]
    #graph_traversal[#그래프 탐색]
    #recursion[#재귀]
    #sorting[#정렬]
</pre>

### 3-1. 수학

<pre class="mermaid">
    graph LR

    #math --> #number_theory
    #math --> #linear_algebra
    #math --> #game_theory
    #math --> #geometry
    #math --> #calculus
    #math --> #combinatorics
    #number_theory --> #primality_test
    #number_theory --> #euclidean
    #number_theory --> #crt
    #number_theory --> #euler_phi
    #number_theory --> #modular_multiplicative_inverse
    #primality_test --> #sieve
    #primality_test --> #miller_rabin
    #modular_multiplicative_inverse --> #flt
    #flt --> #miller_rabin
    #euclidean --> #pollard_rho
    #euclidean --> #extended_euclidean
    #miller_rabin --> #pollard_rho
    #geometry --> CCW
    #geometry --> #sweeping
    CCW --> #line_intersection
    CCW --> #convex_hull
    #convex_hull --> #rotating_calipers
    #linear_algebra --> #gaussian_elimination
    #game_theory --> #sprague_grundy
    #calculus --> #fft

    #calculus[#미적분학]
    #combinatorics[#조합론]
    #convex_hull[#볼록 껍질]
    #crt[#중국인의 나머지 정리]
    #euclidean[#유클리드 호제법]
    #euler_phi[#오일러 피 함수]
    #extended_euclidean[#확장 유클리드 호제법]
    #fft[#고속 푸리에 변환]
    #flt[#페르마의 소정리]
    #game_theory[#게임 이론]
    #gaussian_elimination[#가우스 소거법]
    #geometry[#기하학]
    #line_intersection[#선분 교차 판정]
    #linear_algebra[#선형대수학]
    #math[#수학]
    #miller_rabin[#밀러–라빈 소수 판별법]
    #modular_multiplicative_inverse[#모듈로 곱셈 역원]
    #number_theory[#정수론]
    #pollard_rho[#폴라드 로]
    #primality_test[#소수 판정]
    #rotating_calipers[#회전하는 캘리퍼스]
    #sieve[#에라토스테네스의 체]
    #sprague_grundy[#스프라그–그런디 정리]
    #sweeping[#스위핑]
</pre>

### 3-2. 트리

<pre class="mermaid">
    graph LR

    #trees --> #graph_traversal
    #trees --> BST
    #trees --> #priority_queue
    #trees --> #trie
    #trees --> #segtree
    #trees --> #euler_tour_technique
    #trees --> #disjoint_set
    #trees --> #lca
    #trees --> #centroid
    #centroid --> #centroid_decomposition
    BST --> #splay_tree
    BST --> #rb_tree
    #euler_tour_technique --> #hld
    #segtree --> Fenwick
    #segtree --> #merge_sort_tree
    #segtree --> #lazyprop
    #segtree --> #pst
    #segtree --> #hld

    #centroid[#센트로이드]
    #centroid_decomposition[#센트로이드 분할]
    #disjoint_set[<a href="post/2024/01/13/disjoint_set.html">#분리 집합</a>]
    #euler_tour_technique[#오일러 경로 테크닉]
    #graph_traversal[#그래프 탐색]
    #hld[#Heavy-light 분할]
    #lazyprop[#느리게 갱신되는 세그먼트 트리]
    #lca[#최소 공통 조상]
    #merge_sort_tree[#머지 소트 트리]
    #pst[#퍼시스턴트 세그먼트 트리]
    #rb_tree[#레드-블랙 트리]
    #segtree[<a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>]
    #splay_tree[#스플레이 트리]
    #priority_queue[#우선순위 큐]
    #trees[#트리]
    #trie[<a href="post/2024/01/03/trie.html">#트라이</a>]
</pre>

### 3-3. 그래프

<pre class="mermaid">
    graph LR

    #graphs --> #graph_traversal
    #graphs --> #shortest_path
    #graphs --> #flow
    #graphs --> #bipartite_graph
    #graphs --> #scc
    #graphs --> #articulation
    #articulation --> #biconnected_component
    #graphs --> #mst
    #graphs --> #tsp
    #graphs --> #topological_sorting
    #articulation --> #cactus
    #shortest_path --> #dijkstra
    #shortest_path --> #bellman_ford
    #shortest_path --> #floyd_warshall
    #flow --> Edmond-Karp
    #flow --> Ford-Fulkerson
    #flow --> Dinic
    #flow --> #mcmf
    #mcmf <--> #mfmc
    #flow --> #bipartite_matching
    #bipartite_graph --> #bipartite_matching
    #scc --> #2_sat
    #mst --> Kruskal
    #mst --> Prim

    #2_sat[#2-sat]
    #articulation[#단절점과 단절선]
    #bellman_ford[<a href="post/2024/01/07/bellman_ford.html">#벨만–포드</a>]
    #biconnected_component[#이중 연결 요소]
    #bipartite_graph[#이분 그래프]
    #bipartite_matching[#이분 매칭]
    #cactus[#선인장]
    #dijkstra[<a href="post/2024/01/01/dijkstra.html">#데이크스트라</a>]
    #flow[#최대 유량]
    #floyd_warshall[<a href="post/2024/01/07/floyd_warshall.html">#플로이드–워셜</a>]
    #graph_traversal[#그래프 탐색]
    #graphs[#그래프 이론]
    #mcmf[#최소 비용 최대 유량]
    #mfmc[#최대 유량 최소 컷 정리]
    #mst[#최소 스패닝 트리]
    #scc[#강한 연결 요소]
    #shortest_path[#최단 경로]
    #topological_sorting[#위상 정렬]
    #tsp[#외판원 순회 문제]
</pre>

### 3-4. 문자열

<pre class="mermaid">
    graph LR

    #string --> #parsing
    #string --> #kmp
    #string --> #trie
    #string --> #manacher
    #string --> #rabin_karp
    #string --> #suffix_array
    #trie --> #aho_corasick

    #aho_corasick[#아호-코라식]
    #kmp[#KMP]
    #manacher[#매내처]
    #parsing[#파싱]
    #rabin_karp[#라빈–카프]
    #string[#문자열]
    #suffix_array[#접미사 배열과 LCP 배열]
    #trie[<a href="post/2024/01/03/trie.html">#트라이</a>]
</pre>

### 3-5. 오프라인 쿼리

<pre class="mermaid">
    graph LR

    #offline_queries --> #sqrt_decomposition
    #offline_queries --> Kadane's_algorithm
    #offline_queries --> #prefix_sum
    #offline_queries --> #two_pointer
    #two_pointer --> #mo
    #two_pointer --> #sliding_window
    #two_pointer --> #mitm

    #mitm[#중간에서 만나기]
    #mo[#mo's]
    #offline_queries[#오프라인 쿼리]
    #prefix_sum[#누적 합]
    #sliding_window[#슬라이딩 윈도우]
    #sqrt_decomposition[#제곱근 분할법]
    #two_pointer[#두 포인터]
</pre>

### 3-6. DP

<pre class="mermaid">
    graph LR

    #dp --> #knapsack
    #dp --> Recurrence_Relation
    #dp --> #dp_bitfield
    #dp --> #dp_deque
    #dp_deque --> #deque_trick
    #dp --> #dp_tree
    Recurrence_Relation --> #cht
    Recurrence_Relation --> #divide_and_conquer_optimization
    Recurrence_Relation --> #monotone_queue_optimization
    Recurrence_Relation --> #knuth
    Recurrence_Relation --> #kitamasa
    Recurrence_Relation --> #alien
    Recurrence_Relation --> #hirschberg

    #alien[#Aliens 트릭]
    #cht[#볼록 껍질을 이용한 최적화]
    #deque_trick[#덱을 이용한 구간 최댓값 트릭]
    #divide_and_conquer_optimization[#분할 정복을 사용한 최적화]
    #dp[#다이나믹 프로그래밍]
    #dp_bitfield[#비트필드를 이용한 다이나믹 프로그래밍]
    #dp_deque[#덱을 이용한 다이나믹 프로그래밍]
    #dp_tree[#트리에서의 다이나믹 프로그래밍]
    #hirschberg[#히르쉬버그]
    #kitamasa[#키타마사]
    #knapsack[#배낭 문제]
    #knuth[#크누스 최적화]
    #monotone_queue_optimization[#단조 큐를 이용한 최적화]
</pre>