# gpt_chinese_DistributedDataParallel
gpt_chinese_DistributedDataParallel
把以下项目中的把train.py替换成 项目中的train.py
https://github.com/Morizeyao/GPT2-Chinese
感谢gpt2_chinese
启动 # # CUDA_VISIBLE_DEVICES=1,2,3 python -m torch.distributed.launch --nproc_per_node=3 /home/all/ljc/code/GPT2-Chinese/train_ddp.py

