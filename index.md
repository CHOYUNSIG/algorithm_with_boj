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
    Paradigm --> #heuristics
    #bruteforcing --> #backtracking

    #greedy[#그리디 알고리즘]
    #dp[#다이나믹 프로그래밍]
    #backtracking[#백트래킹]
    #divide_and_conquer[#분할 정복]
    #bruteforcing[#브루트포스 알고리즘]
    #heuristics[#휴리스틱]
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

    #graphs[#그래프 이론]
    #deque[#덱]
    #string[#문자열]
    #segtree[<a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>]
    #stack[#스택]
    #linked_list[#연결 리스트]
    #priority_queue[<a href="post/2024/01/15/priority_queue.html">#우선순위 큐</a>]
    #data_structures[#자료 구조]
    #queue[#큐]
    #trees[#트리]
    #tree_set[#트리를 사용한 집합과 맵]
    #hash_set[#해시를 사용한 집합과 맵]
    #hashing[#해싱]
</pre>

<br>

## 3. 알고리즘

### 3-0. 기초

<pre class="mermaid">
    graph LR

    #sorting --> #binary_search
    #binary_search --> #parametric_search
    #graph_traversal --> #bfs
    #graph_traversal --> #dfs
    #recursion --> #dfs

    #graph_traversal[#그래프 탐색]
    #dfs[#깊이 우선 탐색]
    #bfs[#너비 우선 탐색]
    #parametric_search[#매개 변수 탐색]
    #binary_search[#이분 탐색]
    #recursion[#재귀]
    #sorting[#정렬]
</pre>

### 3-1. 트리

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
    #lca --> #link_cut_tree
    #disjoint_set --> #smaller_to_larger
    #centroid --> #centroid_decomposition
    BST --> #splay_tree
    BST --> #rb_tree
    #splay_tree --> #link_cut_tree
    #euler_tour_technique --> #hld
    #segtree --> #merge_sort_tree
    #segtree --> #lazyprop
    #segtree --> #pst
    #segtree --> #multi_segtree
    #segtree --> #hld
    #lazyprop --> #link_cut_tree

    #hld[#Heavy-light 분할]
    #graph_traversal[#그래프 탐색]
    #lazyprop[#느리게 갱신되는 세그먼트 트리]
    #multi_segtree[#다차원 세그먼트 트리]
    #rb_tree[#레드-블랙 트리]
    #link_cut_tree[#링크/컷 트리]
    #merge_sort_tree[#머지 소트 트리]
    #disjoint_set[<a href="post/2024/01/13/disjoint_set.html">#분리 집합</a>]
    #segtree[<a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>]
    #centroid[#센트로이드]
    #centroid_decomposition[#센트로이드 분할]
    #splay_tree[#스플레이 트리]
    #euler_tour_technique[#오일러 경로 테크닉]
    #priority_queue[<a href="post/2024/01/15/priority_queue.html">#우선순위 큐</a>]
    #smaller_to_larger[#작은 집합에서 큰 집합으로 합치는 테크닉]
    #lca[#최소 공통 조상]
    #trie[<a href="post/2024/01/03/trie.html">#트라이</a>]
    #trees[#트리]
    #pst[#퍼시스턴트 세그먼트 트리]
</pre>

### 3-2. 그래프

