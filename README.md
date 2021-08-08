# petpet-rs

Also [petpet](https://github.com/camprevail/pet-pet-gif/), but in Rust.

## Usage

```bash
cargo run --release -- <input_image> <output_gif>
```

Note that **format of the input image must be the same as suffix name explains**,

otherwise you will get an error like `Bad Signature`!

## Todo

[kotlin_code]: https://github.com/poly000/BotPlugin/blob/master/src/main/kotlin/io/github/rosemoe/miraiPlugin/modules/PetPet.kt
[bad_solution]: https://github.com/poly000/petpet-rs/blob/f637cf3f147340692e1d0fdb9055739af7f1a3b2/src/lib.rs#L52
[example]: https://user-images.githubusercontent.com/34085039/128635187-c82f83f9-e5f0-401c-94c3-3c5e186af499.gif
[GIFEncoder]: https://docs.rs/image/0.23.14/image/codecs/gif/struct.GifEncoder.html

- [x] **[RIIR](https://github.com/ansuz/RIIR)**

I rewrite Petpet in Rust just due to Kotlin Version runs slowly and
I don't know how to extract **[the code][kotlin_code]** generating petpet.

- [ ] transparent background

**Needing help**: idk how to use transparent background in image instead of the first frame.

**[a terrible image example][example]**

Now I just **[added a white background][bad_solution]**.
