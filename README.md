### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1724614](https://hydra.nixos.org/eval/1724614) of nixpkgs commit [fb67ad2](https://github.com/NixOS/nixpkgs/commits/fb67ad2eeab563afe7d20540690712f0ac829aee) as of 2021-11-23 00:38 UTC*

:red_circle: **Branch not mergeable**
  * Too many outstanding jobs on aarch64-linux.
  * `mergeable` jobset is not finished.
  * `maintained` jobset is not finished.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | TimedOut :hourglass::no_entry_sign: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1724614?filter=.aarch64-linux) | 26 | 17 | 3 | 849 | 6247 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1724614?filter=.x86_64-darwin) | 14 | 19 |  | 4352 | 2701 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1724614?filter=.x86_64-linux) | 10 | 3 | 1 | 2 | 7149 | 
#### Maintained packages with failed dependency
- [ ] [cabal-install](https://hydra.nixos.org/eval/1724614?filter=cabal-install) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159067590) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159063121) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159070400) [toplevel](https://hydra.nixos.org/eval/1724614?filter=cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159063626) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159065814) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159058002) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc8107.cabal-install)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159077679) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159064230) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072075) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc884.cabal-install)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159077216) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159063664) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072795) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc901.cabal-install)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159063734) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159068964) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159071492) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc921.cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159067599) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159059672) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159059609) [haskellPackages](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.cabal-install)
- [ ] [cabal2nix](https://hydra.nixos.org/eval/1724614?filter=cabal2nix) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159065596) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159067533) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069698) [toplevel](https://hydra.nixos.org/eval/1724614?filter=cabal2nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159062902) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159075969) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159079366) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc8107.cabal2nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159060597) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159059734) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159061439) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc884.cabal2nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159064193) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159066217) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069074) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc901.cabal2nix)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159064853) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159072977) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159057925) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc921.cabal2nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159067901) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159072433) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069064) [haskellPackages](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.cabal2nix)
- [ ] [hsdns](https://hydra.nixos.org/eval/1724614?filter=hsdns) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159073921) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159074608) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159067124) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc8107.hsdns)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159064187) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159059013) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159062541) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc884.hsdns)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159060832) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159063109) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159075938) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc901.hsdns)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159058650) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159061326) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159064049) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc921.hsdns)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159061112) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159059182) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159068855) [haskellPackages](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.hsdns)
- [ ] [language-nix](https://hydra.nixos.org/eval/1724614?filter=language-nix) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159064672) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159070990) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072679) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc8107.language-nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159061833) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159077339) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159068599) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc884.language-nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159075584) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159078454) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069720) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc901.language-nix)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159077223) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159067199) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159068557) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc921.language-nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159063868) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159070950) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159077925) [haskellPackages](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.language-nix)
- [ ] [titlecase](https://hydra.nixos.org/eval/1724614?filter=titlecase) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159065793) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159063888) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069966) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc8107.titlecase)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159061512) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159071759) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159061626) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc884.titlecase)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159073938) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159068302) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159074417) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc901.titlecase)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159070759) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159062118) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159062479) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc921.titlecase)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159058134) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159069247) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159058450) [haskellPackages](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.titlecase)
#### Unmaintained packages with build failure
<details><summary>43 job(s) </summary>

- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159058466) [[:apple::x:]](https://hydra.nixos.org/build/159073686) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159073561) [haskellPackages.sdp](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp)  :arrow_heading_up: 9 | 9
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159068471) [[:apple::x:]](https://hydra.nixos.org/build/159068198) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159059515) [haskellPackages.junit-xml](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.junit-xml)  :arrow_heading_up: 7 | 9
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159065942) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159074780) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159077356) [haskellPackages.libBF](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.libBF)  :arrow_heading_up: 4 | 20
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159066955) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159063447) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159058623) [haskellPackages.ptr-poker](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.ptr-poker)  :arrow_heading_up: 3 | 4
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159079396) [[:penguin::x:]](https://hydra.nixos.org/build/159071860) [haskellPackages.gi-cogl](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.gi-cogl)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159057951) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159076647) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159058647) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.OrderedBits)  :arrow_heading_up: 1 | 36
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159066804) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159071134) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159063528) [haskellPackages.type-natural](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.type-natural)  :arrow_heading_up: 1 | 4
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159070369) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159065456) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159076982) [haskellPackages.long-double](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.long-double)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159072849) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159076703) [[:penguin::x:]](https://hydra.nixos.org/build/159074531) [haskellPackages.dovetail](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.dovetail)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159074349) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159069196) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159058534) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.easytensor)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159059684) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159072596) [[:penguin::x:]](https://hydra.nixos.org/build/159064047) [haskellPackages.gi-json](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.gi-json)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159069616) [[:apple::x:]](https://hydra.nixos.org/build/159065666) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072178) [haskellPackages.keep-alive](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.keep-alive)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159060647) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159076151) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069993) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159074369) [[:apple::x:]](https://hydra.nixos.org/build/159072053) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159060362) [haskellPackages.sequence-formats](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sequence-formats)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159060854) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159065366) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159063050) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.unicode-properties)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159062200) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159072768) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159077737) [haskellPackages.accelerate-llvm](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.accelerate-llvm)  :arrow_heading_up: 0 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159060891) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159063990) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159061375) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.freetype2)  :arrow_heading_up: 0 | 7
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159061935) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159069321) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072783) [haskellPackages.cdar-mBound](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.cdar-mBound)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159063847) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159078774) [[:penguin::x:]](https://hydra.nixos.org/build/159058966) [haskellPackages.exploring-interpreters](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.exploring-interpreters)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159074238) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159062008) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159060209) [haskellPackages.picosat](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159061581) [[:apple::x:]](https://hydra.nixos.org/build/159059260) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072608) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.FractalArt) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159064674) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159063662) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159074622) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159078169) [[:apple::x:]](https://hydra.nixos.org/build/159058179) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159066359) [haskellPackages.chiphunk](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.chiphunk) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159062888) [[:apple::x:]](https://hydra.nixos.org/build/159072543) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159066423) [haskellPackages.discount](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.discount) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159062720) [[:penguin::x:]](https://hydra.nixos.org/build/159063812) [haskellPackages.gi-gtk-layer-shell](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.gi-gtk-layer-shell) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159059419) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159068965) [[:penguin::x:]](https://hydra.nixos.org/build/159074895) [haskellPackages.gi-rsvg](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.gi-rsvg) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159075903) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159076319) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.gnome-keyring) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159072321) [[:apple::x:]](https://hydra.nixos.org/build/159069556) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159071675) [haskellPackages.hid](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.hid) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159074499) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159075923) [[:penguin::x:]](https://hydra.nixos.org/build/159064026) [haskellPackages.hls-rename-plugin](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.hls-rename-plugin) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159063803) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159076567) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159078333) [haskellPackages.hq](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.hq) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159072722) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159071977) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072733) [haskellPackages.hslua-aeson](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.hslua-aeson) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159072443) [[:apple::x:]](https://hydra.nixos.org/build/159062401) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069960) [haskellPackages.hsshellscript](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.hsshellscript) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159065196) [[:apple::x:]](https://hydra.nixos.org/build/159057935) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159074793) [haskellPackages.linux-framebuffer](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.linux-framebuffer) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159070342) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159072101) [[:penguin::x:]](https://hydra.nixos.org/build/159074660) [haskellPackages.one-line-aeson-text](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.one-line-aeson-text) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159068415) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159062052) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159068938) [haskellPackages.poker](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.poker) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159066654) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159068796) [[:penguin::x:]](https://hydra.nixos.org/build/159073848) [haskellPackages.polysemy-mocks](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.polysemy-mocks) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159061912) [[:apple::x:]](https://hydra.nixos.org/build/159074422) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159075748) [haskellPackages.pthread](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.pthread) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159069587) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159066652) [[:penguin::x:]](https://hydra.nixos.org/build/159062926) [haskellPackages.stripe-wreq](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.stripe-wreq) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159076002) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159070119) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159070352) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/159061923) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159068343) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072236) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.x86-64bit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159076214) [[:apple::x:]](https://hydra.nixos.org/build/159062727) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159074425) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.xmonad-utils) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159069586) [[:apple::x:]](https://hydra.nixos.org/build/159070245) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159066222) [haskellPackages.yoga](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.yoga) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159065077) [[:apple::x:]](https://hydra.nixos.org/build/159066341) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159074491) [haskellPackages.zot](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.zot) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>37 job(s) </summary>

- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159074913) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159058073) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159064326) [haskellPackages.pretty-diff](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.pretty-diff)  :arrow_heading_up: 6 | 12
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159077965) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159060410) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159071069) [haskellPackages.nri-prelude](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.nri-prelude)  :arrow_heading_up: 5 | 7
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159064886) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159074239) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072529) [haskellPackages.nri-env-parser](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.nri-env-parser)  :arrow_heading_up: 4 | 6
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159064151) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159076271) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159066957) [haskellPackages.nri-observability](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.nri-observability)  :arrow_heading_up: 3 | 5
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159073090) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159060041) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159073258) [haskellPackages.jsonifier](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.jsonifier)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159059368) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159060220) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159062099) [haskellPackages.sdp-io](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp-io)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159070185) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159072308) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159075094) [haskellPackages.nri-redis](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.nri-redis)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159069411) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159072688) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159071841) [haskellPackages.opentelemetry-extra](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.opentelemetry-extra)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159059918) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159070590) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159070436) [haskellPackages.sdp-hashable](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp-hashable)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159067108) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159076258) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159059600) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.PrimitiveArray)  :arrow_heading_up: 0 | 35
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159078833) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159077674) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159064639) [haskellPackages.sized](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sized)  :arrow_heading_up: 0 | 2
- [ ] [cabal2nix-unstable](https://hydra.nixos.org/eval/1724614?filter=cabal2nix-unstable) 
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159078945) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159061943) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159064786) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc8107.cabal2nix-unstable)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159075526) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159067218) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159065541) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc884.cabal2nix-unstable)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159065537) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159078198) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159068273) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc901.cabal2nix-unstable)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159065361) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159058368) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159071129) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1724614?filter=haskell.packages.ghc921.cabal2nix-unstable)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159059460) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159063681) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159076606) [haskellPackages](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.cabal2nix-unstable)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159068226) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159073099) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159064194) [haskellPackages.dovetail-aeson](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.dovetail-aeson) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159068233) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159070116) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072007) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159078258) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159064796) [haskellPackages.gi-clutter](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.gi-clutter) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159074303) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159064231) [haskellPackages.gi-coglpango](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.gi-coglpango) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159074005) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159072107) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159069048) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159077288) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159067468) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072808) [haskellPackages.nri-http](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.nri-http) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159067633) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159062484) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159068718) [haskellPackages.nri-test-encoding](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.nri-test-encoding) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159060536) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159067188) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159064315) [haskellPackages.opentelemetry-lightstep](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.opentelemetry-lightstep) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159061882) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159067588) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159070779) [haskellPackages.postgresql-replicant](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.postgresql-replicant) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159078935) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159078105) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159077754) [haskellPackages.rounded](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.rounded) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159065956) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159073549) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159078588) [haskellPackages.sdp-binary](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp-binary) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159061402) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159064272) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159060876) [haskellPackages.sdp-deepseq](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp-deepseq) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159062846) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159070178) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159074773) [haskellPackages.sdp-quickcheck](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp-quickcheck) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159074926) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159070243) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159076660) [haskellPackages.sdp4bytestring](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp4bytestring) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/159077413) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159064045) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159067006) [haskellPackages.sdp4text](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp4text) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159073309) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159077938) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072382) [haskellPackages.sdp4unordered](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp4unordered) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159066809) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159077315) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159079238) [haskellPackages.sdp4vector](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sdp4vector) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159059761) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159059055) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159079511) [haskellPackages.sequenceTools](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.sequenceTools) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/159079253) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159058377) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159072184) [haskellPackages.tasty-test-reporter](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.tasty-test-reporter) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/159067008) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/159063702) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/159067812) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1724614?filter=haskellPackages.unicode-names) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[haskell98](https://packdeps.haskellers.com/reverse/haskell98) :arrow_heading_up: 153  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) :arrow_heading_up: 56  
[derive](https://packdeps.haskellers.com/reverse/derive) :arrow_heading_up: 48  
[contiguous](https://packdeps.haskellers.com/reverse/contiguous) :arrow_heading_up: 46  
[MonadCatchIO-transformers](https://packdeps.haskellers.com/reverse/MonadCatchIO-transformers) :arrow_heading_up: 41  
[parseargs](https://packdeps.haskellers.com/reverse/parseargs) :arrow_heading_up: 41  
[bytesmith](https://packdeps.haskellers.com/reverse/bytesmith) :arrow_heading_up: 36  
[data-lens](https://packdeps.haskellers.com/reverse/data-lens) :arrow_heading_up: 34  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) :arrow_heading_up: 30  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) :arrow_heading_up: 29  
[jmacro](https://packdeps.haskellers.com/reverse/jmacro) :arrow_heading_up: 29  
[ip](https://packdeps.haskellers.com/reverse/ip) :arrow_heading_up: 26  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) :arrow_heading_up: 25  
[HList](https://packdeps.haskellers.com/reverse/HList) :arrow_heading_up: 23  
[SciBaseTypes](https://packdeps.haskellers.com/reverse/SciBaseTypes) :arrow_heading_up: 22  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) :arrow_heading_up: 22  
[hsc3](https://packdeps.haskellers.com/reverse/hsc3) :arrow_heading_up: 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) :arrow_heading_up: 22  
[BiobaseTypes](https://packdeps.haskellers.com/reverse/BiobaseTypes) :arrow_heading_up: 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) :arrow_heading_up: 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) :arrow_heading_up: 20  
[secp256k1-haskell](https://packdeps.haskellers.com/reverse/secp256k1-haskell) :arrow_heading_up: 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) :arrow_heading_up: 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) :arrow_heading_up: 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) :arrow_heading_up: 19  
[numhask](https://packdeps.haskellers.com/reverse/numhask) :arrow_heading_up: 19  
[polysemy-plugin](https://packdeps.haskellers.com/reverse/polysemy-plugin) :arrow_heading_up: 19  
[wx](https://packdeps.haskellers.com/reverse/wx) :arrow_heading_up: 19  
[BiobaseENA](https://packdeps.haskellers.com/reverse/BiobaseENA) :arrow_heading_up: 18  
[asn1-data](https://packdeps.haskellers.com/reverse/asn1-data) :arrow_heading_up: 18  
[dbus-core](https://packdeps.haskellers.com/reverse/dbus-core) :arrow_heading_up: 18  
[gtksourceview2](https://packdeps.haskellers.com/reverse/gtksourceview2) :arrow_heading_up: 18  
[BiobaseXNA](https://packdeps.haskellers.com/reverse/BiobaseXNA) :arrow_heading_up: 17  
[HGamer3D-Data](https://packdeps.haskellers.com/reverse/HGamer3D-Data) :arrow_heading_up: 17  
[certificate](https://packdeps.haskellers.com/reverse/certificate) :arrow_heading_up: 17  
[dbus-client](https://packdeps.haskellers.com/reverse/dbus-client) :arrow_heading_up: 17  
[gconf](https://packdeps.haskellers.com/reverse/gconf) :arrow_heading_up: 17  
[gtk-serialized-event](https://packdeps.haskellers.com/reverse/gtk-serialized-event) :arrow_heading_up: 17  
[uuid-orphans](https://packdeps.haskellers.com/reverse/uuid-orphans) :arrow_heading_up: 17  
[cuda](https://packdeps.haskellers.com/reverse/cuda) :arrow_heading_up: 16  
[happstack-jmacro](https://packdeps.haskellers.com/reverse/happstack-jmacro) :arrow_heading_up: 16  
[manatee-core](https://packdeps.haskellers.com/reverse/manatee-core) :arrow_heading_up: 16  
[monads-fd](https://packdeps.haskellers.com/reverse/monads-fd) :arrow_heading_up: 16  
[murmur3](https://packdeps.haskellers.com/reverse/murmur3) :arrow_heading_up: 16  
[tls-extra](https://packdeps.haskellers.com/reverse/tls-extra) :arrow_heading_up: 16  
[ADPfusion](https://packdeps.haskellers.com/reverse/ADPfusion) :arrow_heading_up: 15  
[MaybeT](https://packdeps.haskellers.com/reverse/MaybeT) :arrow_heading_up: 15  
[blaze-builder-enumerator](https://packdeps.haskellers.com/reverse/blaze-builder-enumerator) :arrow_heading_up: 15  
[clash-prelude](https://packdeps.haskellers.com/reverse/clash-prelude) :arrow_heading_up: 15  
[hetero-dict](https://packdeps.haskellers.com/reverse/hetero-dict) :arrow_heading_up: 15  
</details>


*:arrow_heading_up:: The number of packages that depend (directly or indirectly) on this package (if any). If two numbers are shown the first (lower) number considers only packages which currently have enabled hydra jobs, i.e. are not marked broken. The second (higher) number considers all packages.*

*Report generated with [maintainers/scripts/haskell/hydra-report.hs](https://github.com/NixOS/nixpkgs/blob/haskell-updates/maintainers/scripts/haskell/hydra-report.sh)*


----------------------------------------------------------------------

This README.md is automatically updated every 6 hours with the status of the
[`haskell-updates` branch/jobset on Hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
from [Nixpkgs](https://github.com/NixOS/nixpkgs).  This is mostly only of
interest to the [Nixpkgs Haskell maintainers](https://github.com/orgs/NixOS/teams/haskell).

See the
[haskell-modules/HACKING.md](https://github.com/NixOS/nixpkgs/blob/haskell-updates/pkgs/development/haskell-modules/HACKING.md)
file for more information about this build report.

You can force the GitHub Action to run (and the README.md to be updated) by
manually running the Action.  To do this, go to the Action list screen
(https://github.com/cdepillabout/nix-haskell-updates-status/actions),
click on any of the Workflow runs, and then click the `Re-run jobs` button.
