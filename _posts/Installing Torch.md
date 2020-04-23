# Installing Torch
# in a terminal, run the commands WITHOUT sudo
git clone https://github.com/torch/distro.git ~/torch --recursive
cd ~/torch; bash install-deps;
./install.sh
# Open Http Server by using python -m
python -m http.server [<portNo>]
# Caption Learn Command
# https://github.com/karpathy/neuraltalk2
$ th eval.lua -model ._model_id1-501-1448236541.t7 -image_folder ._images/ -num_images 2
$ python prepro1.py --input_json coco_coco_raw.json --num_val 5000 --num_test 5000 --images_root coco_images_test2014 --word_count_threshold 5 --output_json coco_cocotalk.json --output_h5 coco/cocotalk.h5
​
#research/history
