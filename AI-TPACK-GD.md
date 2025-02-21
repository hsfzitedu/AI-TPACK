graph TD
    subgraph TPACK_Framework
        TK[技术知识（TK）] --> TPK[技术教学知识（TPK）]
        TK --> TCK[技术内容知识（TCK）]
        PK[教学法知识（PK）] --> TPK
        PK --> PCK[教学内容知识（PCK）]
        CK[学科内容知识（CK）] --> TCK
        CK --> PCK
        TPK --> TPACK[TPACK]
        TCK --> TPACK
        PCK --> TPACK
    end
