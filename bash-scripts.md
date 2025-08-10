1. For resizing:

$ for file in *
> do
> squoosh-cli -lossless -m 6 -z 9 "$file" -o "out
put/${file%.png}.webp"
> done

2. For conversion:

$ for file in *
> do
> cwebp -lossless -m 6 -z 9 "$file" -o "out
put/${file%.png}.webp"
> done




## Resize filter tests

- magick og.png -resize x700 -filter bartlett bartlett.png
- magick og.png -resize x700 -filter blackman blackman.png
- magick og.png -resize x700 -filter bohman bohman.png
- magick og.png -resize x700 -filter box box.png
- magick og.png -resize x700 -filter catrom catrom.png
- magick og.png -resize x700 -filter cosine cosine.png
- magick og.png -resize x700 -filter cubic cubic.png
- magick og.png -resize x700 -filter gaussian gaussian.png
- magick og.png -resize x700 -filter hamming hamming.png
- magick og.png -resize x700 -filter hann hann.png
- magick og.png -resize x700 -filter hermite hermite.png
- magick og.png -resize x700 -filter jinc jinc.png
- magick og.png -resize x700 -filter kaiser kaiser.png
- magick og.png -resize x700 -filter lagrange lagrange.png
- magick og.png -resize x700 -filter lanczos lanczos.png
- magick og.png -resize x700 -filter lanczos2 lanczos2.png
- magick og.png -resize x700 -filter lanczos2sharp lanczos2sharp.png
- magick og.png -resize x700 -filter lanczosradius lanczosradius.png
- magick og.png -resize x700 -filter lanczossharp lanczossharp.png
- magick og.png -resize x700 -filter magickernelsharp2013 magickernelsharp2013.png
- magick og.png -resize x700 -filter magickernelsharp2021 magickernelsharp2021.png
- magick og.png -resize x700 -filter mitchell mitchell.png
- magick og.png -resize x700 -filter parzen parzen.png
- magick og.png -resize x700 -filter point point.png
- magick og.png -resize x700 -filter quadratic quadratic.png
- magick og.png -resize x700 -filter robidoux robidoux.png
- magick og.png -resize x700 -filter robidouxsharp robidouxsharp.png
- magick og.png -resize x700 -filter sinc sinc.png
- magick og.png -resize x700 -filter sincfast sincfast.png
- magick og.png -resize x700 -filter spline spline.png
- magick og.png -resize x700 -filter cubicspline cubicspline.png
- magick og.png -resize x700 -filter triangle triangle.png
- magick og.png -resize x700 -filter welch welch.png




magick og.png -resize x700 -filter bartlett bartlett.png && magick og.png -resize x700 -filter blackman blackman.png && magick og.png -resize x700 -filter bohman bohman.png && magick og.png -resize x700 -filter box box.png && magick og.png -resize x700 -filter catrom catrom.png && magick og.png -resize x700 -filter cosine cosine.png && magick og.png -resize x700 -filter cubic cubic.png && magick og.png -resize x700 -filter gaussian gaussian.png && magick og.png -resize x700 -filter hamming hamming.png && magick og.png -resize x700 -filter hann hann.png && magick og.png -resize x700 -filter hermite hermite.png && magick og.png -resize x700 -filter jinc jinc.png && magick og.png -resize x700 -filter kaiser kaiser.png && magick og.png -resize x700 -filter lagrange lagrange.png && magick og.png -resize x700 -filter lanczos lanczos.png && magick og.png -resize x700 -filter lanczos2 lanczos2.png && magick og.png -resize x700 -filter lanczos2sharp lanczos2sharp.png && magick og.png -resize x700 -filter lanczosradius lanczosradius.png && magick og.png -resize x700 -filter lanczossharp lanczossharp.png && magick og.png -resize x700 -filter magickernelsharp2013 magickernelsharp2013.png && magick og.png -resize x700 -filter magickernelsharp2021 magickernelsharp2021.png && magick og.png -resize x700 -filter mitchell mitchell.png && magick og.png -resize x700 -filter parzen parzen.png && magick og.png -resize x700 -filter point point.png && magick og.png -resize x700 -filter quadratic quadratic.png && magick og.png -resize x700 -filter robidoux robidoux.png && magick og.png -resize x700 -filter robidouxsharp robidouxsharp.png && magick og.png -resize x700 -filter sinc sinc.png && magick og.png -resize x700 -filter sincfast sincfast.png && magick og.png -resize x700 -filter spline spline.png && magick og.png -resize x700 -filter cubicspline cubicspline.png && magick og.png -resize x700 -filter triangle triangle.png && magick og.png -resize x700 -filter welch welch.png




## Resize height tests

magick og.png -resize x1200 -filter lanczos 1200.png
magick og.png -resize x1100 -filter lanczos 1100.png
magick og.png -resize x1000 -filter lanczos 1000.png
magick og.png -resize x900 -filter lanczos 900.png
magick og.png -resize x800 -filter lanczos 800.png
magick og.png -resize x750 -filter lanczos 750.png
magick og.png -resize x700 -filter lanczos 700.png
magick og.png -resize x650 -filter lanczos 650.png
magick og.png -resize x600 -filter lanczos 600.png
magick og.png -resize x550 -filter lanczos 550.png
magick og.png -resize x500 -filter lanczos 500.png
magick og.png -resize x450 -filter lanczos 450.png
magick og.png -resize x400 -filter lanczos 400.png
magick og.png -resize x350 -filter lanczos 350.png
magick og.png -resize x300 -filter lanczos 300.png
magick og.png -resize x250 -filter lanczos 250.png
magick og.png -resize x200 -filter lanczos 200.png
magick og.png -resize x150 -filter lanczos 150.png


magick og.png -resize x1200 -filter lanczos 1200.png && magick og.png -resize x1100 -filter lanczos 1100.png && magick og.png -resize x1000 -filter lanczos 1000.png && magick og.png -resize x900 -filter lanczos 900.png && magick og.png -resize x800 -filter lanczos 800.png && magick og.png -resize x750 -filter lanczos 750.png && magick og.png -resize x700 -filter lanczos 700.png && magick og.png -resize x650 -filter lanczos 650.png && magick og.png -resize x600 -filter lanczos 600.png && magick og.png -resize x550 -filter lanczos 550.png && magick og.png -resize x500 -filter lanczos 500.png && magick og.png -resize x450 -filter lanczos 450.png && magick og.png -resize x400 -filter lanczos 400.png && magick og.png -resize x350 -filter lanczos 350.png && magick og.png -resize x300 -filter lanczos 300.png && magick og.png -resize x250 -filter lanczos 250.png && magick og.png -resize x200 -filter lanczos 200.png && magick og.png -resize x150 -filter lanczos 150.png