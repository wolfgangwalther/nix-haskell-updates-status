### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1727540](https://hydra.nixos.org/eval/1727540) of nixpkgs commit [a4f6827](https://github.com/NixOS/nixpkgs/commits/a4f68278eb159d3b963c044884706efbe5d95ac8) as of 2021-12-03 18:16 UTC*

:yellow_circle: **Potential issues**
  * `mergeable` jobset is not finished.
  * `maintained` jobset is not finished.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | TimedOut :hourglass::no_entry_sign: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1727540?filter=.aarch64-linux) | 30 | 39 | 1 | 32 | 7048 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1727540?filter=.x86_64-darwin) |  | 1 |  | 7064 | 26 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1727540?filter=.x86_64-linux) | 8 | 3 |  | 16 | 7162 | 
#### Maintained packages with build failure
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160442639) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160452858) [[:penguin::x:]](https://hydra.nixos.org/build/160447267) [haskellPackages.dhall-nixpkgs](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.dhall-nixpkgs) @Gabriel439
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160444711) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160444980) [[:penguin::x:]](https://hydra.nixos.org/build/160449346) [haskellPackages.rel8](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.rel8) @sternenseemann
#### Maintained packages with failed dependency
- [ ] [git-annex](https://hydra.nixos.org/eval/1727540?filter=git-annex) @peti
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160438866) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160455285) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160444115) [toplevel](https://hydra.nixos.org/eval/1727540?filter=git-annex)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160439618) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160444173) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160453727) [haskellPackages](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.git-annex)
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1727540?filter=haskell-language-server) @maralorn
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160758061) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160758067) [[:penguin::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160758064) [toplevel](https://hydra.nixos.org/eval/1727540?filter=haskell-language-server)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160443318) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160445683) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160455435) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc8107.haskell-language-server)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160451533) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160441483) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160449177) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc884.haskell-language-server)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160758056) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160758066) [[:penguin::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160758062) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc901.haskell-language-server)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160446529) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160445708) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160442682) [haskellPackages](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.haskell-language-server)
- [ ] [hsdns](https://hydra.nixos.org/eval/1727540?filter=hsdns) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160445928) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160447151) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160452154) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc8107.hsdns)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160444002) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160445446) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160448296) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc884.hsdns)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160457080) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160453520) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160440975) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc901.hsdns)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160450041) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160444127) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160444167) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc921.hsdns)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160453268) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160452760) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160436298) [haskellPackages](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.hsdns)
- [ ] [pandoc](https://hydra.nixos.org/eval/1727540?filter=pandoc) @peti
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160441839) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160445289) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160446016) [toplevel](https://hydra.nixos.org/eval/1727540?filter=pandoc)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160444695) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160450974) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160440564) [haskellPackages](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.pandoc)
- [ ] [titlecase](https://hydra.nixos.org/eval/1727540?filter=titlecase) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160437766) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160436845) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160453740) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc8107.titlecase)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160448969) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160446339) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160439450) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc884.titlecase)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160452446) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160439364) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160446378) [haskell.packages.ghc901](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc901.titlecase)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160453934) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160437434) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160445155) [haskell.packages.ghc921](https://hydra.nixos.org/eval/1727540?filter=haskell.packages.ghc921.titlecase)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160449589) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160435610) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160449551) [haskellPackages](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.titlecase)
#### Unmaintained packages with build failure
<details><summary>30 job(s) </summary>

- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160452801) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160439013) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160436279) [haskellPackages.libBF](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.libBF)  :arrow_heading_up: 4 | 20
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160455616) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160449645) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160439430) [haskellPackages.ptr-poker](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.ptr-poker)  :arrow_heading_up: 3 | 4
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160448045) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160439658) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160440064) [haskellPackages.invertible](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.invertible)  :arrow_heading_up: 2 | 5
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160451781) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160436114) [[:penguin::x:]](https://hydra.nixos.org/build/160449097) [haskellPackages.brittany](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.brittany)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160457155) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160447471) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160453021) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.OrderedBits)  :arrow_heading_up: 1 | 36
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160437392) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160455656) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160447705) [haskellPackages.type-natural](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.type-natural)  :arrow_heading_up: 1 | 4
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160448126) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160451711) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160444202) [haskellPackages.long-double](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.long-double)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160442462) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160443828) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160443528) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.easytensor)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160453257) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160447564) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160451962) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160448013) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160438602) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160449591) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.unicode-properties)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160442826) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160451470) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160440611) [haskellPackages.accelerate-llvm](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.accelerate-llvm)  :arrow_heading_up: 0 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160437233) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160455941) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160449533) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.freetype2)  :arrow_heading_up: 0 | 7
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160448165) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160453018) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160436100) [haskellPackages.cdar-mBound](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.cdar-mBound)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160442198) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160451934) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160435617) [haskellPackages.quic](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.quic)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160456686) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160440055) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160447009) [haskellPackages.picosat](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160456993) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160445303) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160444768) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160449190) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160450234) [[:penguin::x:]](https://hydra.nixos.org/build/160447163) [haskellPackages.astro](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.astro) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/160452345) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160447544) [[:penguin::x:]](https://hydra.nixos.org/build/160436713) [haskellPackages.binary-io](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.binary-io) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160441752) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160447751) [[:penguin::x:]](https://hydra.nixos.org/build/160444164) [haskellPackages.doctest-parallel](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.doctest-parallel) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160440618) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160445846) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.gnome-keyring) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160443605) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160456649) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160446999) [haskellPackages.hora](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.hora) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160451239) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160440971) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160443365) [haskellPackages.hq](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.hq) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160449594) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160440357) [[:penguin::x:]](https://hydra.nixos.org/build/160439922) [haskellPackages.jet](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.jet) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160445429) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160456171) [[:penguin::x:]](https://hydra.nixos.org/build/160446239) [haskellPackages.pandoc-lua-marshal](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.pandoc-lua-marshal) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160450731) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160437435) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160437024) [haskellPackages.poker](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.poker) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160455109) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160443158) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160446588) [haskellPackages.powerqueue-distributed](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.powerqueue-distributed) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160447596) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160447064) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160447489) [haskellPackages.risc386](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.risc386) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160450885) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160449620) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160437914) [haskellPackages.shortbytestring](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.shortbytestring) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160440331) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160446697) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160445012) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/160446040) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160441343) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160435780) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.x86-64bit) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>34 job(s) </summary>

- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160444247) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160442380) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160450397) [haskellPackages.heist](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.heist)  :arrow_heading_up: 9 | 70
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160452871) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160444244) [haskellPackages.gi-javascriptcore](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.gi-javascriptcore)  :arrow_heading_up: 7 | 20
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160453459) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160435771) [haskellPackages.gi-webkit2](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.gi-webkit2)  :arrow_heading_up: 5 | 14
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160443625) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160450926) [haskellPackages.webkit2gtk3-javascriptcore](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.webkit2gtk3-javascriptcore)  :arrow_heading_up: 5 | 12
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160438663) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160445783) [haskellPackages.jsaddle-webkit2gtk](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.jsaddle-webkit2gtk)  :arrow_heading_up: 4 | 11
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160439371) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160454140) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160436967) [haskellPackages.pandoc-throw](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.pandoc-throw)  :arrow_heading_up: 2 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160436901) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160437166) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160443953) [haskellPackages.jsonifier](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.jsonifier)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160453859) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160435582) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160444407) [haskellPackages.compdoc](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.compdoc)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160457142) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160448997) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160453826) [haskellPackages.hls-brittany-plugin](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.hls-brittany-plugin)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160435684) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160449924) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160442718) [haskellPackages.opentelemetry-extra](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.opentelemetry-extra)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160443027) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160444316) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160449281) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.PrimitiveArray)  :arrow_heading_up: 0 | 35
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160456901) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160454881) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160442918) [haskellPackages.digestive-functors-heist](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.digestive-functors-heist)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160440781) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160443301) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160451375) [haskellPackages.yesod-markdown](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.yesod-markdown)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160457159) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160437715) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160448497) [haskellPackages.sized](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.sized)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160443254) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160453266) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160436341) [haskellPackages.snaplet-redis](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.snaplet-redis)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160439395) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160439442) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160448836) [haskellPackages.invertible-hxt](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.invertible-hxt)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160446812) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160436618) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160437476) [haskellPackages.compdoc-dhall-decoder](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.compdoc-dhall-decoder) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160450414) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160442758) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160438574) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160436358) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160452088) [haskellPackages.ghcjs-dom-hello](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.ghcjs-dom-hello) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160454880) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160452909) [haskellPackages.gi-webkit2webextension](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.gi-webkit2webextension) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160457185) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160440420) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160443991) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160449300) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160436248) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160450299) [haskellPackages.moonshine](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.moonshine) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160452923) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160446545) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160438494) [haskellPackages.opentelemetry-lightstep](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.opentelemetry-lightstep) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160456597) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160437281) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160438692) [haskellPackages.pandoc-stylefrommeta](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.pandoc-stylefrommeta) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160455264) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160445032) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160444910) [haskellPackages.rounded](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.rounded) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160447255) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160445055) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160445533) [haskellPackages.serversession-frontend-snap](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.serversession-frontend-snap) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160446219) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160446998) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160443497) [haskellPackages.slick](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.slick) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160446381) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160455431) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160440679) [haskellPackages.snaplet-ghcjs](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.snaplet-ghcjs) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160443390) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160443688) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160440315) [haskellPackages.snaplet-i18n](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.snaplet-i18n) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160452270) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160456269) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160444851) [haskellPackages.snaplet-purescript](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.snaplet-purescript) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160451788) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160453694) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160439350) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.unicode-names) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160456990) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160443419) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160448012) [haskellPackages.web-fpco](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.web-fpco) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160449482) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160441838) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160448359) [haskellPackages.web-inv-route](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.web-inv-route) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/160440682) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/160453774) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/160439437) [haskellPackages.wordchoice](https://hydra.nixos.org/eval/1727540?filter=haskellPackages.wordchoice) 
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
[data-lens](https://packdeps.haskellers.com/reverse/data-lens) :arrow_heading_up: 33  
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
[polysemy-plugin](https://packdeps.haskellers.com/reverse/polysemy-plugin) :arrow_heading_up: 20  
[secp256k1-haskell](https://packdeps.haskellers.com/reverse/secp256k1-haskell) :arrow_heading_up: 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) :arrow_heading_up: 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) :arrow_heading_up: 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) :arrow_heading_up: 19  
[numhask](https://packdeps.haskellers.com/reverse/numhask) :arrow_heading_up: 19  
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
