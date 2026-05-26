# mtk_img_parser
Parse Mtk images including preloader,lk for reversing engineering
```
usage: parse-part-img.py [-h] (--dump | --split) [-o OUT_DIR] [-n NAME] image

MTK image parser: dump or split part_hdr_t image lists.

positional arguments:
  image                 input image file

options:
  -h, --help            show this help message and exit
  --dump                print every sub-image part_hdr_t field
  --split               split every sub-image with its part_hdr_t header kept
  -o, --out-dir OUT_DIR
                        split output directory, default: <image_basename>_split
  -n, --name NAME       only split sub-image with this exact name
```

```
Usage: parse_preloader.py <preloader_image>

Parse MTK preloader image and display header information.
Supports ARM64/ARM32 architecture detection and policy_part_map parsing.
```

```
Usage: python parse_mtk_certs.py <image_file>
```
