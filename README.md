# Muti-Senti-Analysis
多模态情感分析模型  

需下载数据集，并放在data文件夹中解压，数据集地址：链接: https://pan.baidu.com/s/10fOExXqSCS4NmIjfsfuo9w?pwd=gqzm 提取码: gqzm 复制这段内容后打开百度网盘手机App，操作更方便哦  

训练：···python main.py --do_train --epoch 10 --text_pretrained_model roberta-base --fuse_model_type OTE 单模态(--text_only --img_only)···

测试：···python main.py --do_test --text_pretrained_model roberta-base --fuse_model_type OTE --load_model_path $your_model_path$ 单模态(--text_only --img_only)···