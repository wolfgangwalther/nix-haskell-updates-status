### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1702901](https://hydra.nixos.org/eval/1702901) of nixpkgs commit [6c413ed](https://github.com/NixOS/nixpkgs/commits/6c413ed5bf5092c2ef6e05b6c22acf32b1c36f08) as of 2021-09-09 06:15 UTC*
#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | TimedOut :hourglass::no_entry_sign: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1702901?filter=.aarch64-linux) | 20 | 10 | 3 |  | 6700 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1702901?filter=.x86_64-darwin) | 50 | 34 | 3 | 1 | 6596 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1702901?filter=.x86_64-linux) | 2 | 3 |  |  | 6771 | 
#### Maintained packages with failed dependency
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1702901?filter=haskell-language-server) @maralorn
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152362454) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152362446) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152362448) [toplevel](https://hydra.nixos.org/eval/1702901?filter=haskell-language-server)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152362456) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152362422) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152362487) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1702901?filter=haskell.packages.ghc8107.haskell-language-server)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152316667) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152314885) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152322826) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1702901?filter=haskell.packages.ghc884.haskell-language-server)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152362445) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152362419) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152362447) [haskellPackages](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.haskell-language-server)
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152373448) [maintained](https://hydra.nixos.org/eval/1702901?filter=maintained) @cdepillabout @expipiplus1 @maralorn @sternenseemann
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152362500) [mergeable](https://hydra.nixos.org/eval/1702901?filter=mergeable) @cdepillabout @expipiplus1 @maralorn @sternenseemann
#### Unmaintained packages with build failure
<details><summary>69 job(s) </summary>

- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152321470) [[:apple::x:]](https://hydra.nixos.org/build/152318672) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152322782) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.FractalArt) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151723150) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151731482) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151717379) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152318988) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152317031) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152319415) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.OrderedBits) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152323302) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152318404) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318942) [haskellPackages.accelerate-llvm](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.accelerate-llvm) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151975782) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151975423) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151977034) [haskellPackages.cdar-mBound](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.cdar-mBound) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151717421) [[:apple::x:]](https://hydra.nixos.org/build/151730444) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151719104) [haskellPackages.chiphunk](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.chiphunk) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151970661) [[:apple::x:]](https://hydra.nixos.org/build/151977550) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151978850) [haskellPackages.di-core](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.di-core) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151724586) [[:apple::x:]](https://hydra.nixos.org/build/151715416) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151723716) [haskellPackages.discount](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.discount) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151722308) [[:apple::x:]](https://hydra.nixos.org/build/151717848) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151715159) [haskellPackages.diskhash](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.diskhash) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151719661) [[:apple::x:]](https://hydra.nixos.org/build/151735374) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151725956) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.easytensor) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152315881) [[:apple::x:]](https://hydra.nixos.org/build/152318892) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314763) [haskellPackages.epub-tools](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.epub-tools) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152318977) [[:apple::x:]](https://hydra.nixos.org/build/152318064) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152319197) [haskellPackages.exinst](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.exinst) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151730435) [[:apple::x:]](https://hydra.nixos.org/build/151723038) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151729481) [haskellPackages.float128](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.float128) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151727007) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151722041) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151715089) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.freetype2) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152324859) [[:apple::x:]](https://hydra.nixos.org/build/152316779) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152317315) [haskellPackages.gi-gdkx11](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.gi-gdkx11) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151727306) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151724718) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.gnome-keyring) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152319877) [[:apple::x:]](https://hydra.nixos.org/build/152317687) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315220) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.gtk-traymanager) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152323277) [[:apple::x:]](https://hydra.nixos.org/build/152318685) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318788) [haskellPackages.hamid](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hamid) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151725530) [[:apple::x:]](https://hydra.nixos.org/build/151724884) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151728947) [haskellPackages.hid](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hid) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152322895) [[:apple::x:]](https://hydra.nixos.org/build/152317465) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152317119) [haskellPackages.higher-leveldb](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.higher-leveldb) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152314408) [[:apple::x:]](https://hydra.nixos.org/build/152322578) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152316799) [haskellPackages.highlight](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.highlight) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152362455) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152362485) [[:penguin::x:]](https://hydra.nixos.org/build/152362480) [haskellPackages.hls-splice-plugin](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hls-splice-plugin) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152316945) [[:apple::x:]](https://hydra.nixos.org/build/152314988) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152317393) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hmatrix-morpheus) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151731650) [[:apple::x:]](https://hydra.nixos.org/build/151721565) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151730119) [haskellPackages.hmidi](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hmidi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152321604) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152319918) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152324298) [haskellPackages.hq](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hq) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151976717) [[:apple::x:]](https://hydra.nixos.org/build/151973170) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151975997) [haskellPackages.hs](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hs) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151730025) [[:apple::x:]](https://hydra.nixos.org/build/151733963) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151718516) [haskellPackages.hsshellscript](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hsshellscript) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151731588) [[:apple::x:]](https://hydra.nixos.org/build/151727903) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151734139) [haskellPackages.hssourceinfo](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hssourceinfo) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151730332) [[:apple::x:]](https://hydra.nixos.org/build/151718342) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151718449) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.huckleberry) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151972026) [[:apple::x:]](https://hydra.nixos.org/build/151980521) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151979069) [haskellPackages.ipcvar](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.ipcvar) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151720909) [[:apple::x:]](https://hydra.nixos.org/build/151722888) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151715932) [haskellPackages.keep-alive](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.keep-alive) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151734395) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151731771) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151722294) [haskellPackages.libBF](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.libBF) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152316328) [[:apple::x:]](https://hydra.nixos.org/build/152319378) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314071) [haskellPackages.loc](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.loc) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151721890) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151717720) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151715215) [haskellPackages.long-double](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.long-double) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152320614) [[:apple::x:]](https://hydra.nixos.org/build/152323310) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318070) [haskellPackages.mediawiki2latex](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.mediawiki2latex) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151973124) [[:apple::x:]](https://hydra.nixos.org/build/151972400) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151974760) [haskellPackages.mercury-api](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.mercury-api) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151732196) [[:apple::x:]](https://hydra.nixos.org/build/151725784) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151731126) [haskellPackages.nano-cryptr](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nano-cryptr) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152321381) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152317748) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318406) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nlopt-haskell) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152315768) [[:apple::x:]](https://hydra.nixos.org/build/152320030) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152317433) [haskellPackages.nri-prelude](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nri-prelude) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152315197) [[:apple::x:]](https://hydra.nixos.org/build/152324890) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152321940) [haskellPackages.opencv](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.opencv) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152317067) [[:apple::x:]](https://hydra.nixos.org/build/152318034) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152324236) [haskellPackages.persistent-pagination](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.persistent-pagination) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151717765) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151718317) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151717284) [haskellPackages.picosat](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.picosat) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152322477) [[:apple::x:]](https://hydra.nixos.org/build/152318725) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318733) [haskellPackages.ping-wrapper](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.ping-wrapper) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152317504) [[:apple::x:]](https://hydra.nixos.org/build/152321444) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152323212) [haskellPackages.pipes-zlib](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.pipes-zlib) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152317771) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152322344) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152321433) [haskellPackages.poker](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.poker) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152315755) [[:apple::x:]](https://hydra.nixos.org/build/152315613) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152320749) [haskellPackages.posix-socket](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.posix-socket) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152318645) [[:apple::x:]](https://hydra.nixos.org/build/152314187) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318762) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.posix-timer) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152322336) [[:apple::x:]](https://hydra.nixos.org/build/152316800) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152319899) [haskellPackages.pthread](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.pthread) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152323662) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152320310) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152323882) [haskellPackages.ptr-poker](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.ptr-poker) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152321534) [[:apple::x:]](https://hydra.nixos.org/build/152319240) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152321059) [haskellPackages.sandwich-webdriver](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sandwich-webdriver) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151733838) [[:apple::x:]](https://hydra.nixos.org/build/151720401) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151727935) [haskellPackages.sdp](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151716733) [[:apple::x:]](https://hydra.nixos.org/build/151724083) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151731829) [haskellPackages.select](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.select) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152316003) [[:apple::x:]](https://hydra.nixos.org/build/152324933) [[:penguin::x:]](https://hydra.nixos.org/build/152322512) [haskellPackages.servant-benchmark](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.servant-benchmark) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151722023) [[:apple::x:]](https://hydra.nixos.org/build/151725640) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151721209) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.shared-memory) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151724291) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151730287) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151725543) [haskellPackages.stm-queue](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.stm-queue) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151718182) [[:apple::x:]](https://hydra.nixos.org/build/151734484) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151722691) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sysinfo) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152323915) [[:apple::x:]](https://hydra.nixos.org/build/152319234) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152317650) [haskellPackages.tailfile-hinotify](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.tailfile-hinotify) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152317732) [[:apple::x:]](https://hydra.nixos.org/build/152319702) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315331) [haskellPackages.thyme](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.thyme) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152315339) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152322930) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152320887) [haskellPackages.type-natural](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.type-natural) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152317511) [[:apple::x:]](https://hydra.nixos.org/build/152322959) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152320948) [haskellPackages.tz](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.tz) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151726243) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151732370) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151715865) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.unicode-properties) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/151730218) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151734842) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151725675) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151728215) [[:apple::x:]](https://hydra.nixos.org/build/151728055) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151718500) [tests.haskell.writers](https://hydra.nixos.org/eval/1702901?filter=tests.haskell.writers) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/152323598) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152318668) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152323052) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.x86-64bit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151726806) [[:apple::x:]](https://hydra.nixos.org/build/151718927) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151717638) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.xmonad-utils) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151723111) [[:apple::x:]](https://hydra.nixos.org/build/151731162) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151734781) [haskellPackages.yoga](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.yoga) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152315400) [[:apple::x:]](https://hydra.nixos.org/build/152316866) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152319902) [haskellPackages.zip](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.zip) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151725271) [[:apple::x:]](https://hydra.nixos.org/build/151727468) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151723906) [haskellPackages.zot](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.zot) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151731820) [[:apple::x:]](https://hydra.nixos.org/build/151720934) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151731961) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>45 job(s) </summary>

- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152319718) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152322765) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152313831) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.PrimitiveArray) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152323555) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152317000) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314720) [haskellPackages.antiope-es](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.antiope-es) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152324611) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152320103) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152321624) [haskellPackages.di](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.di) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152320118) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152321828) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152321192) [haskellPackages.di-df1](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.di-df1) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151976403) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151969531) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151975800) [haskellPackages.di-handle](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.di-handle) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151976595) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151974573) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151969665) [haskellPackages.di-monad](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.di-monad) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151716478) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151719950) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151728138) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152323493) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152318931) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152323449) [haskellPackages.exinst-aeson](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.exinst-aeson) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152323392) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152317514) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152316670) [haskellPackages.exinst-bytes](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.exinst-bytes) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152322857) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152319567) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318424) [haskellPackages.exinst-cereal](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.exinst-cereal) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152321838) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152318641) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315257) [haskellPackages.exinst-serialise](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.exinst-serialise) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152316095) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152319644) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152323907) [haskellPackages.fastparser](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.fastparser) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152322429) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152317636) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152320886) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152313822) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152322176) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314608) [haskellPackages.jsonifier](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.jsonifier) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152320094) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152316628) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314231) [haskellPackages.keenser](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.keenser) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152321065) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152316703) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152320459) [haskellPackages.moto](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.moto) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152322474) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152318285) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315121) [haskellPackages.nri-env-parser](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nri-env-parser) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152314776) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152321336) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315170) [haskellPackages.nri-http](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nri-http) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152314566) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152324488) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314486) [haskellPackages.nri-observability](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nri-observability) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152320007) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152322402) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152320795) [haskellPackages.nri-redis](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nri-redis) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152317011) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152323897) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152317728) [haskellPackages.nri-test-encoding](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.nri-test-encoding) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152321902) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152322110) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152313976) [haskellPackages.opencv-extra](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.opencv-extra) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152313984) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152316943) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315023) [haskellPackages.opentelemetry-extra](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.opentelemetry-extra) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152316356) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152314501) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152316004) [haskellPackages.opentelemetry-lightstep](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.opentelemetry-lightstep) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152322981) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152315296) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315753) [haskellPackages.orgmode-parse](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.orgmode-parse) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152316098) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152314097) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152324246) [haskellPackages.orgstat](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.orgstat) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152320133) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152322918) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152318909) [haskellPackages.postgresql-replicant](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.postgresql-replicant) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151734558) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151724149) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151716937) [haskellPackages.rounded](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.rounded) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152314887) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152314612) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314830) [haskellPackages.scan-metadata](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.scan-metadata) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151727772) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151721656) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151728845) [haskellPackages.sdp-binary](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp-binary) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151728702) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151730103) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151723086) [haskellPackages.sdp-deepseq](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp-deepseq) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151735154) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151716421) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151716900) [haskellPackages.sdp-hashable](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp-hashable) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151733600) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151722095) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151728973) [haskellPackages.sdp-io](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp-io) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151717062) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151731094) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151728805) [haskellPackages.sdp-quickcheck](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp-quickcheck) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152323154) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152322640) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315691) [haskellPackages.sdp4bytestring](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp4bytestring) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152316869) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152320367) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152319801) [haskellPackages.sdp4text](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp4text) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151974457) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151977670) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151970337) [haskellPackages.sdp4unordered](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp4unordered) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152317073) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152321726) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152316617) [haskellPackages.sdp4vector](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sdp4vector) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152319278) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/152323419) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152314422) [haskellPackages.sized](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.sized) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151724163) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151719049) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151732738) [haskellPackages.stm-actor](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.stm-actor) 
- [ ] [taskell](https://hydra.nixos.org/eval/1702901?filter=taskell) 
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152317998) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152316135) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152322551) [toplevel](https://hydra.nixos.org/eval/1702901?filter=taskell)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/152315676) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/152323229) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/152315256) [haskellPackages](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.taskell)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151730687) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/151734719) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151734090) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.unicode-names) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/151725525) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/151728544) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/151728445) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1702901?filter=haskellPackages.xbattbar) 
</details>

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