<pre class="mermaid">
    graph LR

    #graphs --> #graph_traversal
    #graphs --> #shortest_path
    #graphs --> #flow
    #graphs --> #bipartite_graph
    #graphs --> #general_matching
    #graphs --> #scc
    #graphs --> #articulation
    #graphs --> #mst
    #graphs --> #tsp
    #graphs --> #dag
    #graph_traversal --> #flood_fill
    #general_matching --> #bipartite_matching
    #articulation --> #biconnected_component
    #articulation --> #cactus
    #shortest_path --> #dijkstra
    #shortest_path --> #bellman_ford
    #shortest_path --> #floyd_warshall
    #flow --> #mcmf
    #flow --> #mfmc
    #flow --> #circulation
    #flow --> #bipartite_matching
    #flow --> #stoer_wagner
    #bipartite_graph --> #bipartite_matching
    #bipartite_matching --> #hall
    #bipartite_matching --> #hungarian
    #bipartite_matching --> #stable_marriage
    #scc --> #2_sat
    #dijkstra --> #0_1_bfs
    #dijkstra --> #a_star
    #dag --> #topological_sorting

    #0_1_bfs[#0-1 너비 우선 탐색]
    #2_sat[#2-sat]
    #a_star[#a*]
    #scc[#강한 연결 요소]
    #graphs[#그래프 이론]
    #graph_traversal[#그래프 탐색]
    #articulation[#단절점과 단절선]
    #dijkstra[<a href="post/2024/01/01/dijkstra.html">#데이크스트라</a>]
    #dag[#방향 비순환 그래프]
    #bellman_ford[<a href="post/2024/01/07/bellman_ford.html">#벨만–포드</a>]
    #circulation[#서큘레이션]
    #cactus[#선인장]
    #stoer_wagner[#스토어–바그너]
    #stable_marriage[#안정 결혼 문제]
    #tsp[#외판원 순회 문제]
    #topological_sorting[#위상 정렬]
    #bipartite_graph[#이분 그래프]
    #bipartite_matching[#이분 매칭]
    #biconnected_component[#이중 연결 요소]
    #general_matching[#일반적인 매칭]
    #shortest_path[#최단 경로]
    #flow[#최대 유량]
    #mfmc[#최대 유량 최소 컷 정리]
    #mcmf[#최소 비용 최대 유량]
    #mst[#최소 스패닝 트리]
    #flood_fill[#플러드 필]
    #floyd_warshall[<a href="post/2024/01/07/floyd_warshall.html">#플로이드–워셜</a>]
    #hungarian[#헝가리안]
    #hall[#홀의 결혼 정리]
</pre>

### 3-3. 문자열

<pre class="mermaid">
    graph LR

    #string --> #parsing
    #string --> #kmp
    #string --> #trie
    #string --> #manacher
    #string --> #rabin_karp
    #string --> #suffix_array
    #string --> #z
    #parsing --> #regex
    #trie --> #aho_corasick
    #trie --> #suffix_tree

    #kmp[#KMP]
    #z[#z]
    #rabin_karp[#라빈–카프]
    #manacher[#매내처]
    #string[#문자열]
    #aho_corasick[#아호-코라식]
    #suffix_array[#접미사 배열과 LCP 배열]
    #suffix_tree[#접미사 트리]
    #regex[#정규 표현식]
    #trie[<a href="post/2024/01/03/trie.html">#트라이</a>]
    #parsing[#파싱]
</pre>

### 3-4. 오프라인 쿼리

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

### 3-5. 수학

