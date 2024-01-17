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

    Paradigm((패러다임))

    #greedy(["#그리디 알고리즘"])
    #dp(["#다이나믹 프로그래밍"])
    #backtracking(["#백트래킹"])
    #divide_and_conquer(["#분할 정복"])
    #bruteforcing(["#브루트포스 알고리즘"])
    #heuristics(["#휴리스틱"])
</pre>

<br>

## 2. 자료구조

<pre class="mermaid">
    graph LR

    #data_structures --> #stack
    #data_structures --> #queue
    #data_structures --> #string
    #queue --> #deque
    #data_structures --> #linked_list
    #data_structures --> #graphs
    #data_structures --> #trees
    #data_structures --> #hash_set
    #graphs --> #graph_traversal
    #trees --> #priority_queue
    #trees --> #tree_set
    #trees --> #segtree
    #graph_traversal --> #dfs
    #graph_traversal --> #bfs
    #recursion --> #dfs
    #hashing --> #hash_set

    subgraph 선형
        #stack
        #queue
        #string
        #deque
    end

    subgraph 비선형
        #graphs
        #graph_traversal
        #dfs
        #bfs
        #segtree
        #priority_queue
        #trees
        #tree_set
    end

    #graphs(["#그래프 이론"])
    #graph_traversal(["#그래프 탐색"])
    #dfs(["#깊이 우선 탐색"])
    #bfs(["#너비 우선 탐색"])
    #deque(["#덱"])
    #string(["#문자열"])
    #segtree(["<a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>"])
    #stack(["#스택"])
    #linked_list(["#연결 리스트"])
    #priority_queue(["<a href="post/2024/01/15/priority_queue.html">#우선순위 큐</a>"])
    #data_structures(["#자료 구조"])
    #recursion(["#재귀"])
    #queue(["#큐"])
    #trees(["#트리"])
    #tree_set(["#트리를 사용한 집합과 맵"])
    #hash_set(["#해시를 사용한 집합과 맵"])
    #hashing(["#해싱"])
</pre>

<br>

## 3. 알고리즘

### 3-0. 정렬과 검색

<pre class="mermaid">
    graph LR

    #sorting --> #binary_search
    #binary_search --> #parametric_search
    #parametric_search --> #pbs

    #parametric_search(["#매개 변수 탐색"])
    #pbs(["#병렬 이분 탐색"])
    #binary_search(["#이분 탐색"])
    #sorting(["#정렬"])
</pre>

### 3-1. 트리

<pre class="mermaid">
    graph LR

    #trees --> #splay_tree
    #trees --> #rb_tree
    #trees --> #priority_queue
    #trees --> #trie
    #trees --> #segtree
    #trees --> #euler_tour_technique
    #trees --> #disjoint_set
    #trees --> #lca
    #trees --> #centroid
    #priority_queue --> #cartesian_tree
    #lca --> #link_cut_tree
    #disjoint_set --> #offline_dynamic_connectivity
    #disjoint_set --> #smaller_to_larger
    #disjoint_set <--> #tree_compression
    #centroid --> #centroid_decomposition
    #centroid --> #tree_isomorphism
    #splay_tree --> #link_cut_tree
    #link_cut_tree --> #top_tree
    #euler_tour_technique --> #hld
    #segtree --> #merge_sort_tree
    #segtree --> #lazyprop
    #segtree --> #pst
    #segtree --> #multi_segtree
    #segtree --> #hld
    #segtree --> #offline_dynamic_connectivity
    #lazyprop --> #link_cut_tree
    #hld <--> #tree_compression
    #hld <--> #tree_decomposition
    #centroid_decomposition <--> #tree_decomposition

    subgraph 이진검색트리
        #splay_tree
        #rb_tree
    end

    #hld(["#Heavy-light 분할"])
    #lazyprop(["#느리게 갱신되는 세그먼트 트리"])
    #multi_segtree(["#다차원 세그먼트 트리"])
    #cartesian_tree(["#데카르트 트리"])
    #rb_tree(["#레드-블랙 트리"])
    #link_cut_tree(["#링크/컷 트리"])
    #merge_sort_tree(["#머지 소트 트리"])
    #disjoint_set(["<a href="post/2024/01/13/disjoint_set.html">#분리 집합</a>"])
    #segtree(["<a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>"])
    #centroid(["#센트로이드"])
    #centroid_decomposition(["#센트로이드 분할"])
    #splay_tree(["#스플레이 트리"])
    #euler_tour_technique(["#오일러 경로 테크닉"])
    #offline_dynamic_connectivity(["#오프라인 동적 연결성 판정"])
    #priority_queue(["<a href="post/2024/01/15/priority_queue.html">#우선순위 큐</a>"])
    #smaller_to_larger(["#작은 집합에서 큰 집합으로 합치는 테크닉"])
    #lca(["#최소 공통 조상"])
    #top_tree(["#탑 트리"])
    #trie(["<a href="post/2024/01/03/trie.html">#트라이</a>"])
    #trees(["#트리"])
    #tree_isomorphism(["#트리 동형 사상"])
    #tree_decomposition(["#트리 분할"])
    #tree_compression(["#트리 압축"])
    #pst(["#퍼시스턴트 세그먼트 트리"])
