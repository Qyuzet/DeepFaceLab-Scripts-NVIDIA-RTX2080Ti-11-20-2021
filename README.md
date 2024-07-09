# DeepFaceLab-Scripts-NVIDIA-RTX2080Ti-11-20-2021

This repository contains a collection of batch scripts to automate various tasks in DeepFaceLab, specifically configured for the NVIDIA RTX 2080 Ti.

## Prerequisites

Before using these scripts, please ensure that you have DeepFaceLab installed and configured correctly. Additionally, you will need to include specific files from an external link into your DeepFaceLab folder.

## Setup Instructions

1. **Download DeepFaceLab**: Ensure you have the latest version of DeepFaceLab downloaded and set up on your machine.

2. **Clone This Repository**:
   ```sh
   git clone https://github.com/Qyuzet/DeepFaceLab-Scripts-NVIDIA-RTX2080Ti-11-20-2021.git
   cd DeepFaceLab-Scripts-NVIDIA-RTX2080Ti-11-20-2021
   ```

3. **Download Additional Files**:
   - Download the additional files from the provided link: [Download Additional Files](https://binusianorg-my.sharepoint.com/personal/riki_syahputra_binus_ac_id/_layouts/15/guestaccess.aspx?share=EeDBg3Ig3WlGrHymQhfpZ-4BMkhkWQ53YoEmXXCdgHnZ3w&e=hpj5qL).
   - Extract the contents of the downloaded folder.
   - Copy the contents into your DeepFaceLab folder, merging with the existing structure.

## Scripts

Here is a list of the available batch scripts and their functionalities:


- `clear workspace.bat`: Clears the workspace.
- `merged mids.bat`: Merges mids files.
- `merged to mp3.bat`: Merges to mp3.
- `merged to video.bat`: Merges to video.
- `merged to wav.bat`: Merges to wav.
- `extract images from video.bat`: Extracts images from the video.
- `extract images from video (skip black).bat`: Extracts images from the video, skipping black frames.
- `extract images from video (start-end) MANUAL.bat`: Manually extracts images from the video between start and end points.
- `arc faces.bat`: Performs arc face processing.
- `arc faces (extract).bat`: Extracts arc faces.
- `arc faces (extract) MANUAL.bat`: Manually extracts arc faces.
- `arc faces (extract frames).bat`: Extracts arc faces from frames.
- `arc faces (sort).bat`: Sorts arc faces.
- `xSeg (faces) extract masks.bat`: Extracts masks for faces using xSeg.
- `xSeg (faces) will upscale landmarks + cleanup.bat`: Upscales landmarks and cleans up using xSeg.
- `xSeg (faces) will remove landmarks + cleanup.bat`: Removes landmarks and cleans up using xSeg.
- `xSeg (faces) will faceset extract.bat`: Extracts faceset using xSeg.
- `xSeg (faces) will faceset pack.bat`: Packs faceset using xSeg.
- `xSeg (faces) faceset unpack.bat`: Unpacks faceset using xSeg.
- `xSeg (dst) faces will extract masks.bat`: Extracts masks for destination faces using xSeg.
- `xSeg (dst) faces will upscale landmarks + cleanup.bat`: Upscales landmarks and cleans up destination faces using xSeg.
- `xSeg (dst) faces will remove landmarks + cleanup.bat`: Removes landmarks and cleans up destination faces using xSeg.
- `xSeg (dst) faces will faceset extract.bat`: Extracts faceset for destination faces using xSeg.
- `xSeg (dst) faces will faceset pack.bat`: Packs faceset for destination faces using xSeg.
- `xSeg (dst) faces faceset unpack.bat`: Unpacks faceset for destination faces using xSeg.
- `xSeg config.bat`: Configures xSeg.
- `xSeg align dst.bat`: Aligns destination faces using xSeg.
- `xSeg sort aligned results.bat`: Sorts aligned results using xSeg.
- `xSeg will dst extract masks.bat`: Extracts masks for destination using xSeg.
- `xSeg will dst pack masks.bat`: Packs masks for destination using xSeg.
- `xSeg will dst unpack masks.bat`: Unpacks masks for destination using xSeg.
- `xSeg (XSeg dataset) edit.bat`: Edits xSeg dataset.
- `xSeg (XSeg dataset) edit while face swap - MASK.bat`: Edits xSeg dataset while face swapping - MASK.
- `xSeg (XSeg dataset) edit while face swap.bat`: Edits xSeg dataset while face swapping.
- `xSeg (XSeg dataset) dst mask.bat`: Applies mask to xSeg dataset.
- `xSeg (XSeg dataset) dst mask - remove.bat`: Removes mask from xSeg dataset.
- `xSeg (XSeg dataset) trained mask - apply.bat`: Applies trained mask to xSeg dataset.
- `xSeg (XSeg dataset) trained mask.bat`: Trains mask on xSeg dataset.
- `xSeg (XSeg dataset) mask.bat`: Applies mask to xSeg dataset.
- `xSeg (XSeg dataset) mask - remove.bat`: Removes mask from xSeg dataset.
- `xSeg (XSeg dataset) mask - apply.bat`: Applies mask to xSeg dataset.
- `xSeg train.bat`: Trains xSeg model.
- `xSeg export as arc faceset.bat`: Exports as arc faceset.
- `fix hair.bat`: Fixes hair in the images.
- `fix mouth.bat`: Fixes mouth in the images.
- `xSeg AMP.bat`: Uses xSeg AMP.
- `train Quick.bat`: Quick training.
- `train.bat`: Full training.
- `merge SAD.bat`: Merges using SAD.
- `merge D.bat`: Merges using D.
- `merge Kam.bat`: Merges using Kam.
- `merged to mp3.bat`: Merges to mp3.
- `merged to video.bat`: Merges to video.
- `merged to wav.bat`: Merges to wav.
- `LICENSE`: The license file.
- `update.bat`: Updates the scripts.
- `run.bat`: Runs the
  
## Usage

To use these scripts, navigate to the `scripts` directory and run the desired script by double-clicking on it or executing it from the command line. For example:

```sh
cd scripts
./1_clear_workspace.bat
```

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [DeepFaceLab](https://github.com/iperov/DeepFaceLab) - The original project.

Feel free to contribute or report any issues you encounter.
