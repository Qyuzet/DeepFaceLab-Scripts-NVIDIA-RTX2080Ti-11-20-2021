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

- `1_clear_workspace.bat`: Clears the workspace.
- `2_extract_images_from_video_data_src.bat`: Extracts images from the source video.
- `3_cut_video_drop_video_on_me.bat`: Cuts the video; drop the video file on this script to execute.
- `3_extract_images_from_video_data_dst_full_face.bat`: Extracts images from the destination video.
- `4_data_src_faceset_extract_manual.bat`: Manually extracts the faceset from the source data.
- `5_data_dst_faceset_extract_manual.bat`: Manually extracts the faceset from the destination data.
- ... (and so on for all scripts listed in your repository)

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