</pre>

### 3-2. 그래프

<pre class="mermaid">
    graph LR

    #graphs --> #shortest_path
    #graphs --> #flow
    #graphs --> #bipartite_graph
    #graphs --> #general_matching
    #graphs --> #scc
    #graphs --> #articulation
    #graphs --> #mst
    #graphs --> #tsp
    #graphs --> #dag
    #graphs --> #functional_graph
    #graphs --> #chordal_graph
    #graphs --> #degree_sequence
    #graphs --> #dual_graph
    #graphs --> #flood_fill
    #graphs --> #eulerian_path
    #general_matching --> #bipartite_matching
    #articulation --> #biconnected_component
    #articulation --> #cactus
    #articulation --> #dominator_tree
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
    #mst --> #directed_mst
    #scc --> #2_sat
    #scc --> #permutation_cycle_decomposition
    #dijkstra --> #0_1_bfs
    #dijkstra --> #a_star
    #dag --> #topological_sorting
    #dag --> #lgv

    #0_1_bfs(["#0-1 너비 우선 탐색"])
    #2_sat(["#2-sat"])
    #a_star(["#a*"])
    #scc(["#강한 연결 요소"])
    #graphs(["#그래프 이론"])
    #articulation(["#단절점과 단절선"])
    #dijkstra(["<a href="post/2024/01/01/dijkstra.html">#데이크스트라</a>"])
    #dominator_tree(["#도미네이터 트리"])
    #lgv(["#린드스트롬–게셀–비엔노 보조정리"])
    #dag(["#방향 비순환 그래프"])
    #bellman_ford(["<a href="post/2024/01/07/bellman_ford.html">#벨만–포드</a>"])
    #circulation(["#서큘레이션"])
    #cactus(["#선인장"])
    #permutation_cycle_decomposition(["#순열 사이클 분할"])
    #stoer_wagner(["#스토어–바그너"])
    #dual_graph(["#쌍대 그래프"])
    #stable_marriage(["#안정 결혼 문제"])
    #eulerian_path(["#오일러 경로"])
    #tsp(["#외판원 순회 문제"])
    #topological_sorting(["#위상 정렬"])
    #directed_mst(["#유향 최소 신장 트리"])
    #bipartite_graph(["#이분 그래프"])
    #bipartite_matching(["#이분 매칭"])
    #biconnected_component(["#이중 연결 요소"])
    #general_matching(["#일반적인 매칭"])
    #degree_sequence(["#차수열"])
    #shortest_path(["#최단 경로"])
    #flow(["#최대 유량"])
    #mfmc(["#최대 유량 최소 컷 정리"])
    #mcmf(["#최소 비용 최대 유량"])
    #mst(["#최소 스패닝 트리"])
    #flood_fill(["#플러드 필"])
    #floyd_warshall(["<a href="post/2024/01/07/floyd_warshall.html">#플로이드–워셜</a>"])
    #functional_graph(["#함수형 그래프"])
    #hungarian(["#헝가리안"])
    #chordal_graph(["#현 그래프"])
    #hall(["#홀의 결혼 정리"])
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
    #string --> #utf8
    #string --> #palindrome_tree
    #string --> #rope
    #parsing --> #regex
    #trie --> #aho_corasick
    #trie --> #suffix_tree

    #kmp(["#KMP"])
    #utf8(["#utf-8 입력 처리"])
    #z(["#z"])
    #rabin_karp(["#라빈–카프"])
    #rope(["#로프"])
    #manacher(["#매내처"])
    #string(["#문자열"])
    #aho_corasick(["#아호-코라식"])
    #suffix_array(["#접미사 배열과 LCP 배열"])
    #suffix_tree(["#접미사 트리"])
    #regex(["#정규 표현식"])
    #trie(["<a href="post/2024/01/03/trie.html">#트라이</a>"])
    #parsing(["#파싱"])
    #palindrome_tree(["#회문 트리"])
