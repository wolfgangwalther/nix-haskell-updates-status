### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1805953](https://hydra.nixos.org/eval/1805953) of nixpkgs commit [c93aff1](https://github.com/NixOS/nixpkgs/commits/c93aff17d599feb24ca6a0e2156afd3b184a7afb) as of 2024-04-27 18:25 UTC*

🔴 **Branch not mergeable**
  * No `maintained` job found.
  * `mergeable` jobset failed.
  * Too many outstanding jobs on x86_64-linux.

#### Build summary

 | Platform | Failed ❌ | DependencyFailed ❗ | Unfinished ⏳ | Success ✅ | 
 | --- | --- | --- | --- | --- | 
 | [aarch64-darwin 🍏](https://hydra.nixos.org/eval/1805953?filter=.aarch64-darwin) | 5 | 32 | 4916 | 1415 | 
 | [aarch64-linux 📱](https://hydra.nixos.org/eval/1805953?filter=.aarch64-linux) | 19 | 17 | 2 | 6380 | 
 | [x86_64-darwin 🍎](https://hydra.nixos.org/eval/1805953?filter=.x86_64-darwin) | 2 | 5 | 5710 | 650 | 
 | [x86_64-linux 🐧](https://hydra.nixos.org/eval/1805953?filter=.x86_64-linux) | 1 | 4 | 5779 | 693 | 
#### Maintained Linux packages with build failure
- [ ] [hledger-ui](https://hydra.nixos.org/eval/1805953?filter=hledger-ui) @maralorn
  - [[📱❌]](https://hydra.nixos.org/build/257708459) [[🐧⏳]](https://hydra.nixos.org/build/257713465) [toplevel](https://hydra.nixos.org/eval/1805953?filter=hledger-ui)
  - [[📱❌]](https://hydra.nixos.org/build/257716869) [[🐧⏳]](https://hydra.nixos.org/build/257701719) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hledger-ui)
#### Maintained Linux packages with failed dependency
- [ ] [cabal2nix](https://hydra.nixos.org/eval/1805953?filter=cabal2nix) @sternenseemann
  - [[📱✅]](https://hydra.nixos.org/build/257701332) [[🐧⏳]](https://hydra.nixos.org/build/257722935) [toplevel](https://hydra.nixos.org/eval/1805953?filter=cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257686981) [[🐧⏳]](https://hydra.nixos.org/build/257691936) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257693996) [[🐧⏳]](https://hydra.nixos.org/build/257685303) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257680746) [[🐧⏳]](https://hydra.nixos.org/build/257674680) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257677894) [[🐧⏳]](https://hydra.nixos.org/build/257696779) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257676134) [[🐧⏳]](https://hydra.nixos.org/build/257689788) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257692868) [[🐧⏳]](https://hydra.nixos.org/build/257694246) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257679511) [[🐧⏳]](https://hydra.nixos.org/build/257676906) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257684297) [[🐧⏳]](https://hydra.nixos.org/build/257683176) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.cabal2nix)
  - [[📱❗]](https://hydra.nixos.org/build/257696721) [[🐧⏳]](https://hydra.nixos.org/build/257686862) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257697714) [[🐧⏳]](https://hydra.nixos.org/build/257678387) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.cabal2nix)
  - [[📱❗]](https://hydra.nixos.org/build/257708008) [[🐧⏳]](https://hydra.nixos.org/build/257702021) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257725396) [[🐧⏳]](https://hydra.nixos.org/build/257710069) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257706450) [[🐧⏳]](https://hydra.nixos.org/build/257720506) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.cabal2nix)
  - [[📱✅]](https://hydra.nixos.org/build/257714081) [[🐧⏳]](https://hydra.nixos.org/build/257712436) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.cabal2nix)
  -  [[🐧✅]](https://hydra.nixos.org/build/257695293) [pkgsStatic.haskell.packages.native-bignum.ghc948](https://hydra.nixos.org/eval/1805953?filter=pkgsStatic.haskell.packages.native-bignum.ghc948.cabal2nix)
  -  [[🐧✅]](https://hydra.nixos.org/build/257674725) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1805953?filter=pkgsStatic.haskellPackages.cabal2nix)
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1805953?filter=haskell-language-server) @maralorn
  - [[📱❗]](https://hydra.nixos.org/build/257724186) [[🐧⏳]](https://hydra.nixos.org/build/257726470) [toplevel](https://hydra.nixos.org/eval/1805953?filter=haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257678526) [[🐧❗]](https://hydra.nixos.org/build/257675826) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257696323) [[🐧❗]](https://hydra.nixos.org/build/257692222) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257697444) [[🐧⏳]](https://hydra.nixos.org/build/257694883) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257698262) [[🐧⏳]](https://hydra.nixos.org/build/257696874) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257690210) [[🐧⏳]](https://hydra.nixos.org/build/257698188) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257676313) [[🐧❗]](https://hydra.nixos.org/build/257685068) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257699145) [[🐧⏳]](https://hydra.nixos.org/build/257697169) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257695323) [[🐧❗]](https://hydra.nixos.org/build/257684309) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257704018) [[🐧⏳]](https://hydra.nixos.org/build/257711274) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257724095) [[🐧⏳]](https://hydra.nixos.org/build/257702852) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257701933) [[🐧⏳]](https://hydra.nixos.org/build/257702428) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257717292) [[🐧⏳]](https://hydra.nixos.org/build/257703126) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc981.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257711575) [[🐧⏳]](https://hydra.nixos.org/build/257720363) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc982.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/257723316) [[🐧⏳]](https://hydra.nixos.org/build/257702191) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.haskell-language-server)
- [ ] [hlint](https://hydra.nixos.org/eval/1805953?filter=hlint) @maralorn
  - [[📱✅]](https://hydra.nixos.org/build/257706576) [[🐧⏳]](https://hydra.nixos.org/build/257705850) [toplevel](https://hydra.nixos.org/eval/1805953?filter=hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257692789) [[🐧✅]](https://hydra.nixos.org/build/257680549) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257677955) [[🐧✅]](https://hydra.nixos.org/build/257675764) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257694310) [[🐧✅]](https://hydra.nixos.org/build/257686006) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257698708) [[🐧✅]](https://hydra.nixos.org/build/257688655) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257696414) [[🐧✅]](https://hydra.nixos.org/build/257674997) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257676781) [[🐧✅]](https://hydra.nixos.org/build/257692519) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.hlint)
  - [[📱❗]](https://hydra.nixos.org/build/257675951) [[🐧✅]](https://hydra.nixos.org/build/257685095) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257694677) [[🐧✅]](https://hydra.nixos.org/build/257676366) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257720208) [[🐧⏳]](https://hydra.nixos.org/build/257708735) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257719660) [[🐧⏳]](https://hydra.nixos.org/build/257722798) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257725244) [[🐧⏳]](https://hydra.nixos.org/build/257725369) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/257720967) [[🐧⏳]](https://hydra.nixos.org/build/257717144) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hlint)
- [ ] [language-nix](https://hydra.nixos.org/eval/1805953?filter=language-nix) @sternenseemann
  - [[📱✅]](https://hydra.nixos.org/build/257683627) [[🐧✅]](https://hydra.nixos.org/build/257686016) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257685571) [[🐧✅]](https://hydra.nixos.org/build/257697398) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257692457) [[🐧✅]](https://hydra.nixos.org/build/257689991) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257678266) [[🐧✅]](https://hydra.nixos.org/build/257676763) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257678626) [[🐧✅]](https://hydra.nixos.org/build/257690705) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257679444) [[🐧✅]](https://hydra.nixos.org/build/257682081) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257700507) [[🐧✅]](https://hydra.nixos.org/build/257684261) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257682588) [[🐧✅]](https://hydra.nixos.org/build/257683896) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.language-nix)
  - [[📱❗]](https://hydra.nixos.org/build/257674510) [[🐧✅]](https://hydra.nixos.org/build/257690694) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257695615) [[🐧✅]](https://hydra.nixos.org/build/257695353) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.language-nix)
  - [[📱❗]](https://hydra.nixos.org/build/257713439) [[🐧⏳]](https://hydra.nixos.org/build/257709170) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257721933) [[🐧⏳]](https://hydra.nixos.org/build/257714022) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257712265) [[🐧⏳]](https://hydra.nixos.org/build/257711704) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.language-nix)
  - [[📱✅]](https://hydra.nixos.org/build/257726142) [[🐧⏳]](https://hydra.nixos.org/build/257721020) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.language-nix)
- [ ] [[🐧❗]](https://hydra.nixos.org/build/257701523) [mergeable](https://hydra.nixos.org/eval/1805953?filter=mergeable) @cdepillabout @expipiplus1 @maralorn @ncfavier @sternenseemann
- [ ] [weeder](https://hydra.nixos.org/eval/1805953?filter=weeder) @maralorn
  - [[📱✅]](https://hydra.nixos.org/build/257697199) [[🐧⏳]](https://hydra.nixos.org/build/257675117) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257684634) [[🐧⏳]](https://hydra.nixos.org/build/257680542) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257693489) [[🐧⏳]](https://hydra.nixos.org/build/257697616) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257688264) [[🐧⏳]](https://hydra.nixos.org/build/257694917) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257694682) [[🐧⏳]](https://hydra.nixos.org/build/257700300) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257692360) [[🐧⏳]](https://hydra.nixos.org/build/257678186) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257690883) [[🐧⏳]](https://hydra.nixos.org/build/257677093) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257680184) [[🐧⏳]](https://hydra.nixos.org/build/257690361) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.weeder)
  - [[📱❗]](https://hydra.nixos.org/build/257698116) [[🐧⏳]](https://hydra.nixos.org/build/257684836) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257699582) [[🐧⏳]](https://hydra.nixos.org/build/257690345) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.weeder)
  - [[📱❗]](https://hydra.nixos.org/build/257704621) [[🐧⏳]](https://hydra.nixos.org/build/257705261) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257725767) [[🐧⏳]](https://hydra.nixos.org/build/257716915) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257707171) [[🐧⏳]](https://hydra.nixos.org/build/257726537) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/257701397) [[🐧⏳]](https://hydra.nixos.org/build/257715186) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.weeder)
#### Maintained Darwin packages with failed dependency
<details><summary>95 job(s) </summary>

- [ ] [cabal-install](https://hydra.nixos.org/eval/1805953?filter=cabal-install) @sternenseemann
  - [[🍏⏳]](https://hydra.nixos.org/build/257720210) [[🍎⏳]](https://hydra.nixos.org/build/257717742) [toplevel](https://hydra.nixos.org/eval/1805953?filter=cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257691451) [[🍎⏳]](https://hydra.nixos.org/build/257684362) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257675426) [[🍎⏳]](https://hydra.nixos.org/build/257676426) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257684471) [[🍎⏳]](https://hydra.nixos.org/build/257692075) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257682836) [[🍎⏳]](https://hydra.nixos.org/build/257691745) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257682281) [[🍎⏳]](https://hydra.nixos.org/build/257682673) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257699760) [[🍎⏳]](https://hydra.nixos.org/build/257689401) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.cabal-install)
  - [[🍏❗]](https://hydra.nixos.org/build/257693610) [[🍎⏳]](https://hydra.nixos.org/build/257700545) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257677983) [[🍎⏳]](https://hydra.nixos.org/build/257680701) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257676296) [[🍎⏳]](https://hydra.nixos.org/build/257675899) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257684861) [[🍎⏳]](https://hydra.nixos.org/build/257686968) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257701805) [[🍎⏳]](https://hydra.nixos.org/build/257714438) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257705368) [[🍎⏳]](https://hydra.nixos.org/build/257709458) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257707474) [[🍎⏳]](https://hydra.nixos.org/build/257717740) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.cabal-install)
  - [[🍏⏳]](https://hydra.nixos.org/build/257709419) [[🍎⏳]](https://hydra.nixos.org/build/257716870) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.cabal-install)
- [ ] [cabal2nix](https://hydra.nixos.org/eval/1805953?filter=cabal2nix) @sternenseemann
  - [[🍏⏳]](https://hydra.nixos.org/build/257725331) [[🍎⏳]](https://hydra.nixos.org/build/257706628) [toplevel](https://hydra.nixos.org/eval/1805953?filter=cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257686926) [[🍎⏳]](https://hydra.nixos.org/build/257697665) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.cabal2nix)
  - [[🍏❗]](https://hydra.nixos.org/build/257694127) [[🍎⏳]](https://hydra.nixos.org/build/257674981) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257675572) [[🍎⏳]](https://hydra.nixos.org/build/257687759) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257695604) [[🍎⏳]](https://hydra.nixos.org/build/257699405) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257695911) [[🍎⏳]](https://hydra.nixos.org/build/257700606) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257700122) [[🍎⏳]](https://hydra.nixos.org/build/257690675) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.cabal2nix)
  - [[🍏❗]](https://hydra.nixos.org/build/257694174) [[🍎⏳]](https://hydra.nixos.org/build/257687376) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257694961) [[🍎⏳]](https://hydra.nixos.org/build/257693501) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257677575) [[🍎⏳]](https://hydra.nixos.org/build/257695783) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257685675) [[🍎⏳]](https://hydra.nixos.org/build/257681811) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257713427) [[🍎⏳]](https://hydra.nixos.org/build/257719873) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257723247) [[🍎⏳]](https://hydra.nixos.org/build/257723930) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257718180) [[🍎⏳]](https://hydra.nixos.org/build/257702378) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.cabal2nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257704007) [[🍎⏳]](https://hydra.nixos.org/build/257715822) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.cabal2nix)
- [ ] [ghcHEAD](https://hydra.nixos.org/eval/1805953?filter=ghcHEAD) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏❗]](https://hydra.nixos.org/build/257715042) [[🍎⏳]](https://hydra.nixos.org/build/257716061) [haskell.compiler](https://hydra.nixos.org/eval/1805953?filter=haskell.compiler.ghcHEAD)
  - [[🍏❗]](https://hydra.nixos.org/build/257719092) [[🍎⏳]](https://hydra.nixos.org/build/257725993) [haskell.compiler.native-bignum](https://hydra.nixos.org/eval/1805953?filter=haskell.compiler.native-bignum.ghcHEAD)
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1805953?filter=haskell-language-server) @maralorn
  - [[🍏⏳]](https://hydra.nixos.org/build/257720430) [[🍎⏳]](https://hydra.nixos.org/build/257716747) [toplevel](https://hydra.nixos.org/eval/1805953?filter=haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257694864) [[🍎⏳]](https://hydra.nixos.org/build/257699424) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257695120) [[🍎⏳]](https://hydra.nixos.org/build/257700369) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257691083) [[🍎⏳]](https://hydra.nixos.org/build/257688719) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257700523) [[🍎⏳]](https://hydra.nixos.org/build/257690153) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.haskell-language-server)
  - [[🍏❗]](https://hydra.nixos.org/build/257700316) [[🍎⏳]](https://hydra.nixos.org/build/257692071) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257697159) [[🍎⏳]](https://hydra.nixos.org/build/257696108) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257697167) [[🍎⏳]](https://hydra.nixos.org/build/257674628) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257700271) [[🍎⏳]](https://hydra.nixos.org/build/257686369) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257714842) [[🍎⏳]](https://hydra.nixos.org/build/257726109) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257712677) [[🍎⏳]](https://hydra.nixos.org/build/257705257) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257712031) [[🍎⏳]](https://hydra.nixos.org/build/257722240) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257710106) [[🍎⏳]](https://hydra.nixos.org/build/257714216) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc981.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257722417) [[🍎⏳]](https://hydra.nixos.org/build/257719843) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc982.haskell-language-server)
  - [[🍏⏳]](https://hydra.nixos.org/build/257705163) [[🍎⏳]](https://hydra.nixos.org/build/257719908) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.haskell-language-server)
- [ ] [hlint](https://hydra.nixos.org/eval/1805953?filter=hlint) @maralorn
  - [[🍏⏳]](https://hydra.nixos.org/build/257724829) [[🍎⏳]](https://hydra.nixos.org/build/257721767) [toplevel](https://hydra.nixos.org/eval/1805953?filter=hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257684099) [[🍎⏳]](https://hydra.nixos.org/build/257697652) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257675903) [[🍎⏳]](https://hydra.nixos.org/build/257681609) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257684524) [[🍎⏳]](https://hydra.nixos.org/build/257690431) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257698669) [[🍎⏳]](https://hydra.nixos.org/build/257680241) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.hlint)
  - [[🍏❗]](https://hydra.nixos.org/build/257694730) [[🍎⏳]](https://hydra.nixos.org/build/257679996) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257674883) [[🍎⏳]](https://hydra.nixos.org/build/257687819) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257698339) [[🍎⏳]](https://hydra.nixos.org/build/257699973) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257693743) [[🍎⏳]](https://hydra.nixos.org/build/257674250) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257706001) [[🍎⏳]](https://hydra.nixos.org/build/257724358) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257723086) [[🍎⏳]](https://hydra.nixos.org/build/257710669) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257716803) [[🍎⏳]](https://hydra.nixos.org/build/257714718) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.hlint)
  - [[🍏⏳]](https://hydra.nixos.org/build/257721275) [[🍎⏳]](https://hydra.nixos.org/build/257726576) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hlint)
- [ ] [language-nix](https://hydra.nixos.org/eval/1805953?filter=language-nix) @sternenseemann
  - [[🍏⏳]](https://hydra.nixos.org/build/257695222) [[🍎⏳]](https://hydra.nixos.org/build/257689904) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.language-nix)
  - [[🍏✅]](https://hydra.nixos.org/build/257675162) [[🍎✅]](https://hydra.nixos.org/build/257695928) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.language-nix)
  - [[🍏✅]](https://hydra.nixos.org/build/257696897) [[🍎⏳]](https://hydra.nixos.org/build/257678817) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.language-nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257699944) [[🍎⏳]](https://hydra.nixos.org/build/257689829) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.language-nix)
  - [[🍏✅]](https://hydra.nixos.org/build/257674738) [[🍎⏳]](https://hydra.nixos.org/build/257686233) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.language-nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257676843) [[🍎⏳]](https://hydra.nixos.org/build/257693336) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.language-nix)
  - [[🍏❗]](https://hydra.nixos.org/build/257685832) [[🍎✅]](https://hydra.nixos.org/build/257678209) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.language-nix)
  - [[🍏✅]](https://hydra.nixos.org/build/257698113) [[🍎⏳]](https://hydra.nixos.org/build/257684125) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.language-nix)
  - [[🍏✅]](https://hydra.nixos.org/build/257683115) [[🍎✅]](https://hydra.nixos.org/build/257696968) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.language-nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257687828) [[🍎✅]](https://hydra.nixos.org/build/257690577) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.language-nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257722673) [[🍎⏳]](https://hydra.nixos.org/build/257722886) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.language-nix)
  - [[🍏⏳]](https://hydra.nixos.org/build/257701579) [[🍎⏳]](https://hydra.nixos.org/build/257722783) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.language-nix)
  - [[🍏✅]](https://hydra.nixos.org/build/257707772) [[🍎⏳]](https://hydra.nixos.org/build/257706575) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.language-nix)
  - [[🍏✅]](https://hydra.nixos.org/build/257724593) [[🍎⏳]](https://hydra.nixos.org/build/257721111) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.language-nix)
- [ ] [weeder](https://hydra.nixos.org/eval/1805953?filter=weeder) @maralorn
  - [[🍏⏳]](https://hydra.nixos.org/build/257689329) [[🍎⏳]](https://hydra.nixos.org/build/257694439) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.weeder)
  - [[🍏❗]](https://hydra.nixos.org/build/257690485) [[🍎⏳]](https://hydra.nixos.org/build/257685577) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257698887) [[🍎⏳]](https://hydra.nixos.org/build/257678958) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257699369) [[🍎⏳]](https://hydra.nixos.org/build/257681458) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257683477) [[🍎⏳]](https://hydra.nixos.org/build/257681316) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257682044) [[🍎⏳]](https://hydra.nixos.org/build/257676659) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.weeder)
  - [[🍏❗]](https://hydra.nixos.org/build/257691799) [[🍎⏳]](https://hydra.nixos.org/build/257699429) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257674995) [[🍎⏳]](https://hydra.nixos.org/build/257696693) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257675922) [[🍎⏳]](https://hydra.nixos.org/build/257699810) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257683673) [[🍎⏳]](https://hydra.nixos.org/build/257689460) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257718132) [[🍎⏳]](https://hydra.nixos.org/build/257711736) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257721371) [[🍎⏳]](https://hydra.nixos.org/build/257723894) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257726549) [[🍎⏳]](https://hydra.nixos.org/build/257715558) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.weeder)
  - [[🍏⏳]](https://hydra.nixos.org/build/257704236) [[🍎⏳]](https://hydra.nixos.org/build/257708809) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.weeder)
</details>

#### Unmaintained packages with build failure
<details><summary>36 job(s) </summary>

- [ ] [ghc-lib-parser](https://hydra.nixos.org/eval/1805953?filter=ghc-lib-parser)  ⤴️ 19 | 67
  - [[🍏✅]](https://hydra.nixos.org/build/257100356) [[📱✅]](https://hydra.nixos.org/build/257091635) [[🍎✅]](https://hydra.nixos.org/build/257099548) [[🐧✅]](https://hydra.nixos.org/build/257101525) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.ghc-lib-parser)
  - [[🍏❌]](https://hydra.nixos.org/build/257100150) [[📱❌]](https://hydra.nixos.org/build/257079645) [[🍎❌]](https://hydra.nixos.org/build/257084410) [[🐧❌]](https://hydra.nixos.org/build/257080714) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257076582) [[📱✅]](https://hydra.nixos.org/build/257081669) [[🍎✅]](https://hydra.nixos.org/build/257084474) [[🐧✅]](https://hydra.nixos.org/build/257095284) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257089134) [[📱✅]](https://hydra.nixos.org/build/257095691) [[🍎✅]](https://hydra.nixos.org/build/257097972) [[🐧✅]](https://hydra.nixos.org/build/257091373) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257099472) [[📱✅]](https://hydra.nixos.org/build/257088147) [[🍎✅]](https://hydra.nixos.org/build/257083792) [[🐧✅]](https://hydra.nixos.org/build/257090242) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257102035) [[📱✅]](https://hydra.nixos.org/build/257077415) [[🍎✅]](https://hydra.nixos.org/build/257085168) [[🐧✅]](https://hydra.nixos.org/build/257099261) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257092458) [[📱✅]](https://hydra.nixos.org/build/257089528) [[🍎✅]](https://hydra.nixos.org/build/257100081) [[🐧✅]](https://hydra.nixos.org/build/257080842) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257085918) [[📱✅]](https://hydra.nixos.org/build/257090265) [[🍎✅]](https://hydra.nixos.org/build/257086550) [[🐧✅]](https://hydra.nixos.org/build/257099733) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257090195) [[📱✅]](https://hydra.nixos.org/build/257085282) [[🍎✅]](https://hydra.nixos.org/build/257085103) [[🐧✅]](https://hydra.nixos.org/build/257096062) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257101849) [[📱✅]](https://hydra.nixos.org/build/257100215) [[🍎✅]](https://hydra.nixos.org/build/257091340) [[🐧✅]](https://hydra.nixos.org/build/257087968) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257723764) [[📱✅]](https://hydra.nixos.org/build/257717116) [[🍎✅]](https://hydra.nixos.org/build/257709915) [[🐧✅]](https://hydra.nixos.org/build/257721945) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257722876) [[📱✅]](https://hydra.nixos.org/build/257717666) [[🍎✅]](https://hydra.nixos.org/build/257705841) [[🐧✅]](https://hydra.nixos.org/build/257717903) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257704421) [[📱✅]](https://hydra.nixos.org/build/257702636) [[🍎✅]](https://hydra.nixos.org/build/257710491) [[🐧✅]](https://hydra.nixos.org/build/257717364) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.ghc-lib-parser)
  - [[🍏✅]](https://hydra.nixos.org/build/257726431) [[📱✅]](https://hydra.nixos.org/build/257711959) [[🍎✅]](https://hydra.nixos.org/build/257718592) [[🐧✅]](https://hydra.nixos.org/build/257702010) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.ghc-lib-parser)
- [ ] [[🍏❌]](https://hydra.nixos.org/build/257726012) [[📱✅]](https://hydra.nixos.org/build/257717969) [[🍎⏳]](https://hydra.nixos.org/build/257702256) [[🐧⏳]](https://hydra.nixos.org/build/257708374) [haskellPackages.fmt](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.fmt)  ⤴️ 7 | 26
- [ ] [[🍏❌]](https://hydra.nixos.org/build/257717647) [[📱✅]](https://hydra.nixos.org/build/257726691) [[🍎⏳]](https://hydra.nixos.org/build/257726553) [[🐧⏳]](https://hydra.nixos.org/build/257715037) [haskellPackages.di-core](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.di-core)  ⤴️ 6 | 12
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257714667) [[📱❌]](https://hydra.nixos.org/build/257724456) [[🍎⏳]](https://hydra.nixos.org/build/257713376) [[🐧⏳]](https://hydra.nixos.org/build/257701808) [haskellPackages.ghcide](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.ghcide)  ⤴️ 3 | 35
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257723597) [[📱❌]](https://hydra.nixos.org/build/257708286) [[🍎⏳]](https://hydra.nixos.org/build/257718153) [[🐧⏳]](https://hydra.nixos.org/build/257711969) [haskellPackages.prodapi](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.prodapi)  ⤴️ 2 | 2
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257707937) [[📱❌]](https://hydra.nixos.org/build/257717916) [[🍎⏳]](https://hydra.nixos.org/build/257703039) [[🐧⏳]](https://hydra.nixos.org/build/257721729) [haskellPackages.errata](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.errata)  ⤴️ 1 | 3
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257723057) [[📱❌]](https://hydra.nixos.org/build/257725625) [[🍎⏳]](https://hydra.nixos.org/build/257711900) [[🐧⏳]](https://hydra.nixos.org/build/257725773) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.nlopt-haskell)  ⤴️ 1 | 1
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257719827) [[📱❌]](https://hydra.nixos.org/build/257709169) [[🍎⏳]](https://hydra.nixos.org/build/257713900) [[🐧⏳]](https://hydra.nixos.org/build/257719621) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.freetype2)  ⤴️ 0 | 12
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257703866) [[📱❌]](https://hydra.nixos.org/build/257718907) [[🍎⏳]](https://hydra.nixos.org/build/257704209) [[🐧⏳]](https://hydra.nixos.org/build/257718160) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hw-simd)  ⤴️ 0 | 9
- [ ] [[🍏❌]](https://hydra.nixos.org/build/257701732) [[📱✅]](https://hydra.nixos.org/build/257711003) [[🍎❌]](https://hydra.nixos.org/build/257704758) [[🐧✅]](https://hydra.nixos.org/build/257701648) [haskellPackages.rawfilepath](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.rawfilepath)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/257719164) [[📱✅]](https://hydra.nixos.org/build/257715518) [[🍎⏳]](https://hydra.nixos.org/build/257700950) [[🐧⏳]](https://hydra.nixos.org/build/257725678) [haskellPackages.select](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.select)  ⤴️ 0 | 1
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257726152) [[📱❌]](https://hydra.nixos.org/build/257713790) [[🍎⏳]](https://hydra.nixos.org/build/257723047) [[🐧⏳]](https://hydra.nixos.org/build/257702289) [haskellPackages.simple-vec3](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.simple-vec3)  ⤴️ 0 | 1
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257723372) [[📱❌]](https://hydra.nixos.org/build/257705006) [[🍎⏳]](https://hydra.nixos.org/build/257717522) [[🐧⏳]](https://hydra.nixos.org/build/257725716) [haskellPackages.GOST34112012-Hash](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.GOST34112012-Hash) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257725882) [[📱❌]](https://hydra.nixos.org/build/257726170) [[🍎⏳]](https://hydra.nixos.org/build/257718133) [[🐧⏳]](https://hydra.nixos.org/build/257719347) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.HsASA) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257726284) [[📱❌]](https://hydra.nixos.org/build/257726624) [[🍎⏳]](https://hydra.nixos.org/build/257711938) [[🐧⏳]](https://hydra.nixos.org/build/257724584) [haskellPackages.acme-not-a-joke](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.acme-not-a-joke) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257710385) [[📱❌]](https://hydra.nixos.org/build/257706304) [[🍎⏳]](https://hydra.nixos.org/build/257707075) [[🐧⏳]](https://hydra.nixos.org/build/257715854) [haskellPackages.changelog-d](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.changelog-d) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257720380) [[📱❌]](https://hydra.nixos.org/build/257709992) [[🍎⏳]](https://hydra.nixos.org/build/257720544) [[🐧⏳]](https://hydra.nixos.org/build/257714608) [haskellPackages.cornelis](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.cornelis) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257711740) [[📱❌]](https://hydra.nixos.org/build/257723034) [[🍎⏳]](https://hydra.nixos.org/build/257701682) [[🐧⏳]](https://hydra.nixos.org/build/257712398) [haskellPackages.diohsc](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.diohsc) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257722769) [[📱❌]](https://hydra.nixos.org/build/257712169) [[🍎⏳]](https://hydra.nixos.org/build/257720819) [[🐧⏳]](https://hydra.nixos.org/build/257705832) [haskellPackages.opaleye-textsearch](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.opaleye-textsearch) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257714401) [[📱❌]](https://hydra.nixos.org/build/257713096) [[🍎⏳]](https://hydra.nixos.org/build/257717813) [[🐧⏳]](https://hydra.nixos.org/build/257722899) [haskellPackages.significant-figures](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.significant-figures) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257711622) [[📱❌]](https://hydra.nixos.org/build/257704366) [[🍎⏳]](https://hydra.nixos.org/build/257702475) [[🐧⏳]](https://hydra.nixos.org/build/257725995) [haskellPackages.simdutf](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.simdutf) 
- [ ] [[📱❌]](https://hydra.nixos.org/build/257721083) [[🐧⏳]](https://hydra.nixos.org/build/257720915) [haskellPackages.tasty-papi](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.tasty-papi) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>115 job(s) </summary>

- [ ] [microlens](https://hydra.nixos.org/eval/1805953?filter=microlens)  ⤴️ 142 | 586
  - [[🍏✅]](https://hydra.nixos.org/build/257711902) [[📱✅]](https://hydra.nixos.org/build/257702297) [[🍎✅]](https://hydra.nixos.org/build/257700789) [[🐧✅]](https://hydra.nixos.org/build/257703347) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.microlens)
  - [[🍏⏳]](https://hydra.nixos.org/build/257712385)  [[🍎⏳]](https://hydra.nixos.org/build/257705324) [[🐧⏳]](https://hydra.nixos.org/build/257716864) [pkgsCross.ghcjs.haskell.packages.ghc98](https://hydra.nixos.org/eval/1805953?filter=pkgsCross.ghcjs.haskell.packages.ghc98.microlens)
  - [[🍏❗]](https://hydra.nixos.org/build/257723730)  [[🍎⏳]](https://hydra.nixos.org/build/257723923) [[🐧⏳]](https://hydra.nixos.org/build/257703170) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1805953?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.microlens)
  - [[🍏⏳]](https://hydra.nixos.org/build/257719208)  [[🍎⏳]](https://hydra.nixos.org/build/257719498) [[🐧⏳]](https://hydra.nixos.org/build/257708169) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1805953?filter=pkgsCross.ghcjs.haskellPackages.microlens)
- [ ] [ghc-lib-parser-ex](https://hydra.nixos.org/eval/1805953?filter=ghc-lib-parser-ex)  ⤴️ 13 | 44
  - [[🍏⏳]](https://hydra.nixos.org/build/257698048) [[📱✅]](https://hydra.nixos.org/build/257674810) [[🍎⏳]](https://hydra.nixos.org/build/257675885) [[🐧⏳]](https://hydra.nixos.org/build/257681357) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.ghc-lib-parser-ex)
  - [[🍏❗]](https://hydra.nixos.org/build/257682313) [[📱❗]](https://hydra.nixos.org/build/257688333) [[🍎❗]](https://hydra.nixos.org/build/257697713) [[🐧❗]](https://hydra.nixos.org/build/257681298) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257693023) [[📱✅]](https://hydra.nixos.org/build/257680581) [[🍎✅]](https://hydra.nixos.org/build/257691909) [[🐧✅]](https://hydra.nixos.org/build/257687872) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257698570) [[📱✅]](https://hydra.nixos.org/build/257699290) [[🍎✅]](https://hydra.nixos.org/build/257680926) [[🐧✅]](https://hydra.nixos.org/build/257675848) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257697471) [[📱✅]](https://hydra.nixos.org/build/257691116) [[🍎✅]](https://hydra.nixos.org/build/257697230) [[🐧✅]](https://hydra.nixos.org/build/257681451) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257675156) [[📱✅]](https://hydra.nixos.org/build/257681321) [[🍎✅]](https://hydra.nixos.org/build/257685332) [[🐧✅]](https://hydra.nixos.org/build/257687396) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.ghc-lib-parser-ex)
  - [[🍏❗]](https://hydra.nixos.org/build/257693451) [[📱✅]](https://hydra.nixos.org/build/257675364) [[🍎✅]](https://hydra.nixos.org/build/257678763) [[🐧✅]](https://hydra.nixos.org/build/257683782) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257695860) [[📱✅]](https://hydra.nixos.org/build/257678079) [[🍎✅]](https://hydra.nixos.org/build/257689279) [[🐧✅]](https://hydra.nixos.org/build/257682626) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257685373) [[📱❗]](https://hydra.nixos.org/build/257691762) [[🍎✅]](https://hydra.nixos.org/build/257691775) [[🐧✅]](https://hydra.nixos.org/build/257685479) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257680878) [[📱✅]](https://hydra.nixos.org/build/257674540) [[🍎✅]](https://hydra.nixos.org/build/257691464) [[🐧✅]](https://hydra.nixos.org/build/257683735) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.ghc-lib-parser-ex)
  - [[🍏⏳]](https://hydra.nixos.org/build/257722926) [[📱✅]](https://hydra.nixos.org/build/257714276) [[🍎⏳]](https://hydra.nixos.org/build/257707521) [[🐧⏳]](https://hydra.nixos.org/build/257713705) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.ghc-lib-parser-ex)
  - [[🍏⏳]](https://hydra.nixos.org/build/257713761) [[📱✅]](https://hydra.nixos.org/build/257704251) [[🍎⏳]](https://hydra.nixos.org/build/257705393) [[🐧⏳]](https://hydra.nixos.org/build/257725300) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257724953) [[📱✅]](https://hydra.nixos.org/build/257704824) [[🍎⏳]](https://hydra.nixos.org/build/257721073) [[🐧⏳]](https://hydra.nixos.org/build/257712418) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.ghc-lib-parser-ex)
  - [[🍏✅]](https://hydra.nixos.org/build/257722953) [[📱✅]](https://hydra.nixos.org/build/257708917) [[🍎⏳]](https://hydra.nixos.org/build/257718331) [[🐧⏳]](https://hydra.nixos.org/build/257719421) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.ghc-lib-parser-ex)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257710585) [[📱✅]](https://hydra.nixos.org/build/257718158) [[🍎⏳]](https://hydra.nixos.org/build/257717790) [[🐧⏳]](https://hydra.nixos.org/build/257710430) [haskellPackages.di-handle](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.di-handle)  ⤴️ 4 | 10
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257719418) [[📱✅]](https://hydra.nixos.org/build/257721312) [[🍎⏳]](https://hydra.nixos.org/build/257702704) [[🐧⏳]](https://hydra.nixos.org/build/257707224) [haskellPackages.di-monad](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.di-monad)  ⤴️ 4 | 10
- [ ] [hpack](https://hydra.nixos.org/eval/1805953?filter=hpack)  ⤴️ 3 | 15
  - [[🍏⏳]](https://hydra.nixos.org/build/257712005) [[📱✅]](https://hydra.nixos.org/build/257718531) [[🍎⏳]](https://hydra.nixos.org/build/257715529) [[🐧⏳]](https://hydra.nixos.org/build/257709613) [toplevel](https://hydra.nixos.org/eval/1805953?filter=hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257685951) [[📱✅]](https://hydra.nixos.org/build/257688574) [[🍎⏳]](https://hydra.nixos.org/build/257699881) [[🐧✅]](https://hydra.nixos.org/build/257681932) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.hpack)
  - [[🍏❗]](https://hydra.nixos.org/build/257692098) [[📱✅]](https://hydra.nixos.org/build/257693689) [[🍎⏳]](https://hydra.nixos.org/build/257687377) [[🐧✅]](https://hydra.nixos.org/build/257698126) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257682395) [[📱✅]](https://hydra.nixos.org/build/257675660) [[🍎⏳]](https://hydra.nixos.org/build/257680990) [[🐧✅]](https://hydra.nixos.org/build/257691679) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257684643) [[📱✅]](https://hydra.nixos.org/build/257700672) [[🍎⏳]](https://hydra.nixos.org/build/257680646) [[🐧✅]](https://hydra.nixos.org/build/257676222) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257690657) [[📱✅]](https://hydra.nixos.org/build/257676012) [[🍎⏳]](https://hydra.nixos.org/build/257682508) [[🐧✅]](https://hydra.nixos.org/build/257694113) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257683483) [[📱✅]](https://hydra.nixos.org/build/257692698) [[🍎⏳]](https://hydra.nixos.org/build/257678191) [[🐧✅]](https://hydra.nixos.org/build/257692220) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.hpack)
  - [[🍏❗]](https://hydra.nixos.org/build/257687487) [[📱✅]](https://hydra.nixos.org/build/257674636) [[🍎⏳]](https://hydra.nixos.org/build/257675677) [[🐧✅]](https://hydra.nixos.org/build/257678333) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257675084) [[📱✅]](https://hydra.nixos.org/build/257688610) [[🍎⏳]](https://hydra.nixos.org/build/257678245) [[🐧✅]](https://hydra.nixos.org/build/257676686) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257694716) [[📱❗]](https://hydra.nixos.org/build/257675030) [[🍎⏳]](https://hydra.nixos.org/build/257697361) [[🐧✅]](https://hydra.nixos.org/build/257685609) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257700287) [[📱✅]](https://hydra.nixos.org/build/257683486) [[🍎⏳]](https://hydra.nixos.org/build/257689398) [[🐧✅]](https://hydra.nixos.org/build/257677068) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257719760) [[📱✅]](https://hydra.nixos.org/build/257709544) [[🍎⏳]](https://hydra.nixos.org/build/257714367) [[🐧⏳]](https://hydra.nixos.org/build/257721642) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.hpack)
  - [[🍏⏳]](https://hydra.nixos.org/build/257726317) [[📱✅]](https://hydra.nixos.org/build/257724843) [[🍎⏳]](https://hydra.nixos.org/build/257701295) [[🐧⏳]](https://hydra.nixos.org/build/257718067) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/257712597) [[📱✅]](https://hydra.nixos.org/build/257719899) [[🍎⏳]](https://hydra.nixos.org/build/257708821) [[🐧⏳]](https://hydra.nixos.org/build/257724209) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/257717293) [[📱✅]](https://hydra.nixos.org/build/257714478) [[🍎⏳]](https://hydra.nixos.org/build/257717258) [[🐧⏳]](https://hydra.nixos.org/build/257719764) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hpack)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257725122) [[📱✅]](https://hydra.nixos.org/build/257709447) [[🍎⏳]](https://hydra.nixos.org/build/257725603) [[🐧⏳]](https://hydra.nixos.org/build/257725298) [haskellPackages.di-df1](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.di-df1)  ⤴️ 3 | 9
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257719543) [[📱✅]](https://hydra.nixos.org/build/257717875) [[🍎⏳]](https://hydra.nixos.org/build/257707765) [[🐧⏳]](https://hydra.nixos.org/build/257718280) [haskellPackages.nyan-interpolation-core](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.nyan-interpolation-core)  ⤴️ 2 | 2
- [ ] [hoogle](https://hydra.nixos.org/eval/1805953?filter=hoogle)  ⤴️ 1 | 5
  - [[🍏⏳]](https://hydra.nixos.org/build/257688208) [[📱✅]](https://hydra.nixos.org/build/257696545) [[🍎⏳]](https://hydra.nixos.org/build/257697660) [[🐧⏳]](https://hydra.nixos.org/build/257680915) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.hoogle)
  - [[🍏❗]](https://hydra.nixos.org/build/257677963) [[📱✅]](https://hydra.nixos.org/build/257675225) [[🍎⏳]](https://hydra.nixos.org/build/257679488) [[🐧⏳]](https://hydra.nixos.org/build/257695112) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257687348) [[📱✅]](https://hydra.nixos.org/build/257692591) [[🍎⏳]](https://hydra.nixos.org/build/257698800) [[🐧⏳]](https://hydra.nixos.org/build/257688791) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257691287) [[📱✅]](https://hydra.nixos.org/build/257677629) [[🍎⏳]](https://hydra.nixos.org/build/257687876) [[🐧⏳]](https://hydra.nixos.org/build/257689776) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257680328) [[📱✅]](https://hydra.nixos.org/build/257690584) [[🍎⏳]](https://hydra.nixos.org/build/257676045) [[🐧⏳]](https://hydra.nixos.org/build/257696887) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257693680) [[📱✅]](https://hydra.nixos.org/build/257688259) [[🍎⏳]](https://hydra.nixos.org/build/257699520) [[🐧⏳]](https://hydra.nixos.org/build/257680278) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.hoogle)
  - [[🍏❗]](https://hydra.nixos.org/build/257683096) [[📱✅]](https://hydra.nixos.org/build/257674994) [[🍎⏳]](https://hydra.nixos.org/build/257685461) [[🐧⏳]](https://hydra.nixos.org/build/257674885) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257693781) [[📱✅]](https://hydra.nixos.org/build/257699646) [[🍎⏳]](https://hydra.nixos.org/build/257679849) [[🐧⏳]](https://hydra.nixos.org/build/257699247) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257696451) [[📱❗]](https://hydra.nixos.org/build/257685914) [[🍎⏳]](https://hydra.nixos.org/build/257694863) [[🐧⏳]](https://hydra.nixos.org/build/257678428) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257697339) [[📱✅]](https://hydra.nixos.org/build/257677492) [[🍎⏳]](https://hydra.nixos.org/build/257693407) [[🐧⏳]](https://hydra.nixos.org/build/257698552) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257703229) [[📱✅]](https://hydra.nixos.org/build/257718026) [[🍎⏳]](https://hydra.nixos.org/build/257724803) [[🐧⏳]](https://hydra.nixos.org/build/257711945) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257724447) [[📱✅]](https://hydra.nixos.org/build/257710326) [[🍎⏳]](https://hydra.nixos.org/build/257703157) [[🐧⏳]](https://hydra.nixos.org/build/257717966) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257700807) [[📱✅]](https://hydra.nixos.org/build/257720964) [[🍎⏳]](https://hydra.nixos.org/build/257726118) [[🐧⏳]](https://hydra.nixos.org/build/257716214) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/257726544) [[📱✅]](https://hydra.nixos.org/build/257716383) [[🍎⏳]](https://hydra.nixos.org/build/257703036) [[🐧⏳]](https://hydra.nixos.org/build/257714591) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hoogle)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257702590) [[📱✅]](https://hydra.nixos.org/build/257722695) [[🍎⏳]](https://hydra.nixos.org/build/257708240) [[🐧⏳]](https://hydra.nixos.org/build/257713103) [haskellPackages.di-polysemy](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.di-polysemy)  ⤴️ 0 | 4
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257720452) [[📱✅]](https://hydra.nixos.org/build/257709075) [[🍎⏳]](https://hydra.nixos.org/build/257704050) [[🐧⏳]](https://hydra.nixos.org/build/257703056) [haskellPackages.di](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.di)  ⤴️ 0 | 2
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257721345) [[📱❗]](https://hydra.nixos.org/build/257708475) [[🍎⏳]](https://hydra.nixos.org/build/257710788) [[🐧⏳]](https://hydra.nixos.org/build/257724414) [haskellPackages.looksee](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.looksee)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257717325) [[📱✅]](https://hydra.nixos.org/build/257704604) [[🍎⏳]](https://hydra.nixos.org/build/257704540) [[🐧⏳]](https://hydra.nixos.org/build/257725241) [haskellPackages.render-utf8](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.render-utf8)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257703702) [[📱✅]](https://hydra.nixos.org/build/257715054) [[🍎❗]](https://hydra.nixos.org/build/257723117) [[🐧⏳]](https://hydra.nixos.org/build/257724481) [haskellPackages.amqp-utils](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.amqp-utils) 
- [ ] [cabal2nix-unstable](https://hydra.nixos.org/eval/1805953?filter=cabal2nix-unstable) 
  - [[🍏⏳]](https://hydra.nixos.org/build/257677885) [[📱✅]](https://hydra.nixos.org/build/257682063) [[🍎⏳]](https://hydra.nixos.org/build/257691622) [[🐧⏳]](https://hydra.nixos.org/build/257699821) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.cabal2nix-unstable)
  - [[🍏❗]](https://hydra.nixos.org/build/257693073) [[📱✅]](https://hydra.nixos.org/build/257682499) [[🍎⏳]](https://hydra.nixos.org/build/257677426) [[🐧⏳]](https://hydra.nixos.org/build/257685659) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257681970) [[📱✅]](https://hydra.nixos.org/build/257691476) [[🍎⏳]](https://hydra.nixos.org/build/257689692) [[🐧⏳]](https://hydra.nixos.org/build/257677662) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257688173) [[📱✅]](https://hydra.nixos.org/build/257685819) [[🍎⏳]](https://hydra.nixos.org/build/257680127) [[🐧⏳]](https://hydra.nixos.org/build/257678163) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257698380) [[📱✅]](https://hydra.nixos.org/build/257692504) [[🍎⏳]](https://hydra.nixos.org/build/257684368) [[🐧⏳]](https://hydra.nixos.org/build/257684553) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257696493) [[📱✅]](https://hydra.nixos.org/build/257686611) [[🍎⏳]](https://hydra.nixos.org/build/257684030) [[🐧⏳]](https://hydra.nixos.org/build/257699214) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.cabal2nix-unstable)
  - [[🍏❗]](https://hydra.nixos.org/build/257694059) [[📱✅]](https://hydra.nixos.org/build/257698589) [[🍎⏳]](https://hydra.nixos.org/build/257689433) [[🐧⏳]](https://hydra.nixos.org/build/257693925) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257684052) [[📱✅]](https://hydra.nixos.org/build/257675262) [[🍎⏳]](https://hydra.nixos.org/build/257693238) [[🐧⏳]](https://hydra.nixos.org/build/257697969) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257680321) [[📱❗]](https://hydra.nixos.org/build/257683361) [[🍎⏳]](https://hydra.nixos.org/build/257689639) [[🐧⏳]](https://hydra.nixos.org/build/257677250) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257692152) [[📱✅]](https://hydra.nixos.org/build/257687908) [[🍎⏳]](https://hydra.nixos.org/build/257679192) [[🐧⏳]](https://hydra.nixos.org/build/257675697) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257702923) [[📱❗]](https://hydra.nixos.org/build/257716586) [[🍎⏳]](https://hydra.nixos.org/build/257726306) [[🐧⏳]](https://hydra.nixos.org/build/257716367) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257717107) [[📱✅]](https://hydra.nixos.org/build/257708638) [[🍎⏳]](https://hydra.nixos.org/build/257714267) [[🐧⏳]](https://hydra.nixos.org/build/257701212) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257719823) [[📱✅]](https://hydra.nixos.org/build/257715090) [[🍎⏳]](https://hydra.nixos.org/build/257716220) [[🐧⏳]](https://hydra.nixos.org/build/257709855) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.cabal2nix-unstable)
  - [[🍏⏳]](https://hydra.nixos.org/build/257722160) [[📱✅]](https://hydra.nixos.org/build/257709264) [[🍎⏳]](https://hydra.nixos.org/build/257702667) [[🐧⏳]](https://hydra.nixos.org/build/257726076) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.cabal2nix-unstable)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257708292) [[📱✅]](https://hydra.nixos.org/build/257706294) [[🍎⏳]](https://hydra.nixos.org/build/257710521) [[🐧⏳]](https://hydra.nixos.org/build/257700880) [haskellPackages.cardano-coin-selection](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.cardano-coin-selection) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257701864) [[📱✅]](https://hydra.nixos.org/build/257716524) [[🍎❗]](https://hydra.nixos.org/build/257703153) [[🐧⏳]](https://hydra.nixos.org/build/257717769) [haskellPackages.cgrep](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.cgrep) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257701357) [[📱✅]](https://hydra.nixos.org/build/257719636) [[🍎⏳]](https://hydra.nixos.org/build/257700777) [[🐧⏳]](https://hydra.nixos.org/build/257711234) [haskellPackages.fmt-terminal-colors](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.fmt-terminal-colors) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257716440) [[📱✅]](https://hydra.nixos.org/build/257719277) [[🍎❗]](https://hydra.nixos.org/build/257722577) [[🐧⏳]](https://hydra.nixos.org/build/257705737) [haskellPackages.foma](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.foma) 
- [ ] [ghc-lib](https://hydra.nixos.org/eval/1805953?filter=ghc-lib) 
  - [[🍏✅]](https://hydra.nixos.org/build/257077797) [[📱✅]](https://hydra.nixos.org/build/257098937) [[🍎✅]](https://hydra.nixos.org/build/257090165) [[🐧✅]](https://hydra.nixos.org/build/257089443) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc8107.ghc-lib)
  - [[🍏❗]](https://hydra.nixos.org/build/257093281) [[📱❗]](https://hydra.nixos.org/build/257097883) [[🍎❗]](https://hydra.nixos.org/build/257099706) [[🐧❗]](https://hydra.nixos.org/build/257100581) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc902.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257095240) [[📱✅]](https://hydra.nixos.org/build/257078493) [[🍎✅]](https://hydra.nixos.org/build/257093209) [[🐧✅]](https://hydra.nixos.org/build/257078984) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc925.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257084083) [[📱✅]](https://hydra.nixos.org/build/257096241) [[🍎✅]](https://hydra.nixos.org/build/257085511) [[🐧✅]](https://hydra.nixos.org/build/257077274) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc926.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257098107) [[📱✅]](https://hydra.nixos.org/build/257094829) [[🍎✅]](https://hydra.nixos.org/build/257088693) [[🐧✅]](https://hydra.nixos.org/build/257087869) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc927.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257083110) [[📱✅]](https://hydra.nixos.org/build/257096172) [[🍎✅]](https://hydra.nixos.org/build/257077377) [[🐧✅]](https://hydra.nixos.org/build/257096562) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc928.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257096703) [[📱✅]](https://hydra.nixos.org/build/257095542) [[🍎✅]](https://hydra.nixos.org/build/257089911) [[🐧✅]](https://hydra.nixos.org/build/257092024) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc945.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257090710) [[📱✅]](https://hydra.nixos.org/build/257088590) [[🍎✅]](https://hydra.nixos.org/build/257101995) [[🐧✅]](https://hydra.nixos.org/build/257098298) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc946.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257100258) [[📱✅]](https://hydra.nixos.org/build/257082342) [[🍎✅]](https://hydra.nixos.org/build/257095470) [[🐧✅]](https://hydra.nixos.org/build/257090442) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc947.ghc-lib)
  - [[🍏✅]](https://hydra.nixos.org/build/257093591) [[📱✅]](https://hydra.nixos.org/build/257088462) [[🍎✅]](https://hydra.nixos.org/build/257090490) [[🐧✅]](https://hydra.nixos.org/build/257095602) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc948.ghc-lib)
  - [[🍏⏳]](https://hydra.nixos.org/build/257714427) [[📱✅]](https://hydra.nixos.org/build/257719069) [[🍎⏳]](https://hydra.nixos.org/build/257726138) [[🐧⏳]](https://hydra.nixos.org/build/257717692) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc963.ghc-lib)
  - [[🍏⏳]](https://hydra.nixos.org/build/257711202) [[📱✅]](https://hydra.nixos.org/build/257724088) [[🍎⏳]](https://hydra.nixos.org/build/257704055) [[🐧⏳]](https://hydra.nixos.org/build/257711772) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc964.ghc-lib)
  - [[🍏⏳]](https://hydra.nixos.org/build/257712963) [[📱✅]](https://hydra.nixos.org/build/257705736) [[🍎⏳]](https://hydra.nixos.org/build/257703621) [[🐧⏳]](https://hydra.nixos.org/build/257710006) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1805953?filter=haskell.packages.ghc965.ghc-lib)
  - [[🍏⏳]](https://hydra.nixos.org/build/257711270) [[📱✅]](https://hydra.nixos.org/build/257713887) [[🍎⏳]](https://hydra.nixos.org/build/257706196) [[🐧⏳]](https://hydra.nixos.org/build/257721699) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.ghc-lib)
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257713808) [[📱❗]](https://hydra.nixos.org/build/257710999) [[🍎⏳]](https://hydra.nixos.org/build/257708965) [[🐧⏳]](https://hydra.nixos.org/build/257721302) [haskellPackages.ghcide-bench](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.ghcide-bench) 
- [ ] [hello](https://hydra.nixos.org/eval/1805953?filter=hello) 
  - [[🍏⏳]](https://hydra.nixos.org/build/257720406) [[📱✅]](https://hydra.nixos.org/build/257715980) [[🍎⏳]](https://hydra.nixos.org/build/257715082) [[🐧⏳]](https://hydra.nixos.org/build/257723976) [haskellPackages](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hello)
  - [[🍏⏳]](https://hydra.nixos.org/build/257719123)  [[🍎⏳]](https://hydra.nixos.org/build/257702707) [[🐧⏳]](https://hydra.nixos.org/build/257704945) [pkgsCross.ghcjs.haskell.packages.ghc98](https://hydra.nixos.org/eval/1805953?filter=pkgsCross.ghcjs.haskell.packages.ghc98.hello)
  - [[🍏❗]](https://hydra.nixos.org/build/257713197)  [[🍎⏳]](https://hydra.nixos.org/build/257723742) [[🐧⏳]](https://hydra.nixos.org/build/257724244) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1805953?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.hello)
  - [[🍏⏳]](https://hydra.nixos.org/build/257706685)  [[🍎⏳]](https://hydra.nixos.org/build/257721071) [[🐧⏳]](https://hydra.nixos.org/build/257720646) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1805953?filter=pkgsCross.ghcjs.haskellPackages.hello)
  -    [[🐧⏳]](https://hydra.nixos.org/build/257713624) [pkgsMusl.haskellPackages](https://hydra.nixos.org/eval/1805953?filter=pkgsMusl.haskellPackages.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/257097676) [pkgsStatic.haskell.packages.native-bignum.ghc948](https://hydra.nixos.org/eval/1805953?filter=pkgsStatic.haskell.packages.native-bignum.ghc948.hello)
  -    [[🐧⏳]](https://hydra.nixos.org/build/257702293) [pkgsStatic.haskell.packages.native-bignum.ghc982](https://hydra.nixos.org/eval/1805953?filter=pkgsStatic.haskell.packages.native-bignum.ghc982.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/257092821) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1805953?filter=pkgsStatic.haskellPackages.hello)
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257714181) [[📱❗]](https://hydra.nixos.org/build/257709841) [[🍎⏳]](https://hydra.nixos.org/build/257718351) [[🐧⏳]](https://hydra.nixos.org/build/257724768) [haskellPackages.hls-test-utils](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hls-test-utils) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257722120) [[📱❗]](https://hydra.nixos.org/build/257715132) [[🍎⏳]](https://hydra.nixos.org/build/257722456) [[🐧⏳]](https://hydra.nixos.org/build/257714525) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257706297) [[📱✅]](https://hydra.nixos.org/build/257709831) [[🍎⏳]](https://hydra.nixos.org/build/257719038) [[🐧⏳]](https://hydra.nixos.org/build/257707689) [haskellPackages.mem-info](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.mem-info) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257703639) [[📱❗]](https://hydra.nixos.org/build/257723685) [[🍎⏳]](https://hydra.nixos.org/build/257721177) [[🐧⏳]](https://hydra.nixos.org/build/257701349) [haskellPackages.microdns](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.microdns) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257725466) [[📱✅]](https://hydra.nixos.org/build/257704518) [[🍎⏳]](https://hydra.nixos.org/build/257705897) [[🐧⏳]](https://hydra.nixos.org/build/257711807) [haskellPackages.nyan-interpolation](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.nyan-interpolation) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257705186) [[📱✅]](https://hydra.nixos.org/build/257721108) [[🍎⏳]](https://hydra.nixos.org/build/257705331) [[🐧⏳]](https://hydra.nixos.org/build/257709657) [haskellPackages.nyan-interpolation-simple](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.nyan-interpolation-simple) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257710715) [[📱❗]](https://hydra.nixos.org/build/257712571) [[🍎⏳]](https://hydra.nixos.org/build/257704425) [[🐧⏳]](https://hydra.nixos.org/build/257702993) [haskellPackages.prodapi-proxy](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.prodapi-proxy) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/257711904) [[📱❗]](https://hydra.nixos.org/build/257712217) [[🍎⏳]](https://hydra.nixos.org/build/257718524) [[🐧⏳]](https://hydra.nixos.org/build/257703993) [haskellPackages.prodapi-userauth](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.prodapi-userauth) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257708959) [[📱✅]](https://hydra.nixos.org/build/257708442) [[🍎⏳]](https://hydra.nixos.org/build/257722595) [[🐧⏳]](https://hydra.nixos.org/build/257723374) [haskellPackages.quickcheck-quid](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.quickcheck-quid) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257705421) [[📱✅]](https://hydra.nixos.org/build/257723626) [[🍎⏳]](https://hydra.nixos.org/build/257715871) [[🐧⏳]](https://hydra.nixos.org/build/257723587) [haskellPackages.rg](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.rg) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/257706526) [[📱✅]](https://hydra.nixos.org/build/257705442) [[🍎⏳]](https://hydra.nixos.org/build/257722316) [[🐧⏳]](https://hydra.nixos.org/build/257707001) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1805953?filter=haskellPackages.xbattbar) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) ⤴️ 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) ⤴️ 152  
[failure](https://packdeps.haskellers.com/reverse/failure) ⤴️ 72  
[connection](https://packdeps.haskellers.com/reverse/connection) ⤴️ 56  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) ⤴️ 56  
[util](https://packdeps.haskellers.com/reverse/util) ⤴️ 49  
[derive](https://packdeps.haskellers.com/reverse/derive) ⤴️ 48  
[system-fileio](https://packdeps.haskellers.com/reverse/system-fileio) ⤴️ 45  
[web-routes](https://packdeps.haskellers.com/reverse/web-routes) ⤴️ 43  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) ⤴️ 42  
[syb-with-class](https://packdeps.haskellers.com/reverse/syb-with-class) ⤴️ 42  
[MonadCatchIO-transformers](https://packdeps.haskellers.com/reverse/MonadCatchIO-transformers) ⤴️ 41  
[TypeCompose](https://packdeps.haskellers.com/reverse/TypeCompose) ⤴️ 41  
[singletons-base](https://packdeps.haskellers.com/reverse/singletons-base) ⤴️ 41  
[crypto-random](https://packdeps.haskellers.com/reverse/crypto-random) ⤴️ 37  
[PrimitiveArray](https://packdeps.haskellers.com/reverse/PrimitiveArray) ⤴️ 35  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) ⤴️ 33  
[dual](https://packdeps.haskellers.com/reverse/dual) ⤴️ 32  
[hsp](https://packdeps.haskellers.com/reverse/hsp) ⤴️ 32  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) ⤴️ 31  
[language-ecmascript](https://packdeps.haskellers.com/reverse/language-ecmascript) ⤴️ 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) ⤴️ 30  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) ⤴️ 29  
[composite-base](https://packdeps.haskellers.com/reverse/composite-base) ⤴️ 28  
[polysemy-time](https://packdeps.haskellers.com/reverse/polysemy-time) ⤴️ 28  
[polysemy-resume](https://packdeps.haskellers.com/reverse/polysemy-resume) ⤴️ 27  
[polysemy-conc](https://packdeps.haskellers.com/reverse/polysemy-conc) ⤴️ 26  
[regexpr](https://packdeps.haskellers.com/reverse/regexpr) ⤴️ 26  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) ⤴️ 25  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) ⤴️ 25  
[HList](https://packdeps.haskellers.com/reverse/HList) ⤴️ 24  
[polysemy-log](https://packdeps.haskellers.com/reverse/polysemy-log) ⤴️ 24  
[web-routes-th](https://packdeps.haskellers.com/reverse/web-routes-th) ⤴️ 24  
[Crypto](https://packdeps.haskellers.com/reverse/Crypto) ⤴️ 22  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) ⤴️ 22  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) ⤴️ 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) ⤴️ 22  
[BiobaseTypes](https://packdeps.haskellers.com/reverse/BiobaseTypes) ⤴️ 21  
[alg](https://packdeps.haskellers.com/reverse/alg) ⤴️ 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) ⤴️ 21  
[userid](https://packdeps.haskellers.com/reverse/userid) ⤴️ 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) ⤴️ 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) ⤴️ 20  
[reform](https://packdeps.haskellers.com/reverse/reform) ⤴️ 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) ⤴️ 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) ⤴️ 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) ⤴️ 19  
[cprng-aes](https://packdeps.haskellers.com/reverse/cprng-aes) ⤴️ 19  
[fay](https://packdeps.haskellers.com/reverse/fay) ⤴️ 19  
[harp](https://packdeps.haskellers.com/reverse/harp) ⤴️ 19  
</details>


*⤴️: The number of packages that depend (directly or indirectly) on this package (if any). If two numbers are shown the first (lower) number considers only packages which currently have enabled hydra jobs, i.e. are not marked broken. The second (higher) number considers all packages.*

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
