---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---

## 소개

<a href="">APSwBT</a>(<u>A</u>lgorithm <u>P</u>roblem <u>S</u>olving <u>w</u>ith <u>B</u>eakjoon <u>T</u>ag)는 <a href="https://www.acmicpc.net/" target="_blank">백준</a>과 <a href="https://solved.ac/" target="_blank">솔브드</a>의 모든 태그의 카테고리를 분류하고 난이도 별로 정리한 블로그입니다. 

<pre class="mermaid">
    graph LR

    home --> paradigm
    home --> data_structure
    home --> algorithm
    algorithm --> sorting_search
    algorithm --> trees
    algorithm --> graphs
    algorithm --> strings
    algorithm --> math
    algorithm --> dp
    algorithm --> others
    math --> number_theory
    math --> geometry

    subgraph Navigation
        home
        posts
        tags
    end

    home(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="">Home</a>"]):::tier1
    posts(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="archives.html">Posts</a>"]):::tier1
    tags(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="tags.html">Tags</a>"]):::tier1
    paradigm(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-패러다임">패러다임</a>"]):::tier2
    data_structure(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-자료구조">자료구조</a>"]):::tier2
    algorithm(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-알고리즘">알고리즘</a>"]):::tier2
    sorting_search(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-정렬과-탐색">정렬과 탐색</a>"]):::tier3
    trees(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-트리">트리</a>"]):::tier3
    graphs(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-그래프">그래프</a>"]):::tier3
    strings(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-문자열">문자열</a>"]):::tier3
    math(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-수학">수학</a>"]):::tier3
    dp(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-동적계획법">동적계획법</a>"]):::tier3
    others(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-기타">기타</a>"]):::tier3
    number_theory(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-정수론">정수론</a>"]):::tier3
    geometry(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-기하">기하</a>"]):::tier3

    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
</pre>

빨간색 배지가 있는 태그를 클릭하시면 관련 포스트로 이동하실 수 있습니다. 

<pre class="mermaid">
    graph LR

    bronze --> silver --> gold --> platinum --> diamond --> ruby

    subgraph 쉬움
        bronze
        silver
    end

    subgraph 어려움
        diamond
        ruby
    end

    bronze([Bronze]):::tier0
    silver([Silver]):::tier1
    gold([Gold]):::tier2
    platinum([Platinum]):::tier3
    diamond([Diamond]):::tier4
    ruby([Ruby]):::tier5

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

각 태그의 색깔은 해당 태그가 사용된 백준 문제의 평균 솔브드 티어입니다.

| 플랫폼 | 아이디 |
| --- | --- |
| <img src="https://github.githubassets.com/favicons/favicon-dark.svg" style="height: 20px; box-sizing: border-box; padding: 2px; background: black; border-radius: 50%; display: inline-block"> GitHub | <a href="https://github.com/CHOYUNSIG" target="_blank">CHOYUNSIG</a> |
| <img src="https://www.acmicpc.net/favicon-32x32.png/" style="height: 20px; display: inline-block"> Baekjoon Online Judge | <a href="https://www.acmicpc.net/user/asdfghjkl46" target="_blank">asdfghjkl46</a> |
| <img src="https://static.solved.ac/logo.svg" style="height: 20px; display: inline-block">solved.ac | <a href="https://solved.ac/profile/asdfghjkl46" target="_blank">asdfghjkl46</a> |

블로그의 모든 글은 <b>조윤식</b>이 작성하였습니다. 오타 및 내용 상의 오류나 개선 사항이 있을 경우 의견을 보내주세요.

## 패러다임

<pre class="mermaid tag-connection-define">
    graph LR
    
    #divide_and_conquer
    #dp
    #bruteforcing --> #backtracking
    #greedy
    #heuristics
</pre>

## 자료구조

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -150px)">
    graph LR

    #data_structures --> #stack
    #data_structures --> #queue
    #data_structures --> #string
    #queue --> #deque
    #data_structures --> #linked_list
    #data_structures --> #graphs
    #data_structures --> #trees
    #trees --> #priority_queue
    #trees --> #tree_set
    #trees --> #segtree
    #data_structures --> #hash_set
    #graphs --> #graph_traversal
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
        #segtree
        #priority_queue
        #trees
        #tree_set
    end
</pre>

## 알고리즘

### 정렬과 탐색

<pre class="mermaid tag-connection-define">
    graph LR

    #sorting --> #binary_search
    #binary_search --> #parametric_search
    #parametric_search --> #pbs
</pre>

### 트리

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -600px)">
    graph LR

    #trees --> #tree_set
    #trees --> #priority_queue
    #trees --> #segtree
    #trees --> #disjoint_set
    #trees --> #euler_tour_technique
    #trees --> #centroid
    #trees --> #tree_compression
    #trees --> #tree_decomposition
    #trees --> #smaller_to_larger
    #tree_set --> #splay_tree
    #tree_set --> #rb_tree
    #priority_queue --> #cartesian_tree
    #lca --> #link_cut_tree
    #lca --> #hld
    #centroid --> #centroid_decomposition
    #centroid --> #tree_isomorphism
    #splay_tree --> #link_cut_tree
    #link_cut_tree --> #top_tree
    #segtree --> #merge_sort_tree
    #segtree --> #lazyprop
    #segtree --> #pst
    #segtree --> #multi_segtree
    #segtree --> #offline_dynamic_connectivity
    #segtree --> #hld
    #euler_tour_technique --> #lca
    #lazyprop --> #link_cut_tree
    #disjoint_set --> #offline_dynamic_connectivity

    subgraph 기법
        #tree_compression
        #tree_decomposition
        #smaller_to_larger
    end
