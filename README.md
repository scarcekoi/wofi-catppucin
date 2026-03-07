<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/SimplyCEO/wofi">Wofi</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/wofi/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/wofi?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/wofi/issues"><img src="https://img.shields.io/github/issues/catppuccin/wofi?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/wofi/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/wofi?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.png"/>
</details>

<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.png"/>
</details>

<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.png"/>
</details>

<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.png"/>
</details>

## Usage

> [!NOTE]
> The files available in this repository only change colors. There are some recommended non-color changes that can be accessed by cloning this repository, installing [whiskers](https://github.com/catppuccin/whiskers), running `whiskers wofi.tera --overrides '{"non_color_overrides": "yes"}'` in the cloned repository, and then using the generated file of your preferred flavour and accent combination for step 2.

1. Download the flavor and accent combination of your choice from [themes/](themes).
2. Copy the CSS file to your Wofi config directory (change `<flavor>` and `<accent>` to the flavor and accent you downloaded):

```bash
mkdir -p ~/.config/wofi
cp <flavor>-<accent>.css ~/.config/wofi/style.css
```

3. Make sure your Wofi config points to the style:

```ini
# ~/.config/wofi/config
style=~/.config/wofi/style.css
```

4. Launch Wofi:

```bash
wofi --show drun
```

## 💝 Thanks to

- [Yaman](https://github.com/CyberHuman-bot)
- [Scarce Koi](https://github.com/scarcekoi)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>
<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>
<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