</pre>

### 3-4. 오프라인 쿼리

<pre class="mermaid">
    graph LR

    #offline_queries --> #sqrt_decomposition
    #offline_queries --> #prefix_sum
    #offline_queries --> #majority_vote
    #offline_queries --> #two_pointer
    #offline_queries --> #lis
    #two_pointer --> #mo
    #two_pointer --> #sliding_window
    #two_pointer --> #mitm
    #mitm --> #bidirectional_search

    #mo(["#mo's"])
    #lis(["#가장 긴 증가하는 부분 수열: O(n log n)"])
    #prefix_sum(["#누적 합"])
    #two_pointer(["#두 포인터"])
    #majority_vote(["#보이어–무어 다수결 투표"])
    #sliding_window(["#슬라이딩 윈도우"])
    #bidirectional_search(["#양방향 탐색"])
    #offline_queries(["#오프라인 쿼리"])
    #sqrt_decomposition(["#제곱근 분할법"])
    #mitm(["#중간에서 만나기"])
</pre>

### 3-5. 수학

<pre class="mermaid">
    graph LR

    #math --> #number_theory
    #math --> #geometry
    #math --> #linear_algebra
    #math --> #game_theory
    #math --> #calculus
    #math --> #combinatorics
    #math --> #probability
    #math --> #statistics
    #math --> #physics
    #math --> #numerical_analysis
    #math --> #arithmetic
    #math --> #pigeonhole_principle
    #math --> #duality
    #number_theory --> #crt
    #number_theory --> #euler_phi
    #number_theory --> #modular_multiplicative_inverse
    #number_theory --> #euclidean
    #number_theory --> #flt
    #number_theory --> #primality_test
    #number_theory --> #mobius_inversion
    #number_theory --> #lte
    #primality_test --> #miller_rabin
    #primality_test --> #sieve
    #flt --> #miller_rabin
    #euclidean --> #extended_euclidean
    #euclidean --> #pollard_rho
    #miller_rabin --> #pollard_rho
    #geometry --> #pythagoras
    #geometry --> #line_intersection
    #geometry --> #sweeping
    #geometry --> #coordinate_compression
    #geometry --> #delaunay
    #geometry --> #geometry_3d
    #geometry --> #euler_characteristic
    #geometry --> #polygon_area
    #geometry --> #min_enclosing_circle
    #geometry --> #geometric_boolean_operations
    #euler_characteristic --> #pick
    #euler_characteristic --> #planar_graph
    #delaunay <--> #voronoi
    #geometry_3d --> #geometry_hyper
    #line_intersection --> #convex_hull
    #line_intersection --> #point_in_non_convex_polygon
    #line_intersection --> #half_plane_intersection
    #convex_hull --> #rotating_calipers
    #convex_hull --> #point_in_convex_polygon
    #linear_algebra --> #gaussian_elimination
    #linear_algebra --> #sparse_table
    #game_theory --> #sprague_grundy
    #sprague_grundy --> #hackenbush
    #calculus --> #fft
    #calculus --> #gradient_descent
    #calculus --> #polynomial_interpolation
    #calculus --> #ternary_search
    #calculus --> #green
    #combinatorics --> #inclusion_and_exclusion
    #combinatorics --> #lucas
    #combinatorics --> #matroid
    #combinatorics --> #burnside
    #combinatorics --> #generating_function
    #probability --> #bayes
    #probability --> #linearity_of_expectation
    #probability --> #randomization
    #probability --> #differential_cryptanalysis
    #randomization --> #simulated_annealing
    #numerical_analysis --> #linear_programming
    #arithmetic --> #arbitrary_precision
    #arithmetic --> #discrete_kth_root
    #arithmetic --> #discrete_log
    #arithmetic --> #discrete_sqrt
    #arithmetic --> #exponentiation_by_squaring
    #pigeonhole_principle --> #birthday

    subgraph 정수론
        #modular_multiplicative_inverse
        #mobius_inversion
        #miller_rabin
        #primality_test
        #sieve
        #euler_phi
        #euclidean
        #number_theory
        #crt
        #lte
        #flt
        #pollard_rho
        #extended_euclidean
    end

    subgraph 기하학
        #geometry_3d
        #geometry_hyper
        #coordinate_compression
        #geometry
        #polygon_area
        #delaunay
        #geometric_boolean_operations
        #half_plane_intersection
        #voronoi
        #convex_hull
        #point_in_convex_polygon
        #line_intersection
        #sweeping
        #point_in_non_convex_polygon
        #euler_characteristic
        #min_enclosing_circle
        #planar_graph
        #pythagoras
        #pick
        #rotating_calipers
    end

    #geometry_3d(["#3차원 기하학"])
    #geometry_hyper(["#4차원 이상의 기하학"])
    #gaussian_elimination(["#가우스 소거법"])
    #coordinate_compression(["#값 / 좌표 압축"])
    #game_theory(["#게임 이론"])
    #gradient_descent(["#경사 하강법"])
    #fft(["#고속 푸리에 변환"])
    #green(["#그린 정리"])
    #linearity_of_expectation(["#기댓값의 선형성"])
    #geometry(["#기하학"])
    #polygon_area(["#다각형의 넓이"])
    #polynomial_interpolation(["#다항식 보간법"])
    #simulated_annealing(["#담금질 기법"])
    #delaunay(["#델로네 삼각분할"])
    #geometric_boolean_operations(["#도형에서의 불 연산"])
    #lucas(["#뤼카 정리"])
    #matroid(["#매트로이드"])
    #modular_multiplicative_inverse(["#모듈로 곱셈 역원"])
    #mobius_inversion(["#뫼비우스 반전 공식"])
    #randomization(["#무작위화"])
    #physics(["#물리학"])
    #calculus(["#미적분학"])
    #miller_rabin(["#밀러–라빈 소수 판별법"])
    #half_plane_intersection(["#반평면 교집합"])
    #burnside(["#번사이드 보조정리"])
    #bayes(["#베이즈 정리"])
    #voronoi(["#보로노이 다이어그램"])
    #convex_hull(["#볼록 껍질"])
    #point_in_convex_polygon(["#볼록 다각형 내부의 점 판정"])
    #exponentiation_by_squaring(["#분할 정복을 이용한 거듭제곱"])
    #pigeonhole_principle(["#비둘기집 원리"])
    #arithmetic(["#사칙연산"])
    #ternary_search(["#삼분 탐색"])
    #generating_function(["#생성 함수"])
    #birthday(["#생일 문제"])
    #line_intersection(["#선분 교차 판정"])
    #linear_programming(["#선형 계획법"])
    #linear_algebra(["#선형대수학"])
    #primality_test(["#소수 판정"])
    #numerical_analysis(["#수치해석"])
    #math(["#수학"])
    #sweeping(["#스위핑"])
    #sprague_grundy(["#스프라그–그런디 정리"])
    #duality(["#쌍대성"])
    #sieve(["#에라토스테네스의 체"])
    #point_in_non_convex_polygon(["#오목 다각형 내부의 점 판정"])
    #euler_characteristic(["#오일러 지표 (χ=V-E+F)"])
    #euler_phi(["#오일러 피 함수"])
    #euclidean(["#유클리드 호제법"])
    #discrete_kth_root(["#이산 k제곱근"])
    #discrete_log(["#이산 로그"])
    #discrete_sqrt(["#이산 제곱근"])
    #arbitrary_precision(["#임의 정밀도 / 큰 수 연산"])
    #number_theory(["#정수론"])
    #combinatorics(["#조합론"])
    #crt(["#중국인의 나머지 정리"])
    #lte(["#지수승강 보조정리"])
    #differential_cryptanalysis(["#차분 공격"])
    #min_enclosing_circle(["#최소 외접원"])
    #statistics(["#통계학"])
    #flt(["#페르마의 소정리"])
    #planar_graph(["#평면 그래프"])
    #inclusion_and_exclusion(["#포함 배제의 원리"])
    #pollard_rho(["#폴라드 로"])
    #pythagoras(["#피타고라스 정리"])
    #pick(["#픽의 정리"])
    #hackenbush(["#하켄부시 게임"])
    #probability(["#확률론"])
    #extended_euclidean(["#확장 유클리드 호제법"])
    #rotating_calipers(["#회전하는 캘리퍼스"])
    #sparse_table(["#희소 배열"])
