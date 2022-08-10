Запуск обучения

```
python pretrain_transformers.py \
    --output_dir=/home/jovyan/rugpt2large/checkpoints_"${now}"_"${host}" \
    --model_type=gpt2 \
    --model_name_or_path=/home/jovyan/gpt2_large_bbpe_v50 \
    --do_train \
    --train_data_file=/home/jovyan/data/train.txt \
    --do_eval \
    --eval_data_file=/home/jovyan/data/valid.txt \
    --fp16
```