</pre>

### 그래프

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -1100px)">
    graph LR

    #graphs --> #shortest_path
    #graphs --> #flow
    #graphs --> #bipartite_graph
    #graphs --> #general_matching
    #graphs --> #scc
    #graphs --> #functional_graph
    #graphs --> #articulation
    #graphs --> #mst
    #graphs --> #tsp
    #graphs --> #dag
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
    #flow --> #circulation
    #flow --> #stoer_wagner
    #flow --> #mcmf
    #flow --> #mfmc
    #flow --> #bipartite_matching
    #bipartite_graph --> #bipartite_matching
    #bipartite_matching --> #hall
    #bipartite_matching --> #hungarian
    #bipartite_matching --> #stable_marriage
    #mst --> #directed_mst
    #scc --> #2_sat
    #scc --> #permutation_cycle_decomposition
    #functional_graph --> #permutation_cycle_decomposition
    #dijkstra --> #0_1_bfs
    #dijkstra --> #a_star
    #dag --> #topological_sorting
    #dag --> #lgv
</pre>

### 문자열

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -300px)">
    graph LR

    #string --> #utf8
    #string --> #manacher
    #string --> #palindrome_tree
    #string --> #rope
    #string --> #parsing
    #string --> #trie
    #string --> #kmp
    #string --> #rabin_karp
    #string --> #suffix_array
    #string --> #z
    #parsing --> #regex
    #trie --> #aho_corasick
    #trie --> #suffix_tree

    subgraph 회문
        #manacher
        #palindrome_tree
    end

    subgraph 패턴 매칭
        #aho_corasick
        #kmp
        #rabin_karp
        #suffix_array
        #suffix_tree
        #z
    end
</pre>

### 수학

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -1000px)">
    graph LR

    #math --> #number_theory
    #math --> #geometry
    #math --> #linear_algebra
    #math --> #combinatorics
    #math --> #game_theory
    #math --> #calculus
    #math --> #probability
    #math --> #pigeonhole_principle
    #math --> #statistics
    #math --> #physics
    #math --> #arithmetic
    #math --> #duality
    #linear_algebra --> #gaussian_elimination
    #linear_algebra --> #sparse_table
    #linear_algebra --> #matroid
    #game_theory --> #sprague_grundy
    #sprague_grundy --> #hackenbush
    #calculus --> #fft
    #calculus --> #gradient_descent
    #calculus --> #ternary_search
    #calculus --> #green
    #calculus --> #numerical_analysis
    #fft --> #multipoint_evaluation
    #combinatorics --> #matroid
    #combinatorics --> #inclusion_and_exclusion
    #combinatorics --> #lucas
    #combinatorics --> #burnside
    #combinatorics --> #generating_function
    #probability --> #bayes
    #probability --> #linearity_of_expectation
    #probability --> #randomization
    #probability --> #differential_cryptanalysis
    #probability --> #birthday
    #numerical_analysis --> #linear_programming
    #numerical_analysis --> #polynomial_interpolation
    #arithmetic --> #arbitrary_precision
    #arithmetic --> #discrete_kth_root
    #arithmetic --> #discrete_log
    #arithmetic --> #discrete_sqrt
    #arithmetic --> #exponentiation_by_squaring
    #pigeonhole_principle --> #birthday
</pre>

#### 정수론

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -100px)">
    graph LR

    #number_theory --> #crt
    #number_theory --> #euler_phi
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
    #extended_euclidean --> #modular_multiplicative_inverse
</pre>

#### 기하

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -200px)">
    graph LR

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
</pre>

### 동적계획법

<pre class="mermaid tag-connection-define" style="transform: translate(0px, -500px)">
    graph LR

    #dp --> #prefix_sum
    #dp --> #knapsack
    #dp --> #dp_deque
    #dp --> #dp_digit
    #dp --> #dp_tree
    #dp --> #dp_connection_profile
    #dp --> #dp_bitfield
    #dp --> #dp_sum_over_subsets
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
    #bitmask --> #dp_bitfield
    #bitmask --> #dp_sum_over_subsets

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
</pre>

### 기타

<pre class="mermaid tag-connection-define">
    graph LR

    #two_pointer --> #sliding_window
    #two_pointer --> #mitm
    #two_pointer --> #sqrt_decomposition
    #two_pointer --> #mo
    #offline_queries --> #mo
    #mitm --> #bidirectional_search
</pre>

<pre class="mermaid tag-connection-define">
    graph LR

    #dancing_links --> #knuth_x
</pre>

<pre class="mermaid tag-connection-define">
    graph LR

    #implementation --> #case_work
    #implementation --> #simulation
</pre>

<pre class="mermaid tag-connection-define">
    graph LR

    #majority_vote
    #lis
    #simulated_annealing
    #constructive
    #ad_hoc
    #precomputation
</pre>
