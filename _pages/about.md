---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<meta charset="UTF-8">
<title>Musical Interests</title>
<head>
    <meta charset="UTF-8">
    <title>Musical Interests</title>
    <style>
        /* Style for the clickable text */
        .clickable {
            color: magenta;
            cursor: pointer;
            text-decoration: underline;
        }
        /* Hide the video section initially */
        #videoSection {
            display: none;
            margin-top: 20px;
        }
        /* Hide the details section initially */
        #bugDetails {
            display: none;
            margin-top: 10px;
        }
        iframe {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>

Yuancheng Jiang is a Ph.D. candidate at the [School of Computing](https://www.comp.nus.edu.sg/), [National University of Singapore](https://nus.edu.sg/)<img src="./images/nus.jpg" style="width: 1.5em;" />, co-supervised by Prof. [Zhenkai Liang](https://www.comp.nus.edu.sg/~liangzk/) and Prof. [Roland Yap](https://www.comp.nus.edu.sg/cs/people/ryap/), with a research focus on system security. He collaborates with Prof. [Manuel Rigger](https://manuelrigger.at/) on fuzz testing. Prior to his Ph.D. studies, he completed his Master's degree at National University of Singapore and his Bachelor's degree at [Fudan University](https://www.fudan.edu.cn/en/)<img src="./images/fdu.png" style="width: 1.5em;" />.

# 🔥 News
- *Jan. 2025*: &nbsp;🎉🎉 Our work on fuzzing the PHP interpreter by dataflow fusion is accepted in Security'25!
- *Feb. 2024*: &nbsp;🎉🎉 Our work on evaluating disassemblers via dynamic tracing is accepted in NDSS BAR'24!
- *Aug. 2023*: &nbsp;🎉🎉 Our work on detecting logic bugs in graph database engines is accepted in ICSE'24!

# 📝 Publications 

**[Preprint] Enhanced Differential Testing in Emerging Database Systems**

<ins>Yuancheng Jiang</ins>, Jianing Wang, Chuqi Zhang, Roland Yap, Zhenkai Liang, Manuel Rigger

[Paper](https://arxiv.org/pdf/2501.01236) 丨 [Code](https://github.com/YuanchengJiang/SQLxDiff) 丨 Slides 丨 [Bugs](https://github.com/questdb/questdb/issues?q=is%3Aissue%20author%3AYuanchengJiang%20)

**Fuzzing the PHP Interpreter via Dataflow Fusion**

<ins>Yuancheng Jiang</ins>, Chuqi Zhang, Bonan Ruan, Jiahao Liu, Manuel Rigger, Roland Yap, Zhenkai Liang

In the 34th USENIX Security Symposium ``USENIX Security 2025``, [Accepted Rate: Unknown] 

[Paper](https://yuanchengjiang.github.io/docs/flowfusion.pdf) 丨 [Code](https://github.com/php/flowfusion) 丨 Slides 丨 [Bugs (we reported over 300 bug issues!)](https://github.com/php/php-src/issues?q=is%3Aissue%20author%3AYuanchengJiang%20)

**Evaluating Disassembly Ground Truth Through Dynamic Tracing**

Lambang Akbar, <ins>Yuancheng Jiang</ins>, Roland Yap, Zhenkai Liang, Zhuohao Liu

In the Workshop on Binary Analysis Research co-located with NDSS Symposium ``NDSS BAR 2024``, [Accepted Rate: Unknown] 

Paper 丨 Code 丨 Slides

**Detecting Logic Bugs in Graph Database Management Systems via Injective and Surjective Graph Query Transformation**

<ins>Yuancheng Jiang</ins>, Jiahao Liu, Jinsheng Ba, Roland Yap, Zhenkai Liang, Manuel Rigger 

In the 46th International Conference on Software Engineering ``ICSE 2024``, [Accepted Rate: 22%] 

[Paper](https://yuanchengjiang.github.io/docs/GraphGenie-ICSE24.pdf) 丨 [Code](https://github.com/YuanchengJiang/GraphGenie) 丨 [Slides](https://yuanchengjiang.github.io/docs/GraphGenie_slides.pdf) 丨 [Bugs](https://github.com/neo4j/neo4j/issues?q=is%3Aissue%20author%3AYuanchengJiang%20)

**Extensible Virtual Call Integrity**

<ins>Yuancheng Jiang</ins>, Gregory J. Duck, Roland Yap, Zhenkai Liang, Pinghai Yuan 

In the 27th European Symposium on Research in Computer Security ``ESORICS 2022``, [Accepted Rate: 18.5%] 

[Paper](https://yuanchengjiang.github.io/docs/esorics22-evcfi.pdf) 丨 Code 丨 [Slides](https://yuanchengjiang.github.io/docs/EVCFI_slides.pdf)
 
**FlowMatrix: GPU-Assisted Information-Flow Analysis through Matrix-Based Representation** 

Kaihang Ji, Jun Zeng, <ins>Yuancheng Jiang</ins>, Zhenkai Liang, Zheng Leong Chua, Prateek Saxena and Abhik Roychoudhury 

In Proceedings of the 31st USENIX Security Symposium ``Usenix Security 2022``, [Accepted Rate: 18.1%] 

[Paper](https://www.usenix.org/system/files/sec22-ji.pdf) 丨 [Code](https://github.com/mimicji/FlowMatrix) 丨 [Slides](https://yuanchengjiang.github.io/docs/flowmatrix_slides.pdf)

**RecIPE: Revisiting the Evaluation of Memory Error Defenses**

<ins>Yuancheng Jiang</ins>, Roland Yap, Zhenkai Liang, Hubert Rosier

In the 17th ACM ASIA Conference on Computer and Communications Security ``AsiaCCS 2022``, [Accepted Rate: 18.4%]

[Paper](https://dl.acm.org/doi/pdf/10.1145/3488932.3524127) 丨 [Code](https://github.com/YuanchengJiang/recipe-benchmark) 丨 [Slides](https://yuanchengjiang.github.io/docs/RecIPE_slides.pdf)

<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📖 Educations
- *Jan. 2022 ~ present*, Ph.D. in Computer Science, National University of Singapore
- *Aug. 2020 ~ Dec. 2021*, Master of Computing, National University of Singapore
- *Sept. 2016 ~ Jul. 2020*, Bachelor of Engineering in Information Security, Fudan University

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Experiences
- *Jun. 2019 ~ Aug. 2019*, Summer Internship, Huawei, Shanghai
- *2017 ~ 2020*, Capture The Flag (CTF), Member of Fudan [Sixstars](https://github.com/sixstars)

<!--
# 🐞 Bugs
Our research efforts have been rewarded with hundreds of bugs (crashes/errors🔴, wrong results🟡) as follows:
- [The PHP Interpreter](https://github.com/php/php-src) (38.2k⭐): <span id="bugCount" class="clickable">219 bugs</span>
<div id="bugDetails"> 
[#16711🔴](https://github.com/php/php-src/issues/16711), [#16645🔴](https://github.com/php/php-src/issues/16645), [#16637🟡](https://github.com/php/php-src/issues/16637), [#16636🟡](https://github.com/php/php-src/issues/16636), [#16635🔴](https://github.com/php/php-src/issues/16635), [#16634🔴](https://github.com/php/php-src/issues/16634), [#16633🔴](https://github.com/php/php-src/issues/16633), [#16632🔴](https://github.com/php/php-src/issues/16632), [#16631🔴](https://github.com/php/php-src/issues/16631), [#16630🔴](https://github.com/php/php-src/issues/16630), [#16620🔴](https://github.com/php/php-src/issues/16620), [#16618🟡](https://github.com/php/php-src/issues/16618), [#16578🔴](https://github.com/php/php-src/issues/16578), [#16574🟡](https://github.com/php/php-src/issues/16574), [#16572🟡](https://github.com/php/php-src/issues/16572), [#16559🔴](https://github.com/php/php-src/issues/16559), [#16526🔴](https://github.com/php/php-src/issues/16526), [#16515🔴](https://github.com/php/php-src/issues/16515), [#16514🔴](https://github.com/php/php-src/issues/16514), [#16509🟡](https://github.com/php/php-src/issues/16509), [#16504🔴](https://github.com/php/php-src/issues/16504), [#16502🔴](https://github.com/php/php-src/issues/16502), [#16501🔴](https://github.com/php/php-src/issues/16501), [#16500🔴](https://github.com/php/php-src/issues/16500), [#16496🔴](https://github.com/php/php-src/issues/16496), [#16495🟡](https://github.com/php/php-src/issues/16495), [#16487🟡](https://github.com/php/php-src/issues/16487), [#16477🔴](https://github.com/php/php-src/issues/16477), [#16473🟡](https://github.com/php/php-src/issues/16473), [#16472🟡](https://github.com/php/php-src/issues/16472), [#16454🔴](https://github.com/php/php-src/issues/16454), [#16453🔴](https://github.com/php/php-src/issues/16453), [#16435🟡](https://github.com/php/php-src/issues/16435), [#16433🔴](https://github.com/php/php-src/issues/16433), [#16431🔴](https://github.com/php/php-src/issues/16431), [#16430🔴](https://github.com/php/php-src/issues/16430), [#16429🔴](https://github.com/php/php-src/issues/16429), [#16414🔴](https://github.com/php/php-src/issues/16414), [#16413🔴](https://github.com/php/php-src/issues/16413), [#16412🔴](https://github.com/php/php-src/issues/16412), [#16411🔴](https://github.com/php/php-src/issues/16411), [#16410🟡](https://github.com/php/php-src/issues/16410), [#16409🟡](https://github.com/php/php-src/issues/16409), [#16408🟡](https://github.com/php/php-src/issues/16408), [#16406🔴](https://github.com/php/php-src/issues/16406), [#16405🔴](https://github.com/php/php-src/issues/16405), [#16404🟡](https://github.com/php/php-src/issues/16404), [#16397🔴](https://github.com/php/php-src/issues/16397), [#16396🟡](https://github.com/php/php-src/issues/16396), [#16394🔴](https://github.com/php/php-src/issues/16394), [#16393🔴](https://github.com/php/php-src/issues/16393), [#16390🔴](https://github.com/php/php-src/issues/16390), [#16389🔴](https://github.com/php/php-src/issues/16389), [#16388🔴](https://github.com/php/php-src/issues/16388), [#16387🟡](https://github.com/php/php-src/issues/16387), [#16385🟡](https://github.com/php/php-src/issues/16385), [#16371🔴](https://github.com/php/php-src/issues/16371), [#16360🔴](https://github.com/php/php-src/issues/16360), [#16359🔴](https://github.com/php/php-src/issues/16359), [#16358🔴](https://github.com/php/php-src/issues/16358), [#16357🔴](https://github.com/php/php-src/issues/16357), [#16356🔴](https://github.com/php/php-src/issues/16356), [#16355🔴](https://github.com/php/php-src/issues/16355), [#16354🔴](https://github.com/php/php-src/issues/16354), [#16326🔴](https://github.com/php/php-src/issues/16326), [#16325🔴](https://github.com/php/php-src/issues/16325), [#16324🔴](https://github.com/php/php-src/issues/16324), [#16323🔴](https://github.com/php/php-src/issues/16323), [#16322🔴](https://github.com/php/php-src/issues/16322), [#16321🔴](https://github.com/php/php-src/issues/16321), [#16320🔴](https://github.com/php/php-src/issues/16320), [#16319🔴](https://github.com/php/php-src/issues/16319), [#16318🟡](https://github.com/php/php-src/issues/16318), [#16294🔴](https://github.com/php/php-src/issues/16294), [#16293🔴](https://github.com/php/php-src/issues/16293), [#16292🔴](https://github.com/php/php-src/issues/16292), [#16267🔴](https://github.com/php/php-src/issues/16267), [#16266🔴](https://github.com/php/php-src/issues/16266), [#16265🔴](https://github.com/php/php-src/issues/16265), [#16262🔴](https://github.com/php/php-src/issues/16262), [#16261🔴](https://github.com/php/php-src/issues/16261), [#16260🔴](https://github.com/php/php-src/issues/16260), [#16259🔴](https://github.com/php/php-src/issues/16259), [#16258🔴](https://github.com/php/php-src/issues/16258), [#16257🔴](https://github.com/php/php-src/issues/16257), [#16256🔴](https://github.com/php/php-src/issues/16256), [#16255🔴](https://github.com/php/php-src/issues/16255), [#16237🔴](https://github.com/php/php-src/issues/16237), [#16236🔴](https://github.com/php/php-src/issues/16236), [#16235🔴](https://github.com/php/php-src/issues/16235), [#16234🔴](https://github.com/php/php-src/issues/16234), [#16233🔴](https://github.com/php/php-src/issues/16233), [#16232🔴](https://github.com/php/php-src/issues/16232), [#16231🔴](https://github.com/php/php-src/issues/16231), [#16230🔴](https://github.com/php/php-src/issues/16230), [#16229🔴](https://github.com/php/php-src/issues/16229), [#16228🔴](https://github.com/php/php-src/issues/16228), [#16214🔴](https://github.com/php/php-src/issues/16214), [#16212🔴](https://github.com/php/php-src/issues/16212), [#16190🔴](https://github.com/php/php-src/issues/16190), [#16189🔴](https://github.com/php/php-src/issues/16189), [#16188🔴](https://github.com/php/php-src/issues/16188), [#16187🔴](https://github.com/php/php-src/issues/16187), [#16186🔴](https://github.com/php/php-src/issues/16186), [#16185🔴](https://github.com/php/php-src/issues/16185), [#16184🔴](https://github.com/php/php-src/issues/16184), [#16128🔴](https://github.com/php/php-src/issues/16128), [#16054🔴](https://github.com/php/php-src/issues/16054), [#16053🔴](https://github.com/php/php-src/issues/16053), [#16041🔴](https://github.com/php/php-src/issues/16041), [#16040🔴](https://github.com/php/php-src/issues/16040), [#16039🔴](https://github.com/php/php-src/issues/16039), [#16037🔴](https://github.com/php/php-src/issues/16037), [#16009🔴](https://github.com/php/php-src/issues/16009), [#16000🔴](https://github.com/php/php-src/issues/16000), [#15982🔴](https://github.com/php/php-src/issues/15982), [#15981🔴](https://github.com/php/php-src/issues/15981), [#15980🔴](https://github.com/php/php-src/issues/15980), [#15973🔴](https://github.com/php/php-src/issues/15973), [#15972🔴](https://github.com/php/php-src/issues/15972), [#15943🔴](https://github.com/php/php-src/issues/15943), [#15918🔴](https://github.com/php/php-src/issues/15918), [#15917🔴](https://github.com/php/php-src/issues/15917), [#15914🔴](https://github.com/php/php-src/issues/15914), [#15911🔴](https://github.com/php/php-src/issues/15911), [#15910🔴](https://github.com/php/php-src/issues/15910), [#15909🔴](https://github.com/php/php-src/issues/15909), [#15908🔴](https://github.com/php/php-src/issues/15908), [#15907🔴](https://github.com/php/php-src/issues/15907), [#15906🔴](https://github.com/php/php-src/issues/15906), [#15905🔴](https://github.com/php/php-src/issues/15905), [#15904🔴](https://github.com/php/php-src/issues/15904), [#15903🔴](https://github.com/php/php-src/issues/15903), [#15902🔴](https://github.com/php/php-src/issues/15902), [#15901🔴](https://github.com/php/php-src/issues/15901), [#15900🔴](https://github.com/php/php-src/issues/15900), [#15869🔴](https://github.com/php/php-src/issues/15869), [#15868🔴](https://github.com/php/php-src/issues/15868), [#15867🔴](https://github.com/php/php-src/issues/15867), [#15866🔴](https://github.com/php/php-src/issues/15866), [#15837🔴](https://github.com/php/php-src/issues/15837), [#15836🔴](https://github.com/php/php-src/issues/15836), [#15833🔴](https://github.com/php/php-src/issues/15833), [#15823🔴](https://github.com/php/php-src/issues/15823), [#15821🔴](https://github.com/php/php-src/issues/15821), [#15820🔴](https://github.com/php/php-src/issues/15820), [#15712🔴](https://github.com/php/php-src/issues/15712), [#15672🔴](https://github.com/php/php-src/issues/15672), [#15670🔴](https://github.com/php/php-src/issues/15670), [#15662🔴](https://github.com/php/php-src/issues/15662), [#15661🔴](https://github.com/php/php-src/issues/15661), [#15658🔴](https://github.com/php/php-src/issues/15658), [#15657🔴](https://github.com/php/php-src/issues/15657), [#15654🔴](https://github.com/php/php-src/issues/15654), [#15653🔴](https://github.com/php/php-src/issues/15653), [#15652🔴](https://github.com/php/php-src/issues/15652), [#15613🔴](https://github.com/php/php-src/issues/15613), [#15582🔴](https://github.com/php/php-src/issues/15582), [#15570🔴](https://github.com/php/php-src/issues/15570), [#15552🔴](https://github.com/php/php-src/issues/15552), [#15551🔴](https://github.com/php/php-src/issues/15551), [#15496🔴](https://github.com/php/php-src/issues/15496), [#15490🔴](https://github.com/php/php-src/issues/15490), [#15481🔴](https://github.com/php/php-src/issues/15481), [#15456🔴](https://github.com/php/php-src/issues/15456), [#15268🔴](https://github.com/php/php-src/issues/15268), [#15210🔴](https://github.com/php/php-src/issues/15210), [#15208🔴](https://github.com/php/php-src/issues/15208), [#15192🔴](https://github.com/php/php-src/issues/15192), [#15187🔴](https://github.com/php/php-src/issues/15187), [#15181🔴](https://github.com/php/php-src/issues/15181), [#15179🔴](https://github.com/php/php-src/issues/15179), [#15169🔴](https://github.com/php/php-src/issues/15169), [#15168🔴](https://github.com/php/php-src/issues/15168), [#15150🔴](https://github.com/php/php-src/issues/15150), [#15137🔴](https://github.com/php/php-src/issues/15137), [#14808🔴](https://github.com/php/php-src/issues/14808), [#14807🔴](https://github.com/php/php-src/issues/14807), [#14780🔴](https://github.com/php/php-src/issues/14780), [#14775🔴](https://github.com/php/php-src/issues/14775), [#14774🔴](https://github.com/php/php-src/issues/14774), [#14741🔴](https://github.com/php/php-src/issues/14741), [#14732🔴](https://github.com/php/php-src/issues/14732), [#14712🔴](https://github.com/php/php-src/issues/14712), [#14709🔴](https://github.com/php/php-src/issues/14709), [#14698🔴](https://github.com/php/php-src/issues/14698), [#14687🔴](https://github.com/php/php-src/issues/14687), [#14652🔴](https://github.com/php/php-src/issues/14652), [#14643🔴](https://github.com/php/php-src/issues/14643), [#14639🔴](https://github.com/php/php-src/issues/14639), [#14638🔴](https://github.com/php/php-src/issues/14638), [#14637🔴](https://github.com/php/php-src/issues/14637), [#14603🔴](https://github.com/php/php-src/issues/14603), [#14373🔴](https://github.com/php/php-src/issues/14373), [#14361🔴](https://github.com/php/php-src/issues/14361), [#14343🔴](https://github.com/php/php-src/issues/14343), [#14290🔴](https://github.com/php/php-src/issues/14290), [#14164🔴](https://github.com/php/php-src/issues/14164), [#14124🔴](https://github.com/php/php-src/issues/14124), [#14082🔴](https://github.com/php/php-src/issues/14082), [#14075🔴](https://github.com/php/php-src/issues/14075), [#14049🔴](https://github.com/php/php-src/issues/14049), [#14044🔴](https://github.com/php/php-src/issues/14044), [#13998🔴](https://github.com/php/php-src/issues/13998), [#13984🔴](https://github.com/php/php-src/issues/13984), [#13931🔴](https://github.com/php/php-src/issues/13931), [#13903🔴](https://github.com/php/php-src/issues/13903), [#13881🔴](https://github.com/php/php-src/issues/13881), [#13856🔴](https://github.com/php/php-src/issues/13856), [#13836🔴](https://github.com/php/php-src/issues/13836), [#13834🔴](https://github.com/php/php-src/issues/13834), [#13833🔴](https://github.com/php/php-src/issues/13833), [#13827🔴](https://github.com/php/php-src/issues/13827), [#13768🔴](https://github.com/php/php-src/issues/13768), [#13695🔴](https://github.com/php/php-src/issues/13695), [#13685🔴](https://github.com/php/php-src/issues/13685), [#13681🔴](https://github.com/php/php-src/issues/13681), [#13680🔴](https://github.com/php/php-src/issues/13680), [#13671🔴](https://github.com/php/php-src/issues/13671)
</div>
- [Neo4j](https://github.com/neo4j/neo4j) (13.4k⭐): [#13249🟡](https://github.com/neo4j/neo4j/issues/13249), [#13051🟡](https://github.com/neo4j/neo4j/issues/13051), [#13041🔴](https://github.com/neo4j/neo4j/issues/13041), [#13034🟡](https://github.com/neo4j/neo4j/issues/13034), [#13033🟡](https://github.com/neo4j/neo4j/issues/13033), [#13010🟡](https://github.com/neo4j/neo4j/issues/13010), [#13003🟡](https://github.com/neo4j/neo4j/issues/13003), [#13002🔴](https://github.com/neo4j/neo4j/issues/13002), [#12996🟡](https://github.com/neo4j/neo4j/issues/12996), [#12991🟡](https://github.com/neo4j/neo4j/issues/12991), [#12990🟡](https://github.com/neo4j/neo4j/issues/12990), [#12988🟡](https://github.com/neo4j/neo4j/issues/12988), [#12984🟡](https://github.com/neo4j/neo4j/issues/12984), [#12983🟡](https://github.com/neo4j/neo4j/issues/12983), [#12978🟡](https://github.com/neo4j/neo4j/issues/12978), [#12977🟡](https://github.com/neo4j/neo4j/issues/12977), [#12973🟡](https://github.com/neo4j/neo4j/issues/12973), [#12968🔴](https://github.com/neo4j/neo4j/issues/12968), [#12960🟡](https://github.com/neo4j/neo4j/issues/12960), [#12957🟡](https://github.com/neo4j/neo4j/issues/12957), [#13249🟡](https://github.com/neo4j/neo4j/issues/13249), [#13051🟡](https://github.com/neo4j/neo4j/issues/13051), [#13041🟡](https://github.com/neo4j/neo4j/issues/13041), [#13034🟡](https://github.com/neo4j/neo4j/issues/13034), [#13033🟡](https://github.com/neo4j/neo4j/issues/13033), [#13010🟡](https://github.com/neo4j/neo4j/issues/13010), [#13003🟡](https://github.com/neo4j/neo4j/issues/13003), [#13002🟡](https://github.com/neo4j/neo4j/issues/13002), [#12996🟡](https://github.com/neo4j/neo4j/issues/12996), [#12991🟡](https://github.com/neo4j/neo4j/issues/12991), [#12990🟡](https://github.com/neo4j/neo4j/issues/12990), [#12988🟡](https://github.com/neo4j/neo4j/issues/12988), [#12984🟡](https://github.com/neo4j/neo4j/issues/12984), [#12983🟡](https://github.com/neo4j/neo4j/issues/12983), [#12978🟡](https://github.com/neo4j/neo4j/issues/12978), [#12977🟡](https://github.com/neo4j/neo4j/issues/12977), [#12973🟡](https://github.com/neo4j/neo4j/issues/12973), [#12968🟡](https://github.com/neo4j/neo4j/issues/12968), [#12960🟡](https://github.com/neo4j/neo4j/issues/12960), [#12957🟡](https://github.com/neo4j/neo4j/issues/12957)
- [QuestDB](https://github.com/questdb/questdb) (14.6k⭐): [#4531🟡](https://github.com/questdb/questdb/issues/4531), [#4528🟡](https://github.com/questdb/questdb/issues/4528), [#4505🟡](https://github.com/questdb/questdb/issues/4505), [#4496🟡](https://github.com/questdb/questdb/issues/4496), [#4010🟡](https://github.com/questdb/questdb/issues/4010), [#3949🔴](https://github.com/questdb/questdb/issues/3949), [#3938🟡](https://github.com/questdb/questdb/issues/3938), [#3936🟡](https://github.com/questdb/questdb/issues/3936), [#3935🔴](https://github.com/questdb/questdb/issues/3935), [#3934🟡](https://github.com/questdb/questdb/issues/3934), [#3933🟡](https://github.com/questdb/questdb/issues/3933), [#3932🟡](https://github.com/questdb/questdb/issues/3932), [#3833🔴](https://github.com/questdb/questdb/issues/3833), [#3828🟡](https://github.com/questdb/questdb/issues/3828), [#3733🟡](https://github.com/questdb/questdb/issues/3733), [#3670🟡](https://github.com/questdb/questdb/issues/3670), [#3669🟡](https://github.com/questdb/questdb/issues/3669), [#3623🔴](https://github.com/questdb/questdb/issues/3623), [#3622🔴](https://github.com/questdb/questdb/issues/3622), [#3619🟡](https://github.com/questdb/questdb/issues/3619), [#3595🟡](https://github.com/questdb/questdb/issues/3595), [#3590🔴](https://github.com/questdb/questdb/issues/3590), [#3581🟡](https://github.com/questdb/questdb/issues/3581), [#3580🟡](https://github.com/questdb/questdb/issues/3580), [#3576🔴](https://github.com/questdb/questdb/issues/3576), [#3575🟡](https://github.com/questdb/questdb/issues/3575), [#3526🔴](https://github.com/questdb/questdb/issues/3526), [#3470🔴](https://github.com/questdb/questdb/issues/3470), [#3469🔴](https://github.com/questdb/questdb/issues/3469), [#3468🔴](https://github.com/questdb/questdb/issues/3468), [#3467🔴](https://github.com/questdb/questdb/issues/3467), [#3455🔴](https://github.com/questdb/questdb/issues/3455), [#3454🔴](https://github.com/questdb/questdb/issues/3454), [#3445🔴](https://github.com/questdb/questdb/issues/3445), [#3433🔴](https://github.com/questdb/questdb/issues/3433), [#3420🔴](https://github.com/questdb/questdb/issues/3420), [#3419🔴](https://github.com/questdb/questdb/issues/3419), [#3418🔴](https://github.com/questdb/questdb/issues/3418), [#3386🔴](https://github.com/questdb/questdb/issues/3386), [#3376🔴](https://github.com/questdb/questdb/issues/3376), [#3358🟡](https://github.com/questdb/questdb/issues/3358), [#3357🔴](https://github.com/questdb/questdb/issues/3357), [#3356🔴](https://github.com/questdb/questdb/issues/3356), [#3324🔴](https://github.com/questdb/questdb/issues/3324), [#3323🔴](https://github.com/questdb/questdb/issues/3323), [#3322🔴](https://github.com/questdb/questdb/issues/3322), [#3313🟡](https://github.com/questdb/questdb/issues/3313), [#4531🟡](https://github.com/questdb/questdb/issues/4531), [#4528🟡](https://github.com/questdb/questdb/issues/4528), [#4505🟡](https://github.com/questdb/questdb/issues/4505), [#4496🟡](https://github.com/questdb/questdb/issues/4496), [#4010🟡](https://github.com/questdb/questdb/issues/4010), [#3949🟡](https://github.com/questdb/questdb/issues/3949), [#3938🟡](https://github.com/questdb/questdb/issues/3938), [#3936🟡](https://github.com/questdb/questdb/issues/3936), [#3935🟡](https://github.com/questdb/questdb/issues/3935), [#3934🟡](https://github.com/questdb/questdb/issues/3934), [#3933🟡](https://github.com/questdb/questdb/issues/3933), [#3932🟡](https://github.com/questdb/questdb/issues/3932), [#3833🟡](https://github.com/questdb/questdb/issues/3833), [#3828🟡](https://github.com/questdb/questdb/issues/3828), [#3733🟡](https://github.com/questdb/questdb/issues/3733), [#3670🟡](https://github.com/questdb/questdb/issues/3670), [#3669🟡](https://github.com/questdb/questdb/issues/3669), [#3623🟡](https://github.com/questdb/questdb/issues/3623), [#3622🟡](https://github.com/questdb/questdb/issues/3622), [#3619🟡](https://github.com/questdb/questdb/issues/3619), [#3595🟡](https://github.com/questdb/questdb/issues/3595), [#3590🟡](https://github.com/questdb/questdb/issues/3590), [#3581🟡](https://github.com/questdb/questdb/issues/3581), [#3580🟡](https://github.com/questdb/questdb/issues/3580), [#3576🟡](https://github.com/questdb/questdb/issues/3576), [#3575🟡](https://github.com/questdb/questdb/issues/3575), [#3526🟡](https://github.com/questdb/questdb/issues/3526), [#3470🟡](https://github.com/questdb/questdb/issues/3470), [#3469🟡](https://github.com/questdb/questdb/issues/3469), [#3468🟡](https://github.com/questdb/questdb/issues/3468), [#3467🟡](https://github.com/questdb/questdb/issues/3467), [#3455🟡](https://github.com/questdb/questdb/issues/3455), [#3454🟡](https://github.com/questdb/questdb/issues/3454), [#3445🟡](https://github.com/questdb/questdb/issues/3445), [#3433🟡](https://github.com/questdb/questdb/issues/3433), [#3420🟡](https://github.com/questdb/questdb/issues/3420), [#3419🟡](https://github.com/questdb/questdb/issues/3419), [#3418🟡](https://github.com/questdb/questdb/issues/3418), [#3386🟡](https://github.com/questdb/questdb/issues/3386), [#3376🟡](https://github.com/questdb/questdb/issues/3376), [#3358🟡](https://github.com/questdb/questdb/issues/3358), [#3357🟡](https://github.com/questdb/questdb/issues/3357), [#3356🟡](https://github.com/questdb/questdb/issues/3356), [#3324🟡](https://github.com/questdb/questdb/issues/3324), [#3323🟡](https://github.com/questdb/questdb/issues/3323), [#3322🟡](https://github.com/questdb/questdb/issues/3322), [#3313🟡](https://github.com/questdb/questdb/issues/3313)
- [RedisGraph](https://github.com/RedisGraph/RedisGraph) (2.0k⭐): [#2744🟡](https://github.com/RedisGraph/RedisGraph/issues/2744), [#2858🟡](https://github.com/RedisGraph/RedisGraph/issues/2858), [#2859🟡](https://github.com/RedisGraph/RedisGraph/issues/2859), [#2865🟡](https://github.com/RedisGraph/RedisGraph/issues/2865), [#3071🔴](https://github.com/RedisGraph/RedisGraph/issues/3071)
- [AgensGraph](https://github.com/bitnine-oss/agensgraph) (1.3k⭐): [#595🟡](https://github.com/bitnine-oss/agensgraph/issues/595), [#609🟡](https://github.com/bitnine-oss/agensgraph/issues/609), [#617🟡](https://github.com/bitnine-oss/agensgraph/issues/617)
- [CrateDB](https://github.com/crate/crate) (4.1k⭐): [#14805🔴](https://github.com/crate/crate/issues/14805), [#14807🟡](https://github.com/crate/crate/issues/14807)
-->

# 🎸 Music
He has completed the [ABRSM](https://www.abrsm.org/)<img src="./images/abrsm.jpg" style="width: 1.1em;" /> Grade 6 Music Theory exam and enjoys playing the piano 🎹, guitar 🎸, and drums 🥁.

<!--
and enjoy <span id="bandShows" class="clickable">band shows</span>.

<div id="videoSection">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/6ovu13_usIM" frameborder="0"></iframe>
</div>

<script>
    // JavaScript to toggle the video section
    document.getElementById("bandShows").addEventListener("click", function() {
        var videoSection = document.getElementById("videoSection");
        if (videoSection.style.display === "none" || videoSection.style.display === "") {
            videoSection.style.display = "block";
        } else {
            videoSection.style.display = "none";
        }
    });
</script>

<script>
    // JavaScript to toggle the bug details section
    document.getElementById("bugCount").addEventListener("click", function() {
        var bugDetails = document.getElementById("bugDetails");
        if (bugDetails.style.display === "none" || bugDetails.style.display === "") {
            bugDetails.style.display = "block";
        } else {
            bugDetails.style.display = "none";
        }
    });
</script>
-->

<!--
# 👭 Friends
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->

<p align="center">
    <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=0&t=tt&d=2eF_pLvAz6SCyhYAFge0Xn9iWMT1PxKclkuxvQeeuzg&co=0d3e75&cmo=019b2a&cmn=ce3737&ct=ffffff'></script>
</p> 
