### Inference over images
python demo.py \
    --image_folder sample_data/input \
    --output_folder sample_data/output \
    --checkpoint_path ./checkpoints/sam-3d-body-dinov3/model.ckpt \
    --mhr_path ./checkpoints/sam-3d-body-dinov3/assets/mhr_model.pt


### Inference with save mesh
python demo.py \
    --image_folder sample_data/input \
    --output_folder sample_data/output \
    --checkpoint_path ./checkpoints/sam-3d-body-dinov3/model.ckpt \
    --mhr_path ./checkpoints/sam-3d-body-dinov3/assets/mhr_model.pt
    --save_mesh True
    --mesh_format ply