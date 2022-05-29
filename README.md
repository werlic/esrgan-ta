generate meta info example

python scripts/generate_meta_info.py --input datasets/img-align-celeb --root datasets/img-align-celeb --meta_info datasets/img-align-celeb/meta_info/meta_info_img-align-celeb.txt

train with finetune from degraded images
python train.py -opt options/finetune_realesrgan_x4plus.yml --auto_resume