# File Structure Description
## `images` Folder
- Contains the 49-image dataset. Index starts from 0.

## `intrinsics.npy`
- Contains $49 \times 3 \times 3$ numpy array
- `intrinsics[i]` is the $3 \times 3$ intrinsic matrix of camera `i`, corresponding to image of index `i`

## `extrinsics.npy`
- Contains $49 \times 4 \times 4$ numpy array
- `extrinsics[i]` is the $4 \times 4$ extrinsic matrix of camera `i`, corresponding to image of index `i`