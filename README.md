### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1789063](https://hydra.nixos.org/eval/1789063) of nixpkgs commit [4801937](https://github.com/NixOS/nixpkgs/commits/4801937b452deb234d358da8daad0bd2b650f25f) as of 2023-01-11 06:18 UTC*

:yellow_circle: **Potential issues** (and possibly [evaluation errors](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates))
  * `mergeable` jobset is not finished.
  * `maintained` jobset is not finished.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | OutputLimitExceeded :warning: | TimedOut :hourglass::no_entry_sign: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1789063?filter=.aarch64-linux) | 20 | 10 | 2 | 2 | 13 | 6412 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1789063?filter=.x86_64-darwin) | 62 | 10 |  | 180 | 14 | 6137 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1789063?filter=.x86_64-linux) | 6 |  |  |  | 45 | 6469 | 
#### Maintained packages with build failure
- [ ] [ghc](https://hydra.nixos.org/eval/1789063?filter=ghc) @cdepillabout @expipiplus1 @guibou @maralorn @sternenseemann
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202430067) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202425639) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202416186) [haskellPackages](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.ghc)
  - [[:iphone::warning:]](https://hydra.nixos.org/build/204535242) [[:apple::x:]](https://hydra.nixos.org/build/204535235) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204535253) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1789063?filter=pkgsCross.ghcjs.haskellPackages.ghc)
- [ ] [wstunnel](https://hydra.nixos.org/eval/1789063?filter=wstunnel) @gebner
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204651908) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/204651906) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204651903) [toplevel](https://hydra.nixos.org/eval/1789063?filter=wstunnel)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204651902) [[:apple::x:]](https://hydra.nixos.org/build/204651905) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204651904) [haskellPackages](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.wstunnel)
#### Unmaintained packages with build failure
<details><summary>79 job(s) </summary>

- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/203512898) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203506397) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203501055) [haskellPackages.hw-json-simd](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hw-json-simd)  :arrow_heading_up: 3 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/203504151) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203509684) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203508490) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hw-simd)  :arrow_heading_up: 2 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/203508328) [[:apple::x:]](https://hydra.nixos.org/build/203502249) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203509145) [haskellPackages.quic](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.quic)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202421573) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202418260) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202425856) [haskellPackages.Crypto](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.Crypto)  :arrow_heading_up: 1 | 22
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203512336) [[:apple::x:]](https://hydra.nixos.org/build/203501945) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203502818) [haskellPackages.thyme](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.thyme)  :arrow_heading_up: 1 | 15
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203626672) [[:apple::x:]](https://hydra.nixos.org/build/203626684) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203626681) [haskellPackages.inline-r](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.inline-r)  :arrow_heading_up: 1 | 4
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202422717) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202426386) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202428144) [haskellPackages.long-double](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.long-double)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203511538) [[:apple::x:]](https://hydra.nixos.org/build/203504622) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203506040) [haskellPackages.posix-socket](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.posix-socket)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204521357) [[:apple::x:]](https://hydra.nixos.org/build/204521336) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204521348) [haskellPackages.gi-gdkx11](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.gi-gdkx11)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202417930) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202430377) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202419841) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202428372) [[:apple::x:]](https://hydra.nixos.org/build/202423142) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202421039) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.openal-ffi)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/203500850) [[:apple::x:]](https://hydra.nixos.org/build/203511578) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203507291) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.swisstable)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202427092) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202433526) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202428264) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.freetype2)  :arrow_heading_up: 0 | 9
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203510435) [[:apple::x:]](https://hydra.nixos.org/build/203506652) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203512693) [haskellPackages.pipes-zlib](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.pipes-zlib)  :arrow_heading_up: 0 | 5
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202423908) [[:apple::x:]](https://hydra.nixos.org/build/202435790) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202417988) [haskellPackages.hmidi](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hmidi)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/204648998) [[:apple::x:]](https://hydra.nixos.org/build/204649164) [[:penguin::x:]](https://hydra.nixos.org/build/204648873) [haskellPackages.redis-glob](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.redis-glob)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202435088) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202430782) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202426261) [haskellPackages.picosat](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202425185) [[:apple::x:]](https://hydra.nixos.org/build/203194258) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202428882) [haskellPackages.SDL-mixer](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.SDL-mixer)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204521401) [[:apple::x:]](https://hydra.nixos.org/build/204521439) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204521387) [haskellPackages.h-raylib](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.h-raylib)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202431795) [[:apple::x:]](https://hydra.nixos.org/build/202416334) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202434942) [haskellPackages.hamid](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hamid)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203505170) [[:apple::x:]](https://hydra.nixos.org/build/203511104) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203503505) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hmatrix-morpheus)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202427340) [[:apple::x:]](https://hydra.nixos.org/build/202430442) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202419088) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.huckleberry)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202423886) [[:apple::x:]](https://hydra.nixos.org/build/202425806) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202433480) [haskellPackages.select](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.select)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203502062) [[:apple::x:]](https://hydra.nixos.org/build/203508618) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203511126) [haskellPackages.simple-vec3](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.simple-vec3)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203505734) [[:apple::x:]](https://hydra.nixos.org/build/203501142) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203508546) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.sysinfo)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/204648923) [[:apple::x:]](https://hydra.nixos.org/build/204648655) [[:penguin::x:]](https://hydra.nixos.org/build/204648454) [haskellPackages.FailT](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.FailT) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203510531) [[:apple::x:]](https://hydra.nixos.org/build/203503861) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203501769) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.FractalArt) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202420797) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202436365) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202427200) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202435395) [[:apple::x:]](https://hydra.nixos.org/build/202417422) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202430954) [haskellPackages.al](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.al) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/204648222) [[:apple::x:]](https://hydra.nixos.org/build/204649240) [[:penguin::x:]](https://hydra.nixos.org/build/204649173) [haskellPackages.dep-t-dynamic](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.dep-t-dynamic) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203503717) [[:apple::x:]](https://hydra.nixos.org/build/203509434) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203509306) [haskellPackages.env-extra](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.env-extra) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203510575) [[:apple::x:]](https://hydra.nixos.org/build/203501166) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203507602) [haskellPackages.epub-tools](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.epub-tools) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203501527) [[:apple::x:]](https://hydra.nixos.org/build/203502009) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203502432) [haskellPackages.fsnotify-conduit](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.fsnotify-conduit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202430271) [[:apple::x:]](https://hydra.nixos.org/build/202436430) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202416704) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.fudgets) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204649311) [[:apple::x:]](https://hydra.nixos.org/build/204648179) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204648380) [haskellPackages.gerrit](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.gerrit) 
- [ ] [ghc-lib](https://hydra.nixos.org/eval/1789063?filter=ghc-lib) 
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202415372) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202420620) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202436058) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1789063?filter=haskell.packages.ghc8107.ghc-lib)
  - [[:iphone::x:]](https://hydra.nixos.org/build/202432716) [[:apple::x:]](https://hydra.nixos.org/build/202421851) [[:penguin::x:]](https://hydra.nixos.org/build/202432410) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1789063?filter=haskell.packages.ghc884.ghc-lib)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202431629) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202430373) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202433873) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1789063?filter=haskell.packages.ghc902.ghc-lib)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202428546) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202428909) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202428449) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1789063?filter=haskell.packages.ghc924.ghc-lib)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202433874) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202434011) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202429700) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1789063?filter=haskell.packages.ghc925.ghc-lib)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203389427) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203389426) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203389429) [haskell.packages.ghc944](https://hydra.nixos.org/eval/1789063?filter=haskell.packages.ghc944.ghc-lib)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202434897) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202423469) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202431067) [haskellPackages](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.ghc-lib)
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/204521376) [haskellPackages.gi-gtkosxapplication](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.gi-gtkosxapplication) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/203626686) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203626642) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.gnome-keyring) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/203194244) [haskellPackages.gtk-mac-integration](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.gtk-mac-integration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203502282) [[:apple::x:]](https://hydra.nixos.org/build/202416749) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203502415) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.gtk-traymanager) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/202434306) [haskellPackages.gtk3-mac-integration](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.gtk3-mac-integration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203512576) [[:apple::x:]](https://hydra.nixos.org/build/203508788) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203510541) [haskellPackages.highlight](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.highlight) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203504263) [[:apple::x:]](https://hydra.nixos.org/build/203502394) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203500823) [haskellPackages.hinotify-conduit](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hinotify-conduit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202430380) [[:apple::x:]](https://hydra.nixos.org/build/202435742) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202432776) [haskellPackages.hsshellscript](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hsshellscript) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202418023) [[:apple::x:]](https://hydra.nixos.org/build/202430436) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202426581) [haskellPackages.hssourceinfo](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hssourceinfo) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203505227) [[:apple::x:]](https://hydra.nixos.org/build/203506099) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203502314) [haskellPackages.hunspell-hs](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hunspell-hs) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/203501053) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203507800) [haskellPackages.inline-asm](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.inline-asm) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203506577) [[:apple::x:]](https://hydra.nixos.org/build/203508553) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203504651) [haskellPackages.interprocess](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.interprocess) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203505836) [[:apple::x:]](https://hydra.nixos.org/build/203509523) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203507126) [haskellPackages.ipcvar](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.ipcvar) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/202424556) [haskellPackages.kqueue](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.kqueue) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202429811) [[:apple::x:]](https://hydra.nixos.org/build/202415593) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202430903) [haskellPackages.linux-framebuffer](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.linux-framebuffer) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204648719) [[:apple::x:]](https://hydra.nixos.org/build/204648843) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204649365) [haskellPackages.mediawiki2latex](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.mediawiki2latex) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202416216) [[:apple::x:]](https://hydra.nixos.org/build/202433801) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202429864) [haskellPackages.memfd](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.memfd) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203505044) [[:apple::x:]](https://hydra.nixos.org/build/203504108) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203512510) [haskellPackages.persistent-pagination](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.persistent-pagination) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203510813) [[:apple::x:]](https://hydra.nixos.org/build/203512536) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203501050) [haskellPackages.phatsort](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.phatsort) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203510536) [[:apple::x:]](https://hydra.nixos.org/build/203503461) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203504455) [haskellPackages.ping-wrapper](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.ping-wrapper) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203509982) [[:apple::x:]](https://hydra.nixos.org/build/203513028) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203501314) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.posix-timer) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203505195) [[:apple::x:]](https://hydra.nixos.org/build/203505651) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203504186) [haskellPackages.powerqueue-distributed](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.powerqueue-distributed) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203512909) [[:apple::x:]](https://hydra.nixos.org/build/203509486) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203512861) [haskellPackages.procex](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.procex) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203504459) [[:apple::x:]](https://hydra.nixos.org/build/203512730) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203503468) [haskellPackages.pthread](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.pthread) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204649180) [[:apple::x:]](https://hydra.nixos.org/build/204648145) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204649069) [haskellPackages.sandwich-webdriver](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.sandwich-webdriver) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202432097) [[:apple::x:]](https://hydra.nixos.org/build/202425944) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202427952) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.shared-memory) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/204648616) [[:apple::x:]](https://hydra.nixos.org/build/204649248) [[:penguin::x:]](https://hydra.nixos.org/build/204649074) [haskellPackages.sockets-and-pipes](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.sockets-and-pipes) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203510243) [[:apple::x:]](https://hydra.nixos.org/build/203507250) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203507475) [haskellPackages.tailfile-hinotify](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.tailfile-hinotify) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/203502504) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203501830) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203506715) [haskellPackages.the-snip](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.the-snip) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202424843) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202430364) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202432968) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/202424744) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202416582) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202416260) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.x86-64bit) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/204648272) [[:apple::x:]](https://hydra.nixos.org/build/204649056) [[:penguin::x:]](https://hydra.nixos.org/build/204648961) [haskellPackages.xcffib](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.xcffib) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202418227) [[:apple::x:]](https://hydra.nixos.org/build/202419197) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202436039) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.xmonad-utils) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202426690) [[:apple::x:]](https://hydra.nixos.org/build/202430057) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202426520) [haskellPackages.yoga](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.yoga) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202425259) [[:apple::x:]](https://hydra.nixos.org/build/202416959) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202418284) [haskellPackages.zot](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.zot) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202431702) [[:apple::x:]](https://hydra.nixos.org/build/202433071) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202420076) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>22 job(s) </summary>

- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203505129) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203512310) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203506803) [haskellPackages.hw-json-standard-cursor](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hw-json-standard-cursor)  :arrow_heading_up: 1 | 6
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203503887) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203507727) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203505091) [haskellPackages.hw-json-simple-cursor](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hw-json-simple-cursor)  :arrow_heading_up: 1 | 4
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203505964) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203510704) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203508664) [haskellPackages.http3](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.http3)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203507311) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203504733) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203512759) [haskellPackages.hw-dsv](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hw-dsv)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203501709) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203501913) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203504547) [haskellPackages.hw-json](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hw-json)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203510590) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203512567) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203509561) [haskellPackages.hS3](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hS3)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203512106) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203506643) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203506260) [haskellPackages.network-dns](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.network-dns)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203626676) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203626648) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203626629) [haskellPackages.H](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.H) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203500987) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203500827) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203512205) [haskellPackages.fastparser](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.fastparser) 
- [ ] [hello](https://hydra.nixos.org/eval/1789063?filter=hello) 
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202434015) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/202421551) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202430153) [haskellPackages](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hello)
  - [[:iphone::warning:]](https://hydra.nixos.org/build/204535245) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/204535259) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204535232) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1789063?filter=pkgsCross.ghcjs.haskellPackages.hello)
  -   [[:penguin::hourglass_flowing_sand:]](https://hydra.nixos.org/build/204928287) [pkgsMusl.haskellPackages](https://hydra.nixos.org/eval/1789063?filter=pkgsMusl.haskellPackages.hello)
  -   [[:penguin::hourglass_flowing_sand:]](https://hydra.nixos.org/build/204928239) [pkgsStatic.haskell.packages.native-bignum.ghc924](https://hydra.nixos.org/eval/1789063?filter=pkgsStatic.haskell.packages.native-bignum.ghc924.hello)
  -   [[:penguin::hourglass_flowing_sand:]](https://hydra.nixos.org/build/204928256) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1789063?filter=pkgsStatic.haskellPackages.hello)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203508851) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203510481) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203506726) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203512153) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203502782) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203511995) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/204648545) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/204648557) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/204648397) [haskellPackages.ihaskell-inline-r](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.ihaskell-inline-r) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/203509260) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203504666) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203502308) [haskellPackages.intricacy](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.intricacy) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203503884) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/203511268) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203508585) [haskellPackages.rounded-hw](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.rounded-hw) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203501634) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/203504833) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/203502943) [haskellPackages.warp-quic](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.warp-quic) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/202421771) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/202420460) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/202420292) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1789063?filter=haskellPackages.xbattbar) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[amazonka-core](https://packdeps.haskellers.com/reverse/amazonka-core) :arrow_heading_up: 187  
[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) :arrow_heading_up: 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) :arrow_heading_up: 153  
[th-desugar](https://packdeps.haskellers.com/reverse/th-desugar) :arrow_heading_up: 57  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) :arrow_heading_up: 56  
[util](https://packdeps.haskellers.com/reverse/util) :arrow_heading_up: 49  
[derive](https://packdeps.haskellers.com/reverse/derive) :arrow_heading_up: 48  
[cgi](https://packdeps.haskellers.com/reverse/cgi) :arrow_heading_up: 46  
[amazonka](https://packdeps.haskellers.com/reverse/amazonka) :arrow_heading_up: 45  
[TypeCompose](https://packdeps.haskellers.com/reverse/TypeCompose) :arrow_heading_up: 44  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) :arrow_heading_up: 42  
[PrimitiveArray](https://packdeps.haskellers.com/reverse/PrimitiveArray) :arrow_heading_up: 35  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) :arrow_heading_up: 33  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) :arrow_heading_up: 31  
[storablevector](https://packdeps.haskellers.com/reverse/storablevector) :arrow_heading_up: 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) :arrow_heading_up: 30  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) :arrow_heading_up: 29  
[sydtest](https://packdeps.haskellers.com/reverse/sydtest) :arrow_heading_up: 26  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) :arrow_heading_up: 25  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) :arrow_heading_up: 25  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) :arrow_heading_up: 22  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) :arrow_heading_up: 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) :arrow_heading_up: 22  
[BiobaseTypes](https://packdeps.haskellers.com/reverse/BiobaseTypes) :arrow_heading_up: 21  
[alg](https://packdeps.haskellers.com/reverse/alg) :arrow_heading_up: 21  
[amazonka-s3](https://packdeps.haskellers.com/reverse/amazonka-s3) :arrow_heading_up: 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) :arrow_heading_up: 21  
[polysemy-resume](https://packdeps.haskellers.com/reverse/polysemy-resume) :arrow_heading_up: 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) :arrow_heading_up: 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) :arrow_heading_up: 20  
[bzlib](https://packdeps.haskellers.com/reverse/bzlib) :arrow_heading_up: 20  
[polysemy-conc](https://packdeps.haskellers.com/reverse/polysemy-conc) :arrow_heading_up: 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) :arrow_heading_up: 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) :arrow_heading_up: 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) :arrow_heading_up: 19  
[fay](https://packdeps.haskellers.com/reverse/fay) :arrow_heading_up: 19  
[wx](https://packdeps.haskellers.com/reverse/wx) :arrow_heading_up: 19  
[BiobaseENA](https://packdeps.haskellers.com/reverse/BiobaseENA) :arrow_heading_up: 18  
[asn1-data](https://packdeps.haskellers.com/reverse/asn1-data) :arrow_heading_up: 18  
[dbus-core](https://packdeps.haskellers.com/reverse/dbus-core) :arrow_heading_up: 18  
[gtksourceview2](https://packdeps.haskellers.com/reverse/gtksourceview2) :arrow_heading_up: 18  
[hsc3](https://packdeps.haskellers.com/reverse/hsc3) :arrow_heading_up: 18  
[polysemy-log](https://packdeps.haskellers.com/reverse/polysemy-log) :arrow_heading_up: 18  
[ukrainian-phonetics-basic](https://packdeps.haskellers.com/reverse/ukrainian-phonetics-basic) :arrow_heading_up: 18  
[BiobaseXNA](https://packdeps.haskellers.com/reverse/BiobaseXNA) :arrow_heading_up: 17  
[HGamer3D-Data](https://packdeps.haskellers.com/reverse/HGamer3D-Data) :arrow_heading_up: 17  
[certificate](https://packdeps.haskellers.com/reverse/certificate) :arrow_heading_up: 17  
[clash-prelude](https://packdeps.haskellers.com/reverse/clash-prelude) :arrow_heading_up: 17  
[clay](https://packdeps.haskellers.com/reverse/clay) :arrow_heading_up: 17  
[dbus-client](https://packdeps.haskellers.com/reverse/dbus-client) :arrow_heading_up: 17  
</details>


*:arrow_heading_up:: The number of packages that depend (directly or indirectly) on this package (if any). If two numbers are shown the first (lower) number considers only packages which currently have enabled hydra jobs, i.e. are not marked broken. The second (higher) number considers all packages.*

*Report generated with [maintainers/scripts/haskell/hydra-report.hs](https://github.com/NixOS/nixpkgs/blob/haskell-updates/maintainers/scripts/haskell/hydra-report.hs)*


----------------------------------------------------------------------

This README.md is automatically updated every 6 hours with the status of the
[`haskell-updates` branch/jobset on Hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
from [Nixpkgs](https://github.com/NixOS/nixpkgs).  This is mostly only of
interest to the [Nixpkgs Haskell maintainers](https://github.com/orgs/NixOS/teams/haskell).

See the
[haskell-modules/HACKING.md](https://github.com/NixOS/nixpkgs/blob/haskell-updates/pkgs/development/haskell-modules/HACKING.md)
file for more information about this build report.

You may also be interested in the currently open
[`haskell-updates` PR in Nixpkgs](https://github.com/nixos/nixpkgs/pulls?q=is%3Apr+is%3Aopen+head%3Ahaskell-updates).

You can force the GitHub Action to run (and the README.md to be updated) by
manually running the Action.  To do this, go to the Action list screen
(https://github.com/cdepillabout/nix-haskell-updates-status/actions),
click on any of the Workflow runs, and then click the `Re-run jobs` button.