</pre>

### 3-6. 동적계획법

<pre class="mermaid">
    graph LR

    #dp --> #knapsack
    #dp --> #dp_sum_over_subsets
    #dp --> #dp_bitfield
    #dp --> #dp_deque
    #dp --> #dp_digit
    #dp --> #dp_tree
    #dp --> #bitmask
    #dp --> #slope_trick
    #dp --> #cht
    #dp --> #divide_and_conquer_optimization
    #dp --> #monotone_queue_optimization
    #dp --> #knuth
    #dp --> #kitamasa
    #dp --> #alien
    #dp --> #hirschberg
    #kitamasa --> #berlekamp_massey
    #dp_deque --> #deque_trick
    #bitmask --> #bitset
    #bitmask --> #dp_connection_profile

    subgraph 점화식
        #alien
        #monotone_queue_optimization
        #berlekamp_massey
        #cht
        #divide_and_conquer_optimization
        #knuth
        #kitamasa
        #hirschberg
    end

    #alien(["#Aliens 트릭"])
    #dp(["#다이나믹 프로그래밍"])
    #monotone_queue_optimization(["#단조 큐를 이용한 최적화"])
    #deque_trick(["#덱을 이용한 구간 최댓값 트릭"])
    #dp_deque(["#덱을 이용한 다이나믹 프로그래밍"])
    #knapsack(["#배낭 문제"])
    #berlekamp_massey(["#벌리캠프–매시"])
    #cht(["#볼록 껍질을 이용한 최적화"])
    #dp_sum_over_subsets(["#부분집합의 합 다이나믹 프로그래밍"])
    #divide_and_conquer_optimization(["#분할 정복을 사용한 최적화"])
    #bitset(["#비트 집합"])
    #bitmask(["#비트마스킹"])
    #dp_bitfield(["#비트필드를 이용한 다이나믹 프로그래밍"])
    #dp_digit(["#자릿수를 이용한 다이나믹 프로그래밍"])
    #dp_connection_profile(["#커넥션 프로파일을 이용한 다이나믹 프로그래밍"])
    #knuth(["#크누스 최적화"])
    #kitamasa(["#키타마사"])
    #dp_tree(["#트리에서의 다이나믹 프로그래밍"])
    #slope_trick(["#함수 개형을 이용한 최적화"])
    #hirschberg(["#히르쉬버그"])
</pre>

## 4. 부록

### 4-1. 구현

<pre class="mermaid">
    graph LR

    #implementation --> #multipoint_evaluation
    #implementation --> #case_work
    #implementation --> #simulation

    #implementation(["#구현"])
    #multipoint_evaluation(["#다중 대입값 계산"])
    #case_work(["#많은 조건 분기"])
    #simulation(["#시뮬레이션"])
</pre>

### 4-2. 백트래킹 최적화

<pre class="mermaid">
    graph LR

    #backtracking --> #precomputation
    #backtracking --> #dancing_links
    #dancing_links --> #knuth_x

    #precomputation(["#런타임 전의 전처리"])
    #backtracking(["#백트래킹"])
    #dancing_links(["#춤추는 링크"])
    #knuth_x(["#크누스 X"])
</pre>

### 4-3. 발상

<pre class="mermaid">
    graph LR

    #ad_hoc(["#애드 혹"])
    #constructive(["#해 구성하기"])
</pre>