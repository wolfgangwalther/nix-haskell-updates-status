### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1764192](https://hydra.nixos.org/eval/1764192) of nixpkgs commit [9fd1366](https://github.com/NixOS/nixpkgs/commits/9fd1366f68ac00809f2b7dce3dfba075e40e696f) as of 2022-05-29 12:24 UTC*

:yellow_circle: **Potential issues**
  * `mergeable` jobset is not finished.
  * `maintained` jobset is not finished.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1764192?filter=.aarch64-linux) | 19 | 31 | 32 | 6220 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1764192?filter=.x86_64-darwin) | 51 | 15 | 7 | 6167 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1764192?filter=.x86_64-linux) | 1 | 12 | 7 | 6309 | 
#### Unmaintained packages with build failure
<details><summary>67 job(s) </summary>

- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178285123) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178272629) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178277443) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.OrderedBits)  :arrow_heading_up: 5 | 36
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178276605) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178280959) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178280826) [haskellPackages.hw-json-simd](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hw-json-simd)  :arrow_heading_up: 2 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178278965) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178279028) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178288026) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hw-simd)  :arrow_heading_up: 2 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178284195) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178274912) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178277548) [haskellPackages.quic](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.quic)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178285950) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178285407) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178285409) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.freetype2)  :arrow_heading_up: 1 | 8
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178278018) [[:apple::x:]](https://hydra.nixos.org/build/178280083) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273777) [haskellPackages.free-vector-spaces](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.free-vector-spaces)  :arrow_heading_up: 1 | 7
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178276670) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178283215) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178287231) [haskellPackages.long-double](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.long-double)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178288499) [[:apple::x:]](https://hydra.nixos.org/build/178285336) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178272536) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.easytensor)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178290229) [[:apple::x:]](https://hydra.nixos.org/build/178283545) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178271575) [haskellPackages.grab](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.grab)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178277992) [[:apple::x:]](https://hydra.nixos.org/build/178272857) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178287184) [haskellPackages.keep-alive](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.keep-alive)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178275003) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178272836) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178289735) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178273182) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178279420) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178281330) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.swisstable)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178286072) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178277930) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178278716) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.unicode-properties)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178289515) [[:apple::x:]](https://hydra.nixos.org/build/178278622) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178280464) [haskellPackages.zip](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.zip)  :arrow_heading_up: 0 | 5
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178286606) [[:apple::x:]](https://hydra.nixos.org/build/178288573) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178283296) [haskellPackages.PyF](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.PyF)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178286522) [[:apple::x:]](https://hydra.nixos.org/build/178286158) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273642) [haskellPackages.hmidi](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hmidi)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178281180) [[:apple::x:]](https://hydra.nixos.org/build/178282341) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178282250) [haskellPackages.posix-socket](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.posix-socket)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178280259) [[:apple::x:]](https://hydra.nixos.org/build/178283506) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178278624) [haskellPackages.gi-gdkx11](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gi-gdkx11)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178288125) [[:apple::x:]](https://hydra.nixos.org/build/178287718) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178284672) [haskellPackages.hamid](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hamid)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178287480) [[:apple::x:]](https://hydra.nixos.org/build/178273939) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273305) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hmatrix-morpheus)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178290144) [[:apple::x:]](https://hydra.nixos.org/build/178283374) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178286630) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.huckleberry)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178283644) [[:apple::x:]](https://hydra.nixos.org/build/178279872) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178279156) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.openal-ffi)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178273991) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178282452) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178289096) [haskellPackages.picosat](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178274233) [[:apple::x:]](https://hydra.nixos.org/build/178284335) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178274444) [haskellPackages.select](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.select)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178282154) [[:apple::x:]](https://hydra.nixos.org/build/178287249) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178287886) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.sysinfo)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178284278) [[:apple::x:]](https://hydra.nixos.org/build/178275745) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178276292) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.FractalArt) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178281305) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178278249) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178272433) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/178288928) [[:apple::x:]](https://hydra.nixos.org/build/178280462) [[:penguin::hourglass_flowing_sand:]](https://hydra.nixos.org/build/178281780) [haskellPackages.bindings-common](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.bindings-common) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178289230) [[:apple::x:]](https://hydra.nixos.org/build/178271517) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178282858) [haskellPackages.chiphunk](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.chiphunk) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178283177) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178275093) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178284660) [haskellPackages.comfort-fftw](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.comfort-fftw) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178285941) [[:apple::x:]](https://hydra.nixos.org/build/178271313) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178278975) [haskellPackages.diskhash](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.diskhash) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178288544) [[:apple::x:]](https://hydra.nixos.org/build/178280352) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178284216) [haskellPackages.epub-tools](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.epub-tools) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178273268) [[:apple::x:]](https://hydra.nixos.org/build/178282383) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178286183) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.fudgets) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178277586) [[:apple::x:]](https://hydra.nixos.org/build/178280937) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178289324) [haskellPackages.gerrit](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gerrit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178274537) [[:apple::x:]](https://hydra.nixos.org/build/178273837) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178275535) [haskellPackages.ghc-gc-hook](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.ghc-gc-hook) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/178274646) [haskellPackages.gi-gtkosxapplication](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gi-gtkosxapplication) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/178287042) [haskellPackages.gtk-mac-integration](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gtk-mac-integration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178275713) [[:apple::x:]](https://hydra.nixos.org/build/178278039) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178290225) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gtk-traymanager) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/178284388) [haskellPackages.gtk3-mac-integration](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gtk3-mac-integration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178287395) [[:apple::x:]](https://hydra.nixos.org/build/178286412) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178281461) [haskellPackages.hid](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hid) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178290005) [[:apple::x:]](https://hydra.nixos.org/build/178276037) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178287327) [haskellPackages.hinotify-conduit](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hinotify-conduit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178288912) [[:apple::x:]](https://hydra.nixos.org/build/178276375) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273150) [haskellPackages.hsshellscript](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hsshellscript) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178276957) [[:apple::x:]](https://hydra.nixos.org/build/178277983) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273372) [haskellPackages.hssourceinfo](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hssourceinfo) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178287443) [[:apple::x:]](https://hydra.nixos.org/build/178271621) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178279998) [haskellPackages.ipcvar](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.ipcvar) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178275113) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178277483) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178276703) [haskellPackages.jammittools](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.jammittools) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/178285837) [haskellPackages.kqueue](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.kqueue) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178284887) [[:apple::x:]](https://hydra.nixos.org/build/178278380) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178282105) [haskellPackages.linux-framebuffer](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.linux-framebuffer) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178284645) [[:apple::x:]](https://hydra.nixos.org/build/178282690) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273633) [haskellPackages.mediawiki2latex](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.mediawiki2latex) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178276947) [[:apple::x:]](https://hydra.nixos.org/build/178274842) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178281105) [haskellPackages.mercury-api](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.mercury-api) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178272563) [[:apple::x:]](https://hydra.nixos.org/build/178278551) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178276039) [haskellPackages.nano-cryptr](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.nano-cryptr) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178289808) [[:apple::x:]](https://hydra.nixos.org/build/178274903) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178289015) [haskellPackages.persistent-pagination](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.persistent-pagination) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178282995) [[:apple::x:]](https://hydra.nixos.org/build/178276818) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178281836) [haskellPackages.phatsort](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.phatsort) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178285992) [[:apple::x:]](https://hydra.nixos.org/build/178281018) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273468) [haskellPackages.ping-wrapper](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.ping-wrapper) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178275173) [[:apple::x:]](https://hydra.nixos.org/build/178285699) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178272999) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.posix-timer) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178285931) [[:apple::x:]](https://hydra.nixos.org/build/178288076) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273271) [haskellPackages.pthread](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.pthread) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178289195) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178275142) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178275290) [haskellPackages.risc386](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.risc386) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178279976) [[:apple::x:]](https://hydra.nixos.org/build/178273821) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178283286) [haskellPackages.sfml-audio](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.sfml-audio) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178277600) [[:apple::x:]](https://hydra.nixos.org/build/178289828) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178271547) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.shared-memory) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178285105) [[:apple::x:]](https://hydra.nixos.org/build/178272721) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178276259) [haskellPackages.slugify](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.slugify) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178280978) [[:apple::x:]](https://hydra.nixos.org/build/178277273) [[:penguin::x:]](https://hydra.nixos.org/build/178272078) [haskellPackages.strongweak](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.strongweak) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178272821) [[:apple::x:]](https://hydra.nixos.org/build/178288892) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178282237) [haskellPackages.tailfile-hinotify](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.tailfile-hinotify) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178272070) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178279807) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178281086) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/178274027) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178274970) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178282974) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.x86-64bit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178280605) [[:apple::x:]](https://hydra.nixos.org/build/178271733) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178278931) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.xmonad-utils) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178279805) [[:apple::x:]](https://hydra.nixos.org/build/178284219) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178288549) [haskellPackages.yoga](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.yoga) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178271201) [[:apple::x:]](https://hydra.nixos.org/build/178282945) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178286219) [haskellPackages.zot](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.zot) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178284390) [[:apple::x:]](https://hydra.nixos.org/build/178281490) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178278207) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>42 job(s) </summary>

- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178285241) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178284451) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178283253) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.PrimitiveArray)  :arrow_heading_up: 4 | 35
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178290282) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178287751) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178284157) [haskellPackages.BiobaseTypes](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.BiobaseTypes)  :arrow_heading_up: 3 | 21
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178280784) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178272300) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178286231) [haskellPackages.BiobaseENA](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.BiobaseENA)  :arrow_heading_up: 1 | 18
- [ ] [hoogle](https://hydra.nixos.org/eval/1764192?filter=hoogle)  :arrow_heading_up: 1 | 3
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178283761) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178272577) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178277140) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1764192?filter=haskell.packages.ghc8107.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178287314) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178273152) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273519) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1764192?filter=haskell.packages.ghc884.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178281632) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178284749) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178290228) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1764192?filter=haskell.packages.ghc902.hoogle)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178276258) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178284360) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178272053) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1764192?filter=haskell.packages.ghc922.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178281203) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178288571) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178284190) [haskellPackages](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hoogle)
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/178291643) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178291654) [haskellPackages.hbro](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hbro)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178289799) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178279233) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178275433) [haskellPackages.http3](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.http3)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178277223) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178273421) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178283012) [haskellPackages.BiobaseXNA](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.BiobaseXNA)  :arrow_heading_up: 0 | 17
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178279446) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178271856) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178284256) [haskellPackages.hw-json-standard-cursor](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hw-json-standard-cursor)  :arrow_heading_up: 0 | 6
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178272735) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178287439) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178279024) [haskellPackages.hw-json-simple-cursor](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hw-json-simple-cursor)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178275461) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178283312) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178273945) [haskellPackages.BiobaseFasta](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.BiobaseFasta)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178278493) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178285703) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178280651) [haskellPackages.hw-dsv](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hw-dsv)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178274024) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178275659) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178286920) [haskellPackages.dde](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.dde)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178284449) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178283088) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178288563) [haskellPackages.GuiHaskell](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.GuiHaskell) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178287321) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178288731) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178276867) [haskellPackages.HPlot](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.HPlot) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178290290) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178275165) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178285303) [haskellPackages.align-audio](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.align-audio) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178273884) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178281519) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178286312) [haskellPackages.bluetile](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.bluetile) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178271913) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178277793) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178285816) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178284977) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178274185) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178285384) [haskellPackages.gladexml-accessor](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gladexml-accessor) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178278384) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178289989) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178285817) [haskellPackages.grab-form](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.grab-form) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178286962) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178273051) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178286723) [haskellPackages.gtk2hs-cast-glade](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.gtk2hs-cast-glade) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178287159) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178286595) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178287410) [haskellPackages.harfbuzz-pure](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.harfbuzz-pure) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/178291633) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178291628) [haskellPackages.hbro-contrib](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hbro-contrib) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178285873) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178273073) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178284971) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178287519) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178281302) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178280272) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178274277) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178280739) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178286339) [haskellPackages.hstzaar](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hstzaar) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178278822) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178283583) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178280856) [haskellPackages.hw-simd-cli](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.hw-simd-cli) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178285134) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178283542) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178277086) [haskellPackages.kmn-programming](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.kmn-programming) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178274229) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178276277) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178277912) [haskellPackages.minesweeper](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.minesweeper) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178284453) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178287133) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178289278) [haskellPackages.nymphaea](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.nymphaea) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178281091) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178278142) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178289383) [haskellPackages.postgresql-replicant](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.postgresql-replicant) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178271640) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178275189) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178274294) [haskellPackages.proplang](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.proplang) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178278871) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178277278) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178277874) [haskellPackages.rounded-hw](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.rounded-hw) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178283976) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178277064) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178272995) [haskellPackages.showdown](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.showdown) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178280601) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178282189) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178289227) [haskellPackages.sound-collage](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.sound-collage) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178286016) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178274303) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178277154) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.unicode-names) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178271213) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/178288989) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178288871) [haskellPackages.warp-quic](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.warp-quic) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/178284534) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/178272228) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/178289847) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1764192?filter=haskellPackages.xbattbar) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[amazonka-core](https://packdeps.haskellers.com/reverse/amazonka-core) :arrow_heading_up: 185  
[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) :arrow_heading_up: 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) :arrow_heading_up: 153  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) :arrow_heading_up: 56  
[util](https://packdeps.haskellers.com/reverse/util) :arrow_heading_up: 49  
[derive](https://packdeps.haskellers.com/reverse/derive) :arrow_heading_up: 48  
[amazonka](https://packdeps.haskellers.com/reverse/amazonka) :arrow_heading_up: 43  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) :arrow_heading_up: 42  
[parseargs](https://packdeps.haskellers.com/reverse/parseargs) :arrow_heading_up: 42  
[syb-with-class](https://packdeps.haskellers.com/reverse/syb-with-class) :arrow_heading_up: 42  
[MonadCatchIO-transformers](https://packdeps.haskellers.com/reverse/MonadCatchIO-transformers) :arrow_heading_up: 41  
[autodocodec](https://packdeps.haskellers.com/reverse/autodocodec) :arrow_heading_up: 33  
[data-lens](https://packdeps.haskellers.com/reverse/data-lens) :arrow_heading_up: 33  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) :arrow_heading_up: 33  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) :arrow_heading_up: 31  
[language-ecmascript](https://packdeps.haskellers.com/reverse/language-ecmascript) :arrow_heading_up: 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) :arrow_heading_up: 30  
[ip](https://packdeps.haskellers.com/reverse/ip) :arrow_heading_up: 29  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) :arrow_heading_up: 29  
[jmacro](https://packdeps.haskellers.com/reverse/jmacro) :arrow_heading_up: 29  
[validity-aeson](https://packdeps.haskellers.com/reverse/validity-aeson) :arrow_heading_up: 29  
[text-format](https://packdeps.haskellers.com/reverse/text-format) :arrow_heading_up: 28  
[autodocodec-schema](https://packdeps.haskellers.com/reverse/autodocodec-schema) :arrow_heading_up: 27  
[mmsyn3](https://packdeps.haskellers.com/reverse/mmsyn3) :arrow_heading_up: 27  
[autodocodec-yaml](https://packdeps.haskellers.com/reverse/autodocodec-yaml) :arrow_heading_up: 26  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) :arrow_heading_up: 26  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) :arrow_heading_up: 25  
[web-routes-th](https://packdeps.haskellers.com/reverse/web-routes-th) :arrow_heading_up: 24  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) :arrow_heading_up: 23  
[ixset-typed](https://packdeps.haskellers.com/reverse/ixset-typed) :arrow_heading_up: 23  
[sydtest](https://packdeps.haskellers.com/reverse/sydtest) :arrow_heading_up: 23  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) :arrow_heading_up: 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) :arrow_heading_up: 22  
[alg](https://packdeps.haskellers.com/reverse/alg) :arrow_heading_up: 21  
[amazonka-s3](https://packdeps.haskellers.com/reverse/amazonka-s3) :arrow_heading_up: 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) :arrow_heading_up: 21  
[userid](https://packdeps.haskellers.com/reverse/userid) :arrow_heading_up: 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) :arrow_heading_up: 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) :arrow_heading_up: 20  
[subG](https://packdeps.haskellers.com/reverse/subG) :arrow_heading_up: 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) :arrow_heading_up: 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) :arrow_heading_up: 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) :arrow_heading_up: 19  
[fay](https://packdeps.haskellers.com/reverse/fay) :arrow_heading_up: 19  
[harp](https://packdeps.haskellers.com/reverse/harp) :arrow_heading_up: 19  
[hsx2hs](https://packdeps.haskellers.com/reverse/hsx2hs) :arrow_heading_up: 19  
[ixset](https://packdeps.haskellers.com/reverse/ixset) :arrow_heading_up: 19  
[wx](https://packdeps.haskellers.com/reverse/wx) :arrow_heading_up: 19  
[asn1-data](https://packdeps.haskellers.com/reverse/asn1-data) :arrow_heading_up: 18  
[dbus-core](https://packdeps.haskellers.com/reverse/dbus-core) :arrow_heading_up: 18  
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

You may also be interested in the currently open
[`haskell-updates` PR in Nixpkgs](https://github.com/nixos/nixpkgs/pulls?q=is%3Apr+is%3Aopen+head%3Ahaskell-updates).

You can force the GitHub Action to run (and the README.md to be updated) by
manually running the Action.  To do this, go to the Action list screen
(https://github.com/cdepillabout/nix-haskell-updates-status/actions),
click on any of the Workflow runs, and then click the `Re-run jobs` button.
