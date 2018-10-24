# pix2scene
Modelling 3D structure from Images

Setup:

python setup.py develop --user


To Run:

python main.py --width 128 --height 128 --splats_img_size 128 --pixel_samples=1 --lr 2e-4 --name exp1 --disc_type cnn --cam_dist 0.8 --fovy 26 --batchSize 6   --gz_gi_loss 0.2 --est_normals --zloss 0.05  --unit_normalloss 0.0 --normal_consistency_loss_weight 10.0 --spatial_var_loss_weight 0.0 --grad_img_depth_loss 0.0 --spatial_loss_weight 0.0 --root_dir /path/pix2scene/data/cube --root_dir2 /path/pix2scene/data/cube --root_dir3 /path/pix2scene/data/cube --root_dir4 /path/pix2scene/data/cube
