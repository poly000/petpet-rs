# petpet-rs

[![crates.io](https://img.shields.io/crates/v/petpet.svg)](https://crates.io/crates/petpet)

[![Example Image](https://user-images.githubusercontent.com/34085039/129224045-41649633-7fb1-4bdf-85ce-eadfac183c3d.gif)](https://yande.re/post/show/304166)

Also [petpet](https://github.com/camprevail/pet-pet-gif/), but in Rust.

The default hands images were credited by [PetPet Generator](https://benisland.neocities.org/petpet/).

[Here](https://github.com/poly000/awesome-petpet-hands) you can download more custom hands.

You can replace hand images in src/res then **recompile** petpet.

## Download

You can download the latest release from [releases](https://github.com/poly000/petpet-rs/releases) page.

## Build

```bash
cargo build --release
```

## Usage

```bash
cargo run --release -- <input_image> <output_gif> <encode_speed>
```

**[details about encode_speed](https://doc.servo.org/color_quant/struct.NeuQuant.html#method.new)**

![more visual performance line chart](img/speed_to_cpu-time.png)

Note that **format of the input image must be the same as its extension explains**,

otherwise you will get an error like `Bad Signature`!

# Clicks

![:petpet](https://count.getloli.com/get/@:petpet)