<pre class="mermaid">
    graph LR

    #math --> #number_theory
    #math --> #linear_algebra
    #math --> #game_theory
    #math --> #geometry
    #math --> #calculus
    #math --> #combinatorics
    #math --> #probability
    #math --> #statistics

    subgraph 정수론
    #number_theory --> #crt
    #number_theory --> #euler_phi
    #number_theory --> #modular_multiplicative_inverse
    #number_theory --> #euclidean
    #number_theory --> #flt
    #number_theory --> #primality_test
    #number_theory --> #mobius_inversion
    #primality_test --> #miller_rabin
    #primality_test --> #sieve
    #flt --> #miller_rabin
    #euclidean --> #extended_euclidean
    #euclidean --> #pollard_rho
    #miller_rabin --> #pollard_rho
    end
    subgraph 기하학
    #geometry --> #pythagoras
    #geometry --> CCW
    #geometry --> #sweeping
    #geometry --> #coordinate_compression
    #geometry --> #delaunay
    #geometry --> #geometry_3d
    #geometry --> #euler_characteristic
    #euler_characteristic --> #pick
    #delaunay <--> #voronoi
    #geometry_3d --> #geometry_hyper
    CCW --> #line_intersection
    CCW --> #convex_hull
    CCW --> #point_in_non_convex_polygon
    #convex_hull --> #rotating_calipers
    #convex_hull --> #point_in_convex_polygon
    end
    #linear_algebra --> #gaussian_elimination
    #game_theory --> #sprague_grundy
    #calculus --> #fft
    #calculus --> #gradient_descent
    #calculus --> #polynomial_interpolation
    #calculus --> #ternary_search
    #combinatorics --> #inclusion_and_exclusion
    #probability --> #bayes

    #geometry_3d[#3차원 기하학]
    #geometry_hyper[#4차원 이상의 기하학]
    #gaussian_elimination[#가우스 소거법]
    #coordinate_compression[#값 / 좌표 압축]
    #game_theory[#게임 이론]
    #gradient_descent[#경사 하강법]
    #fft[#고속 푸리에 변환]
    #geometry[#기하학]
    #polynomial_interpolation[#다항식 보간법]
    #delaunay[#델로네 삼각분할]
    #modular_multiplicative_inverse[#모듈로 곱셈 역원]
    #mobius_inversion[#뫼비우스 반전 공식]
    #calculus[#미적분학]
    #miller_rabin[#밀러–라빈 소수 판별법]
    #bayes[#베이즈 정리]
    #voronoi[#보로노이 다이어그램]
    #convex_hull[#볼록 껍질]
    #point_in_convex_polygon[#볼록 다각형 내부의 점 판정]
    #ternary_search[#삼분 탐색]
    #line_intersection[#선분 교차 판정]
    #linear_algebra[#선형대수학]
    #primality_test[#소수 판정]
    #math[#수학]
    #sweeping[#스위핑]
    #sprague_grundy[#스프라그–그런디 정리]
    #sieve[#에라토스테네스의 체]
    #point_in_non_convex_polygon[#오목 다각형 내부의 점 판정]
    #euler_characteristic[#오일러 지표 #40;χ=V-E+F#41;]
    #euler_phi[#오일러 피 함수]
    #euclidean[#유클리드 호제법]
    #number_theory[#정수론]
    #combinatorics[#조합론]
    #crt[#중국인의 나머지 정리]
    #statistics[#통계학]
    #flt[#페르마의 소정리]
    #inclusion_and_exclusion[#포함 배제의 원리]
    #pollard_rho[#폴라드 로]
    #pythagoras[#피타고라스 정리]
    #pick[#픽의 정리]
    #probability[#확률론]
    #extended_euclidean[#확장 유클리드 호제법]
    #rotating_calipers[#회전하는 캘리퍼스]
</pre>

### 3-6. DP

<pre class="mermaid">
    graph LR

    #dp --> #knapsack
    #dp --> #dp_sum_over_subsets
    #dp --> Recurrence_Relation
    #dp --> #dp_bitfield
    #dp --> #dp_deque
    #dp --> #dp_digit
    #dp --> #dp_tree
    #dp_deque --> #deque_trick
    Recurrence_Relation --> #cht
    Recurrence_Relation --> #divide_and_conquer_optimization
    Recurrence_Relation --> #monotone_queue_optimization
    Recurrence_Relation --> #knuth
    Recurrence_Relation --> #kitamasa
    Recurrence_Relation --> #alien
    Recurrence_Relation --> #hirschberg
    #kitamasa --> #berlekamp_massey

    #alien[#Aliens 트릭]
    #dp[#다이나믹 프로그래밍]
    #monotone_queue_optimization[#단조 큐를 이용한 최적화]
    #deque_trick[#덱을 이용한 구간 최댓값 트릭]
    #dp_deque[#덱을 이용한 다이나믹 프로그래밍]
    #knapsack[#배낭 문제]
    #berlekamp_massey[#벌리캠프–매시]
    #cht[#볼록 껍질을 이용한 최적화]
    #dp_sum_over_subsets[#부분집합의 합 다이나믹 프로그래밍]
    #divide_and_conquer_optimization[#분할 정복을 사용한 최적화]
    #dp_bitfield[#비트필드를 이용한 다이나믹 프로그래밍]
    #dp_digit[#자릿수를 이용한 다이나믹 프로그래밍]
    #knuth[#크누스 최적화]
    #kitamasa[#키타마사]
    #dp_tree[#트리에서의 다이나믹 프로그래밍]
    #hirschberg[#히르쉬버그]
</pre>