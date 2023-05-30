original - [https://github.com/zyxElsa/InST](https://github.com/zyxElsa/InST)

# Infer
1. Clone repo
2. Download https://huggingface.co/CompVis/stable-diffusion-v-1-4-original/resolve/main/sd-v1-4.ckpt and put it in models/sd
3. Create env
```
chmod 777 create_venv.sh
./create_venv.sh
source venv_styletransfer/bin/activate

```
4. For style transfer run
```
python3 transfer_style.py -cont_im Images/vazovski.jpeg -style_im Images/shrek.png
```
# Examples

Shrek + Gigachad

<img width="319" alt="shrek" src="https://github.com/GendalfSeriyy/StyleTransfer/assets/55240294/f27df31f-34ff-4438-abd9-bb551fc0d0c7">

<img width="319" alt="chad" src="https://github.com/GendalfSeriyy/StyleTransfer/assets/55240294/6d7541cf-b3a5-4e2a-81bf-1d95d7fd74f6">

<img width="446" alt="shrekochad" src="https://github.com/GendalfSeriyy/StyleTransfer/assets/55240294/e6b72442-f7f4-4883-91df-796163b1ec52">

<img width="461" alt="Снимок экрана 2023-05-24 в 15 13 28" src="https://github.com/GendalfSeriyy/StyleTransfer/assets/55240294/a126a011-93a9-4b78-a406-457ed24fe294">

Shrek + Wazowski

<img width="319" alt="shrek" src="https://github.com/GendalfSeriyy/StyleTransfer/assets/55240294/f27df31f-34ff-4438-abd9-bb551fc0d0c7">
<img width="319" alt="Wazowski" src=https://github.com/GendalfSeriyy/StyleTransfer/assets/55240294/dfa0e1c5-d57c-49ec-985a-e994648c0095>
<img width="506" alt="shrekovas" src="https://github.com/GendalfSeriyy/StyleTransfer/assets/55240294/e9416304-f94f-45b7-948a-9b7bdf98f60a">

