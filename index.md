---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
banner:
    image: "/assets/images/banners/home.jpeg"
---

## 소개

<a href="">APSwBT</a>(<u>A</u>lgorithm <u>P</u>roblem <u>S</u>olving <u>w</u>ith <u>B</u>eakjoon <u>T</u>ag)는 <a href="https://www.acmicpc.net/" target="_blank">백준</a>과 <a href="https://solved.ac/" target="_blank">솔브드</a>의 모든 태그의 카테고리를 분류하고 난이도 별로 정리한 블로그입니다. 

<center>
    <pre class="mermaid" style="max-width: 70%">
        graph LR

        home --> paradigm
        home --> data_structure
        home --> algorithm
        home --> none
        algorithm --> sorting_search
        algorithm --> trees
        algorithm --> graphs
        algorithm --> strings
        algorithm --> offline_query
        algorithm --> math
        algorithm --> optimization
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
        paradigm(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-1-패러다임">패러다임</a>"]):::tier2
        data_structure(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-2-자료구조">자료구조</a>"]):::tier2
        algorithm(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-알고리즘">알고리즘</a>"]):::tier2
        sorting_search(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-1-정렬과-검색">정렬과 탐색</a>"]):::tier3
        trees(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-2-트리">트리</a>"]):::tier3
        graphs(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-3-그래프">그래프</a>"]):::tier3
        strings(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-4-문자열">문자열</a>"]):::tier3
        offline_query(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-5-오프라인-쿼리">오프라인 쿼리</a>"]):::tier3
        math(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-6-수학">수학</a>"]):::tier3
        optimization(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-7-최적화-및-기법">최적화 및 기법</a>"]):::tier3
        number_theory(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-6-1-정수론">정수론</a>"]):::tier3
        geometry(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-3-6-2-기하">기하</a>"]):::tier3
        none(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="#h-a-미분류">미분류</a>"]):::tier0

        classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
        classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
        classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
        classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    </pre>
</center>

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

<div style="text-align: center; margin-bottom: 16px">
    <img src="https://github-readme-solvedac.hyp3rflow.vercel.app/api/?handle=asdfghjkl46" width="90%">
</div>

블로그의 모든 글은 <b>조윤식</b>(깃허브: <a href="https://github.com/CHOYUNSIG" target="_blank">CHOYUNSIG</a>, 솔브드: <a href="https://solved.ac/profile/asdfghjkl46" target="_blank">asdfghjkl46</a>)이 작성하였습니다. 오타 및 내용 상의 오류나 개선 사항이 있을 경우 의견을 보내주세요.

<hr style="margin-top: 50pt; margin-bottom: 50pt">

## 1. 패러다임

<pre class="mermaid">
    graph LR
    
    Paradigm --> #divide_and_conquer
    Paradigm --> #dp
    Paradigm --> #bruteforcing
    Paradigm --> #greedy
    Paradigm --> #heuristics
    #bruteforcing --> #backtracking

    Paradigm((문제 해결 패러다임)):::paradigm
    classDef paradigm stroke:#0000

    #greedy(["#그리디 알고리즘"]):::tier1
    #dp(["#다이나믹 프로그래밍"]):::tier2
    #backtracking(["#백트래킹"]):::tier1
    #divide_and_conquer(["#분할 정복"]):::tier3
    #bruteforcing(["#브루트포스 알고리즘"]):::tier1
    #heuristics(["#휴리스틱"]):::tier2

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

<hr style="margin-top: 50pt; margin-bottom: 50pt">

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

    #graphs(["#그래프 이론"]):::tier2
    #graph_traversal(["#그래프 탐색"]):::tier2
    #dfs(["#깊이 우선 탐색"]):::tier2
    #bfs(["#너비 우선 탐색"]):::tier2
    #deque(["#덱"]):::tier2
    #string(["#문자열"]):::tier0
    #segtree(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>"]):::tier3
    #stack(["#스택"]):::tier1
    #linked_list(["#연결 리스트"]):::tier2
    #priority_queue(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/15/priority_queue.html">#우선순위 큐</a>"]):::tier2
    #data_structures(["#자료 구조"]):::tier2
    #recursion(["#재귀"]):::tier1
    #queue(["#큐"]):::tier1
    #trees(["#트리"]):::tier2
    #tree_set(["#트리를 사용한 집합과 맵"]):::tier2
    #hash_set(["#해시를 사용한 집합과 맵"]):::tier1
    #hashing(["#해싱"]):::tier3

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

<hr style="margin-top: 50pt; margin-bottom: 50pt">

## 3. 알고리즘

### 3-1. 정렬과 검색

<pre class="mermaid">
    graph LR

    #sorting --> #binary_search
    #binary_search --> #parametric_search
    #parametric_search --> #pbs

    #parametric_search(["#매개 변수 탐색"]):::tier2
    #pbs(["#병렬 이분 탐색"]):::tier4
    #binary_search(["#이분 탐색"]):::tier2
    #sorting(["#정렬"]):::tier1

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

### 3-2. 트리

<pre class="mermaid">
    graph LR

    #trees --> #splay_tree
    #trees --> #rb_tree
    #trees --> #priority_queue
    #trees --> #segtree
    #trees --> #euler_tour_technique
    #trees --> #disjoint_set
    #trees --> #centroid
    #priority_queue --> #cartesian_tree
    #lca --> #link_cut_tree
    #centroid --> #centroid_decomposition
    #centroid --> #tree_isomorphism
    #splay_tree --> #link_cut_tree
    #link_cut_tree --> #top_tree
    #segtree --> #merge_sort_tree
    #segtree --> #lazyprop
    #segtree --> #pst
    #segtree --> #multi_segtree
    #segtree --> #hld
    #segtree --> #offline_dynamic_connectivity
    #euler_tour_technique --> #hld
    #euler_tour_technique --> #lca
    #lazyprop --> #link_cut_tree
    #disjoint_set --> #offline_dynamic_connectivity
    #disjoint_set --> #smaller_to_larger
    #disjoint_set <--> #tree_compression 
    #centroid_decomposition <--> #tree_decomposition 
    #hld <--> #tree_compression
    #hld <--> #tree_decomposition

    subgraph 이진 검색 트리
        #splay_tree
        #rb_tree
    end

    subgraph 세그먼트 트리
        #segtree
        #merge_sort_tree
        #lazyprop
        #pst
        #multi_segtree
    end

    #hld(["#Heavy-light 분할"]):::tier4
    #lazyprop(["#느리게 갱신되는 세그먼트 트리"]):::tier3
    #multi_segtree(["#다차원 세그먼트 트리"]):::tier3
    #cartesian_tree(["#데카르트 트리"]):::tier4
    #rb_tree(["#레드-블랙 트리"]):::tier5
    #link_cut_tree(["#링크/컷 트리"]):::tier4
    #merge_sort_tree(["#머지 소트 트리"]):::tier3
    #disjoint_set(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/13/disjoint_set.html">#분리 집합</a>"]):::tier2
    #segtree(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/11/segtree.html">#세그먼트 트리</a>"]):::tier3
    #centroid(["#센트로이드"]):::tier4
    #centroid_decomposition(["#센트로이드 분할"]):::tier4
    #splay_tree(["#스플레이 트리"]):::tier4
    #euler_tour_technique(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/18/euler_tour_technique.html">#오일러 경로 테크닉</a>"]):::tier3
    #offline_dynamic_connectivity(["#오프라인 동적 연결성 판정"]):::tier4
    #priority_queue(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/15/priority_queue.html">#우선순위 큐</a>"]):::tier2
    #smaller_to_larger(["#작은 집합에서 큰 집합으로 합치는 테크닉"]):::tier3
    #lca(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/20/lca.html">#최소 공통 조상</a>"]):::tier3
    #top_tree(["#탑 트리"]):::tier5
    #trees(["#트리"]):::tier2
    #tree_isomorphism(["#트리 동형 사상"]):::tier3
    #tree_decomposition(["#트리 분할"]):::tier4
    #tree_compression(["#트리 압축"]):::tier3
    #pst(["#퍼시스턴트 세그먼트 트리"]):::tier4

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

### 3-3. 그래프

<pre class="mermaid">
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
    
    subgraph 최단 경로
        #shortest_path
        #dijkstra
        #bellman_ford
        #floyd_warshall
    end

    subgraph 유량 그래프
        #flow
        #mcmf
        #mfmc
        #bipartite_matching
    end

    #0_1_bfs(["#0-1 너비 우선 탐색"]):::tier2
    #2_sat(["#2-sat"]):::tier3
    #a_star(["#a*"]):::tier5
    #scc(["#강한 연결 요소"]):::tier3
    #graphs(["#그래프 이론"]):::tier2
    #articulation(["#단절점과 단절선"]):::tier3
    #dijkstra(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/01/dijkstra.html">#데이크스트라</a>"]):::tier2
    #dominator_tree(["#도미네이터 트리"]):::tier4
    #lgv(["#린드스트롬–게셀–비엔노 보조정리"]):::tier5
    #dag(["#방향 비순환 그래프"]):::tier2
    #bellman_ford(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/07/bellman_ford.html">#벨만–포드</a>"]):::tier2
    #circulation(["#서큘레이션"]):::tier4
    #cactus(["#선인장"]):::tier3
    #permutation_cycle_decomposition(["#순열 사이클 분할"]):::tier2
    #stoer_wagner(["#스토어–바그너"]):::tier4
    #dual_graph(["#쌍대 그래프"]):::tier4
    #stable_marriage(["#안정 결혼 문제"]):::tier3
    #eulerian_path(["#오일러 경로"]):::tier2
    #tsp(["#외판원 순회 문제"]):::tier2
    #topological_sorting(["#위상 정렬"]):::tier2
    #directed_mst(["#유향 최소 신장 트리"]):::tier4
    #bipartite_graph(["#이분 그래프"]):::tier2
    #bipartite_matching(["#이분 매칭"]):::tier3
    #biconnected_component(["#이중 연결 요소"]):::tier3
    #general_matching(["#일반적인 매칭"]):::tier5
    #degree_sequence(["#차수열"]):::tier2
    #shortest_path(["#최단 경로"]):::tier2
    #flow(["#최대 유량"]):::tier3
    #mfmc(["#최대 유량 최소 컷 정리"]):::tier3
    #mcmf(["#최소 비용 최대 유량"]):::tier3
    #mst(["#최소 스패닝 트리"]):::tier2
    #flood_fill(["#플러드 필"]):::tier2
    #floyd_warshall(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/07/floyd_warshall.html">#플로이드–워셜</a>"]):::tier2
    #functional_graph(["#함수형 그래프"]):::tier3
    #hungarian(["#헝가리안"]):::tier3
    #chordal_graph(["#현 그래프"]):::tier4
    #hall(["#홀의 결혼 정리"]):::tier4

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

### 3-4. 문자열

<pre class="mermaid">
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

    #kmp(["#KMP"]):::tier3
    #utf8(["#utf-8 입력 처리"]):::tier0
    #z(["#z"]):::tier3
    #rabin_karp(["#라빈–카프"]):::tier3
    #rope(["#로프"]):::tier4
    #manacher(["#매내처"]):::tier3
    #string(["#문자열"]):::tier0
    #aho_corasick(["#아호-코라식"]):::tier3
    #suffix_array(["#접미사 배열과 LCP 배열"]):::tier3
    #suffix_tree(["#접미사 트리"]):::tier5
    #regex(["#정규 표현식"]):::tier1
    #trie(["<span style="background-color: red; border-radius: 50%; display:inline-block; width:28px; height:28px">fa:fa-code</span> <a href="post/2024/01/03/trie.html">#트라이</a>"]):::tier3
    #parsing(["#파싱"]):::tier1
    #palindrome_tree(["#회문 트리"]):::tier4

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

### 3-5. 오프라인 쿼리

<pre class="mermaid">
    graph LR

    #offline_queries --> #sqrt_decomposition
    #offline_queries --> #prefix_sum
    #offline_queries --> #two_pointer
    #offline_queries --> #majority_vote
    #offline_queries --> #lis
    #two_pointer --> #mo
    #two_pointer --> #sliding_window
    #two_pointer --> #mitm
    #mitm --> #bidirectional_search

    #mo(["#mo's"]):::tier3
    #lis(["#가장 긴 증가하는 부분 수열: O(n log n)"]):::tier2
    #prefix_sum(["#누적 합"]):::tier2
    #two_pointer(["#두 포인터"]):::tier2
    #majority_vote(["#보이어–무어 다수결 투표"]):::tier2
    #sliding_window(["#슬라이딩 윈도우"]):::tier1
    #bidirectional_search(["#양방향 탐색"]):::tier3
    #offline_queries(["#오프라인 쿼리"]):::tier3
    #sqrt_decomposition(["#제곱근 분할법"]):::tier3
    #mitm(["#중간에서 만나기"]):::tier2

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

### 3-6. 수학

<pre class="mermaid">
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

    #gaussian_elimination(["#가우스 소거법"]):::tier3
    #game_theory(["#게임 이론"]):::tier2
    #gradient_descent(["#경사 하강법"]):::tier3
    #fft(["#고속 푸리에 변환"]):::tier4
    #green(["#그린 정리"]):::tier4
    #linearity_of_expectation(["#기댓값의 선형성"]):::tier2
    #geometry(["#기하학"]):::tier1
    #multipoint_evaluation(["#다중 대입값 계산"]):::tier5
    #polynomial_interpolation(["#다항식 보간법"]):::tier4
    #lucas(["#뤼카 정리"]):::tier3
    #matroid(["#매트로이드"]):::tier5
    #randomization(["#무작위화"]):::tier2
    #physics(["#물리학"]):::tier1
    #calculus(["#미적분학"]):::tier2
    #burnside(["#번사이드 보조정리"]):::tier3
    #bayes(["#베이즈 정리"]):::tier3
    #exponentiation_by_squaring(["#분할 정복을 이용한 거듭제곱"]):::tier2
    #pigeonhole_principle(["#비둘기집 원리"]):::tier1
    #arithmetic(["#사칙연산"]):::tier0
    #ternary_search(["#삼분 탐색"]):::tier2
    #generating_function(["#생성 함수"]):::tier4
    #birthday(["#생일 문제"]):::tier2
    #linear_programming(["#선형 계획법"]):::tier4
    #linear_algebra(["#선형대수학"]):::tier3
    #numerical_analysis(["#수치해석"]):::tier3
    #math(["#수학"]):::tier1
    #sprague_grundy(["#스프라그–그런디 정리"]):::tier3
    #duality(["#쌍대성"]):::tier4
    #discrete_kth_root(["#이산 k제곱근"]):::tier3
    #discrete_log(["#이산 로그"]):::tier4
    #discrete_sqrt(["#이산 제곱근"]):::tier4
    #arbitrary_precision(["#임의 정밀도 / 큰 수 연산"]):::tier1
    #number_theory(["#정수론"]):::tier1
    #combinatorics(["#조합론"]):::tier2
    #differential_cryptanalysis(["#차분 공격"]):::tier1
    #statistics(["#통계학"]):::tier2
    #inclusion_and_exclusion(["#포함 배제의 원리"]):::tier2
    #hackenbush(["#하켄부시 게임"]):::tier5
    #probability(["#확률론"]):::tier2
    #sparse_table(["#희소 배열"]):::tier3

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

#### 3-6-1. 정수론

<pre class="mermaid">
    graph LR

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

    #modular_multiplicative_inverse(["#모듈로 곱셈 역원"]):::tier2
    #mobius_inversion(["#뫼비우스 반전 공식"]):::tier4
    #miller_rabin(["#밀러–라빈 소수 판별법"]):::tier3
    #primality_test(["#소수 판정"]):::tier1
    #sieve(["#에라토스테네스의 체"]):::tier1
    #euler_phi(["#오일러 피 함수"]):::tier3
    #euclidean(["#유클리드 호제법"]):::tier1
    #number_theory(["#정수론"]):::tier1
    #crt(["#중국인의 나머지 정리"]):::tier3
    #lte(["#지수승강 보조정리"]):::tier4
    #flt(["#페르마의 소정리"]):::tier2
    #pollard_rho(["#폴라드 로"]):::tier3
    #extended_euclidean(["#확장 유클리드 호제법"]):::tier3

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

#### 3-6-2. 기하

<pre class="mermaid">
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

    #geometry_3d(["#3차원 기하학"]):::tier1
    #geometry_hyper(["#4차원 이상의 기하학"]):::tier2
    #coordinate_compression(["#값 / 좌표 압축"]):::tier2
    #geometry(["#기하학"]):::tier1
    #polygon_area(["#다각형의 넓이"]):::tier2
    #delaunay(["#델로네 삼각분할"]):::tier5
    #geometric_boolean_operations(["#도형에서의 불 연산"]):::tier5
    #half_plane_intersection(["#반평면 교집합"]):::tier4
    #voronoi(["#보로노이 다이어그램"]):::tier3
    #convex_hull(["#볼록 껍질"]):::tier3
    #point_in_convex_polygon(["#볼록 다각형 내부의 점 판정"]):::tier3
    #line_intersection(["#선분 교차 판정"]):::tier2
    #sweeping(["#스위핑"]):::tier2
    #point_in_non_convex_polygon(["#오목 다각형 내부의 점 판정"]):::tier3
    #euler_characteristic(["#오일러 지표 (χ=V-E+F)"]):::tier3
    #min_enclosing_circle(["#최소 외접원"]):::tier3
    #planar_graph(["#평면 그래프"]):::tier3
    #pythagoras(["#피타고라스 정리"]):::tier0
    #pick(["#픽의 정리"]):::tier2
    #rotating_calipers(["#회전하는 캘리퍼스"]):::tier3

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

### 3-7. 최적화 및 기법

<pre class="mermaid">
    graph LR

    #dp --> #knapsack
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
    #bitset --> #dp_bitfield
    #bitset --> #dp_sum_over_subsets
    #backtracking --> #dancing_links
    #dancing_links --> #knuth_x
    #heuristics --> #simulated_annealing

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

    #alien(["#Aliens 트릭"]):::tier4
    #dp(["#다이나믹 프로그래밍"]):::tier2
    #monotone_queue_optimization(["#단조 큐를 이용한 최적화"]):::tier4
    #simulated_annealing(["#담금질 기법"]):::tier3
    #deque_trick(["#덱을 이용한 구간 최댓값 트릭"]):::tier3
    #dp_deque(["#덱을 이용한 다이나믹 프로그래밍"]):::tier3
    #knapsack(["#배낭 문제"]):::tier2
    #backtracking(["#백트래킹"]):::tier1
    #berlekamp_massey(["#벌리캠프–매시"]):::tier3
    #cht(["#볼록 껍질을 이용한 최적화"]):::tier3
    #dp_sum_over_subsets(["#부분집합의 합 다이나믹 프로그래밍"]):::tier4
    #divide_and_conquer_optimization(["#분할 정복을 사용한 최적화"]):::tier4
    #bitset(["#비트 집합"]):::tier3
    #bitmask(["#비트마스킹"]):::tier2
    #dp_bitfield(["#비트필드를 이용한 다이나믹 프로그래밍"]):::tier3
    #dp_digit(["#자릿수를 이용한 다이나믹 프로그래밍"]):::tier3
    #dancing_links(["#춤추는 링크"]):::tier4
    #dp_connection_profile(["#커넥션 프로파일을 이용한 다이나믹 프로그래밍"]):::tier4
    #knuth_x(["#크누스 X"]):::tier4
    #knuth(["#크누스 최적화"]):::tier4
    #kitamasa(["#키타마사"]):::tier4
    #dp_tree(["#트리에서의 다이나믹 프로그래밍"]):::tier3
    #slope_trick(["#함수 개형을 이용한 최적화"]):::tier4
    #heuristics(["#휴리스틱"]):::tier2
    #hirschberg(["#히르쉬버그"]):::tier4

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>

<hr style="margin-top: 50pt; margin-bottom: 50pt">

## A. 미분류

<pre class="mermaid">
    graph LR

    #implementation --> #case_work
    #implementation --> #simulation
    #constructive --> #precomputation
    #constructive <--> #ad_hoc

    #implementation(["#구현"]):::tier0
    #precomputation(["#런타임 전의 전처리"]):::tier1
    #case_work(["#많은 조건 분기"]):::tier1
    #simulation(["#시뮬레이션"]):::tier0
    #ad_hoc(["#애드 혹"]):::tier2
    #constructive(["#해 구성하기"]):::tier2

    classDef tier0 fill:#ad5600, color:#fff, stroke:#0000
    classDef tier1 fill:#435f7a, color:#fff, stroke:#0000
    classDef tier2 fill:#ec9a00, color:#fff, stroke:#0000
    classDef tier3 fill:#27e2a4, color:#fff, stroke:#0000
    classDef tier4 fill:#00b4fc, color:#fff, stroke:#0000
    classDef tier5 fill:#ff0062, color:#fff, stroke:#0000
</pre>
