# NL2KB

NTU NL2KB (Natural Language to Knowledge Base) Resource
# Introduction
A total of 7,139 Chinese relation patterns that cover 1,087 DBpedia properties are extracted and verified by human annotators. This resource can be used for knowledge base construction and knowledge base retrieval (e.g., question-answering).

# Format
Each line in the UTF-8 encoded tab separated file is a relation pattern. The first column is the property defined in DBpedia. The second column is the pattern in Chinese. The third and the fourth columns are the support and the confidence values of this pattern, respectively. The last column denotes this pattern is correct (T) or wrong (F) verified by annotators.

As the example shown as follows, "<實體一> 執導 <實體二>" is a Chinese pattern that suggests the DBpedia property producer with 103 supports and a confidence of 0.112. This mapping is validated by human annotators.  
<sub> producer <實體一> 執導 <實體二> 103 0.112 T </sub>
  
# Download and Demo
Download [Traditional Chinese](http://nlg.csie.ntu.edu.tw/nlpresource/nl2kb/nl2kb_zhTW.txt) / [Simplified Chinese](http://nlg.csie.ntu.edu.tw/nlpresource/nl2kb/nl2kb_zhCN.txt) pattern.
Click [here](http://nlg18.csie.ntu.edu.tw/nl2kb/) to visit our demosite.
  
# How to Cite this resource
Please cite the following paper when referring to NL2KB in academic publications and papers.

<sub>Sheng-Lun Wei, Yen-Pin Chiu, Hen-Hsen Huang, and Hsin-Hsi Chen (2016). “NL2KB: Resolving Vocabulary Gap between Natural Language and Knowledge Base in Knowledge Base Construction and Retrieval.” Proceedings of the 26th International Conference on Computational Linguistics (COLING 2016), December 11-16, 2016, Osaka, Japan.</sub>
