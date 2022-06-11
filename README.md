# knlp_data
本项目作为knlp的姊妹项目，保存knlp的data中的完全数据。在运行knlp中依赖到本项目中的数据时，将会自动从本项目中下载数据，并解压缩到knlp/data目录下。
数据都来自于网络开源数据，感谢各位开源。

## 数据罗列

─data
    │  hanzi_segment.txt
    │  jieba_dict.txt
    │  pinyin_segment.txt
    │  pytest_data.txt
    │  stopwords.txt
    │  wait_to_cut.txt
    │  
    ├─pinyin_input_data
    │      emission_pro.json
    │      init_state_set.json
    │      pinyin_hanzi.json
    │      start_state.json
    │      state_set.json
    │      transition_pro.json
    │      
    └─seg_data
        └─train
                out3.txt
                pin_hanzi.txt
                pku_hmm_training_data_sample.txt
                pku_vocab.txt
                tag.txt