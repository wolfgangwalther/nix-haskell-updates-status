### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1802777](https://hydra.nixos.org/eval/1802777) of nixpkgs commit [0b8c1b3](https://github.com/NixOS/nixpkgs/commits/0b8c1b3e5f1e32250b110daaeca68d65c2d0f78b) as of 2023-12-11 18:16 UTC*

🟡 **Potential issues** (and possibly [evaluation errors](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates))
  * `maintained` jobset failed.

#### Build summary

 | Platform | Failed ❌ | DependencyFailed ❗ | TimedOut ⌛🚫 | HydraFailure 🚧 | Success ✅ | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-darwin 🍏](https://hydra.nixos.org/eval/1802777?filter=.aarch64-darwin) | 87 | 44 |  | 1 | 6659 | 
 | [aarch64-linux 📱](https://hydra.nixos.org/eval/1802777?filter=.aarch64-linux) | 29 | 11 | 3 |  | 6823 | 
 | [x86_64-darwin 🍎](https://hydra.nixos.org/eval/1802777?filter=.x86_64-darwin) | 74 | 34 | 1 |  | 6695 | 
 | [x86_64-linux 🐧](https://hydra.nixos.org/eval/1802777?filter=.x86_64-linux) | 13 | 7 | 1 |  | 6884 | 
#### Maintained Linux packages with build failure
- [ ] [[📱❌]](https://hydra.nixos.org/build/243329135) [[🐧✅]](https://hydra.nixos.org/build/243322653) [haskellPackages.board-games](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.board-games) @thielema
- [ ] [dhall-nix](https://hydra.nixos.org/eval/1802777?filter=dhall-nix) @Gabriella439
  - [[📱❌]](https://hydra.nixos.org/build/243492900) [[🐧❌]](https://hydra.nixos.org/build/243492913) [toplevel](https://hydra.nixos.org/eval/1802777?filter=dhall-nix)
  - [[📱❌]](https://hydra.nixos.org/build/243492872) [[🐧❌]](https://hydra.nixos.org/build/243492906) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.dhall-nix)
- [ ] [update-nix-fetchgit](https://hydra.nixos.org/eval/1802777?filter=update-nix-fetchgit) @expipiplus1 @sorki
  - [[📱❌]](https://hydra.nixos.org/build/243492930) [[🐧❌]](https://hydra.nixos.org/build/243492919) [toplevel](https://hydra.nixos.org/eval/1802777?filter=update-nix-fetchgit)
  - [[📱❌]](https://hydra.nixos.org/build/243492910) [[🐧❌]](https://hydra.nixos.org/build/243492873) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.update-nix-fetchgit)
- [ ] [wstunnel](https://hydra.nixos.org/eval/1802777?filter=wstunnel) @gebner
  - [[📱✅]](https://hydra.nixos.org/build/243333164) [[🐧✅]](https://hydra.nixos.org/build/243329406) [toplevel](https://hydra.nixos.org/eval/1802777?filter=wstunnel)
  - [[📱❌]](https://hydra.nixos.org/build/243325125) [[🐧✅]](https://hydra.nixos.org/build/243323374) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.wstunnel)
#### Maintained Linux packages with failed dependency
- [ ] [git-annex](https://hydra.nixos.org/eval/1802777?filter=git-annex) @peti @roosemberth
  - [[📱❗]](https://hydra.nixos.org/build/243364289) [[🐧❗]](https://hydra.nixos.org/build/243364250) [toplevel](https://hydra.nixos.org/eval/1802777?filter=git-annex)
  - [[📱❗]](https://hydra.nixos.org/build/243364402) [[🐧❗]](https://hydra.nixos.org/build/243364420) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.git-annex)
- [ ] [[🐧❗]](https://hydra.nixos.org/build/243659771) [maintained](https://hydra.nixos.org/eval/1802777?filter=maintained) @cdepillabout @expipiplus1 @maralorn @ncfavier @sternenseemann
- [ ] [termonad](https://hydra.nixos.org/eval/1802777?filter=termonad) @cdepillabout
  - [[📱❗]](https://hydra.nixos.org/build/243326444) [[🐧❗]](https://hydra.nixos.org/build/243327072) [toplevel](https://hydra.nixos.org/eval/1802777?filter=termonad)
  - [[📱❗]](https://hydra.nixos.org/build/243321225) [[🐧❗]](https://hydra.nixos.org/build/243323835) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.termonad)
#### Maintained Darwin packages with build failure
<details><summary>16 job(s) </summary>

- [ ] [dhall-nix](https://hydra.nixos.org/eval/1802777?filter=dhall-nix) @Gabriella439
  - [[🍏❌]](https://hydra.nixos.org/build/243492904) [[🍎❌]](https://hydra.nixos.org/build/243492894) [toplevel](https://hydra.nixos.org/eval/1802777?filter=dhall-nix)
  - [[🍏❌]](https://hydra.nixos.org/build/243492897) [[🍎❌]](https://hydra.nixos.org/build/243492896) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.dhall-nix)
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243329001) [[🍎❌]](https://hydra.nixos.org/build/243322675) [haskellPackages.gcodehs](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gcodehs) @sorki
- [ ] [ghc98](https://hydra.nixos.org/eval/1802777?filter=ghc98) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏✅]](https://hydra.nixos.org/build/243325932) [[🍎✅]](https://hydra.nixos.org/build/243330673) [haskell.compiler](https://hydra.nixos.org/eval/1802777?filter=haskell.compiler.ghc98)
  - [[🍏❌]](https://hydra.nixos.org/build/243326307) [[🍎✅]](https://hydra.nixos.org/build/243329961) [haskell.compiler.native-bignum](https://hydra.nixos.org/eval/1802777?filter=haskell.compiler.native-bignum.ghc98)
- [ ] [ghc981](https://hydra.nixos.org/eval/1802777?filter=ghc981) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏✅]](https://hydra.nixos.org/build/243329785) [[🍎✅]](https://hydra.nixos.org/build/243332071) [haskell.compiler](https://hydra.nixos.org/eval/1802777?filter=haskell.compiler.ghc981)
  - [[🍏❌]](https://hydra.nixos.org/build/243322813) [[🍎✅]](https://hydra.nixos.org/build/243327354) [haskell.compiler.native-bignum](https://hydra.nixos.org/eval/1802777?filter=haskell.compiler.native-bignum.ghc981)
- [ ] [gitit](https://hydra.nixos.org/eval/1802777?filter=gitit) @Profpatsch @sternenseemann
  - [[🍏❌]](https://hydra.nixos.org/build/243322776) [[🍎✅]](https://hydra.nixos.org/build/243322079) [toplevel](https://hydra.nixos.org/eval/1802777?filter=gitit)
  - [[🍏✅]](https://hydra.nixos.org/build/243320889) [[🍎✅]](https://hydra.nixos.org/build/243321555) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gitit)
- [ ] [update-nix-fetchgit](https://hydra.nixos.org/eval/1802777?filter=update-nix-fetchgit) @expipiplus1 @sorki
  - [[🍏❌]](https://hydra.nixos.org/build/243492871) [[🍎❌]](https://hydra.nixos.org/build/243492929) [toplevel](https://hydra.nixos.org/eval/1802777?filter=update-nix-fetchgit)
  - [[🍏❌]](https://hydra.nixos.org/build/243492921) [[🍎❌]](https://hydra.nixos.org/build/243492917) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.update-nix-fetchgit)
</details>

#### Maintained Darwin packages with failed dependency
<details><summary>17 job(s) </summary>

- [ ] [git-annex](https://hydra.nixos.org/eval/1802777?filter=git-annex) @peti @roosemberth
  - [[🍏❗]](https://hydra.nixos.org/build/243364587) [[🍎❗]](https://hydra.nixos.org/build/243364589) [toplevel](https://hydra.nixos.org/eval/1802777?filter=git-annex)
  - [[🍏❗]](https://hydra.nixos.org/build/243364581) [[🍎❗]](https://hydra.nixos.org/build/243364590) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.git-annex)
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1802777?filter=haskell-language-server) @maralorn
  - [[🍏✅]](https://hydra.nixos.org/build/243364254) [[🍎✅]](https://hydra.nixos.org/build/243364404) [toplevel](https://hydra.nixos.org/eval/1802777?filter=haskell-language-server)
  - [[🍏❗]](https://hydra.nixos.org/build/243322494) [[🍎✅]](https://hydra.nixos.org/build/243328502) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc902.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243331841) [[🍎✅]](https://hydra.nixos.org/build/243325367) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc924.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243327169) [[🍎✅]](https://hydra.nixos.org/build/243321095) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc925.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243330797) [[🍎✅]](https://hydra.nixos.org/build/243326430) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc926.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243330025) [[🍎✅]](https://hydra.nixos.org/build/243331300) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc927.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243328347) [[🍎✅]](https://hydra.nixos.org/build/243326611) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc928.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243364330) [[🍎✅]](https://hydra.nixos.org/build/243364407) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc945.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243364341) [[🍎✅]](https://hydra.nixos.org/build/243364452) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc946.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243364336) [[🍎✅]](https://hydra.nixos.org/build/243364446) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc947.haskell-language-server)
  - [[🍏🚧]](https://hydra.nixos.org/build/243364328) [[🍎✅]](https://hydra.nixos.org/build/243364426) [haskell.packages.ghc962](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc962.haskell-language-server)
  - [[🍏🚧]](https://hydra.nixos.org/build/243364292) [[🍎✅]](https://hydra.nixos.org/build/243364345) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc963.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/243364460) [[🍎✅]](https://hydra.nixos.org/build/243364461) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.haskell-language-server)
</details>

#### Unmaintained packages with build failure
<details><summary>116 job(s) </summary>

- [ ] [[🍏❌]](https://hydra.nixos.org/build/241416250) [[📱✅]](https://hydra.nixos.org/build/241426391) [[🍎❌]](https://hydra.nixos.org/build/241418696) [[🐧✅]](https://hydra.nixos.org/build/241432601) [haskellPackages.di-core](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.di-core)  ⤴️ 7 | 11
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243326433) [[📱✅]](https://hydra.nixos.org/build/243331061) [[🍎❌]](https://hydra.nixos.org/build/243325287) [[🐧✅]](https://hydra.nixos.org/build/243324957) [haskellPackages.fmt](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.fmt)  ⤴️ 6 | 24
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241431423) [[📱✅]](https://hydra.nixos.org/build/241433048) [[🍎❌]](https://hydra.nixos.org/build/241420008) [[🐧✅]](https://hydra.nixos.org/build/241434280) [haskellPackages.lbfgs](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.lbfgs)  ⤴️ 3 | 3
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243323880) [[📱❌]](https://hydra.nixos.org/build/243330390) [[🍎✅]](https://hydra.nixos.org/build/243326743) [[🐧✅]](https://hydra.nixos.org/build/243329479) [haskellPackages.spatial-math](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.spatial-math)  ⤴️ 2 | 7
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243331774) [[📱❌]](https://hydra.nixos.org/build/243327289) [[🍎❌]](https://hydra.nixos.org/build/243329343) [[🐧❌]](https://hydra.nixos.org/build/243324186) [haskellPackages.cairo-image](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.cairo-image)  ⤴️ 2 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243325596) [[📱❌]](https://hydra.nixos.org/build/243321733) [[🍎❌]](https://hydra.nixos.org/build/243324698) [[🐧❌]](https://hydra.nixos.org/build/243324592) [haskellPackages.opencascade-hs](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.opencascade-hs)  ⤴️ 2 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241438044) [[📱✅]](https://hydra.nixos.org/build/241421617) [[🍎❌]](https://hydra.nixos.org/build/241431081) [[🐧✅]](https://hydra.nixos.org/build/241440950) [haskellPackages.HsSyck](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.HsSyck)  ⤴️ 1 | 10
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243333023) [[📱❌]](https://hydra.nixos.org/build/243328263) [[🍎❌]](https://hydra.nixos.org/build/243322988) [[🐧✅]](https://hydra.nixos.org/build/243328607) [haskellPackages.nqe](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.nqe)  ⤴️ 1 | 4
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243327486) [[📱⌛🚫]](https://hydra.nixos.org/build/243331547) [[🍎✅]](https://hydra.nixos.org/build/243329295) [[🐧✅]](https://hydra.nixos.org/build/243331909) [haskellPackages.telegram-bot-api](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.telegram-bot-api)  ⤴️ 1 | 4
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241423203) [[📱✅]](https://hydra.nixos.org/build/241421742) [[🍎✅]](https://hydra.nixos.org/build/241441956) [[🐧✅]](https://hydra.nixos.org/build/241417284) [haskellPackages.cabal-install-solver](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.cabal-install-solver)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243330026) [[📱✅]](https://hydra.nixos.org/build/243330545) [[🍎❌]](https://hydra.nixos.org/build/243325488) [[🐧✅]](https://hydra.nixos.org/build/243333050) [haskellPackages.posix-socket](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.posix-socket)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243322283) [[📱✅]](https://hydra.nixos.org/build/243323215) [[🍎✅]](https://hydra.nixos.org/build/243331253) [[🐧✅]](https://hydra.nixos.org/build/243330110) [haskellPackages.postgresql-syntax](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.postgresql-syntax)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243326643) [[📱✅]](https://hydra.nixos.org/build/243332016) [[🍎❌]](https://hydra.nixos.org/build/243321705) [[🐧✅]](https://hydra.nixos.org/build/243331202) [haskellPackages.async-refresh](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.async-refresh)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243332579) [[📱✅]](https://hydra.nixos.org/build/243324399) [[🍎❌]](https://hydra.nixos.org/build/243329931) [[🐧✅]](https://hydra.nixos.org/build/243326415) [haskellPackages.gi-gdkx11](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gi-gdkx11)  ⤴️ 1 | 1
- [ ] [[📱❌]](https://hydra.nixos.org/build/243323345) [[🐧❌]](https://hydra.nixos.org/build/243322033) [haskellPackages.gi-vte](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gi-vte)  ⤴️ 1 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/241516517) [[📱✅]](https://hydra.nixos.org/build/241521193) [[🍎❌]](https://hydra.nixos.org/build/241516668) [[🐧✅]](https://hydra.nixos.org/build/241523355) [haskellPackages.mighty-metropolis](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.mighty-metropolis)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241441570) [[📱❌]](https://hydra.nixos.org/build/241442221) [[🍎✅]](https://hydra.nixos.org/build/241428090) [[🐧✅]](https://hydra.nixos.org/build/241433603) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.nlopt-haskell)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241438874) [[📱✅]](https://hydra.nixos.org/build/242598172) [[🍎❌]](https://hydra.nixos.org/build/241419480) [[🐧✅]](https://hydra.nixos.org/build/242598343) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.openal-ffi)  ⤴️ 1 | 1
- [ ] [[🍎❌]](https://hydra.nixos.org/build/243324883) [[🐧✅]](https://hydra.nixos.org/build/243329065) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.swisstable)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241429613) [[📱✅]](https://hydra.nixos.org/build/241429324) [[🍎❌]](https://hydra.nixos.org/build/241434255) [[🐧✅]](https://hydra.nixos.org/build/241440845) [haskellPackages.sym](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.sym)  ⤴️ 1 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/241416931) [[📱❌]](https://hydra.nixos.org/build/241432083) [[🍎✅]](https://hydra.nixos.org/build/241421537) [[🐧✅]](https://hydra.nixos.org/build/241441339) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.freetype2)  ⤴️ 0 | 12
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243327202) [[📱❌]](https://hydra.nixos.org/build/243333204) [[🍎✅]](https://hydra.nixos.org/build/243333262) [[🐧✅]](https://hydra.nixos.org/build/243323846) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hw-simd)  ⤴️ 0 | 9
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243326281) [[📱❌]](https://hydra.nixos.org/build/243326616) [[🍎✅]](https://hydra.nixos.org/build/243332859) [[🐧✅]](https://hydra.nixos.org/build/243332985) [haskellPackages.toolshed](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.toolshed)  ⤴️ 0 | 7
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243325252) [[📱✅]](https://hydra.nixos.org/build/243324489) [[🍎❌]](https://hydra.nixos.org/build/243324366) [[🐧✅]](https://hydra.nixos.org/build/243326632) [haskellPackages.pipes-zlib](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.pipes-zlib)  ⤴️ 0 | 5
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241442778) [[📱✅]](https://hydra.nixos.org/build/241442951) [[🍎✅]](https://hydra.nixos.org/build/241422492) [[🐧✅]](https://hydra.nixos.org/build/241423736) [haskellPackages.rdtsc](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.rdtsc)  ⤴️ 0 | 4
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241438179) [[📱✅]](https://hydra.nixos.org/build/241429641) [[🍎❌]](https://hydra.nixos.org/build/241415985) [[🐧✅]](https://hydra.nixos.org/build/241418547) [haskellPackages.error-codes](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.error-codes)  ⤴️ 0 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243324043) [[📱✅]](https://hydra.nixos.org/build/243331033) [[🍎✅]](https://hydra.nixos.org/build/243331332) [[🐧✅]](https://hydra.nixos.org/build/243328838) [haskellPackages.folds](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.folds)  ⤴️ 0 | 3
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241440222) [[📱❌]](https://hydra.nixos.org/build/241423981) [[🍎✅]](https://hydra.nixos.org/build/241424884) [[🐧✅]](https://hydra.nixos.org/build/241420802) [haskellPackages.picosat](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.picosat)  ⤴️ 0 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241418237) [[📱✅]](https://hydra.nixos.org/build/241427188) [[🍎✅]](https://hydra.nixos.org/build/241434604) [[🐧✅]](https://hydra.nixos.org/build/241420057) [haskellPackages.LibZip](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.LibZip)  ⤴️ 0 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243333488) [[📱❌]](https://hydra.nixos.org/build/243331127) [[🍎✅]](https://hydra.nixos.org/build/243321804) [[🐧✅]](https://hydra.nixos.org/build/243329355) [haskellPackages.amazonka-cloudwatch](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.amazonka-cloudwatch)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241418292) [[📱✅]](https://hydra.nixos.org/build/241419411) [[🍎✅]](https://hydra.nixos.org/build/241422539) [[🐧✅]](https://hydra.nixos.org/build/241416430) [haskellPackages.bindings-levmar](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.bindings-levmar)  ⤴️ 0 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243323288) [[📱❗]](https://hydra.nixos.org/build/243331557) [[🍎❗]](https://hydra.nixos.org/build/243322898) [[🐧❌]](https://hydra.nixos.org/build/243332834) [haskellPackages.haskoin-node](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.haskoin-node)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241424091) [[📱✅]](https://hydra.nixos.org/build/241441753) [[🍎✅]](https://hydra.nixos.org/build/241427201) [[🐧✅]](https://hydra.nixos.org/build/241431703) [haskellPackages.rocksdb-haskell](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.rocksdb-haskell)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243329834) [[📱✅]](https://hydra.nixos.org/build/243330799) [[🍎❌]](https://hydra.nixos.org/build/243323285) [[🐧✅]](https://hydra.nixos.org/build/243324229) [haskellPackages.HsHTSLib](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.HsHTSLib)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243327505) [[📱✅]](https://hydra.nixos.org/build/243324973) [[🍎❌]](https://hydra.nixos.org/build/243322138) [[🐧✅]](https://hydra.nixos.org/build/243333395) [haskellPackages.diagrams-html5](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.diagrams-html5)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241433161) [[📱✅]](https://hydra.nixos.org/build/241435823) [[🍎❌]](https://hydra.nixos.org/build/241431240) [[🐧✅]](https://hydra.nixos.org/build/241438068) [haskellPackages.hamid](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hamid)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/241419089) [[📱✅]](https://hydra.nixos.org/build/241419403) [[🍎❌]](https://hydra.nixos.org/build/241439309) [[🐧✅]](https://hydra.nixos.org/build/241417021) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hmatrix-morpheus)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241416500) [[📱✅]](https://hydra.nixos.org/build/241439140) [[🍎❌]](https://hydra.nixos.org/build/241438868) [[🐧✅]](https://hydra.nixos.org/build/241442519) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.huckleberry)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243324009) [[📱✅]](https://hydra.nixos.org/build/243329357) [[🍎❌]](https://hydra.nixos.org/build/243329922) [[🐧✅]](https://hydra.nixos.org/build/243333570) [haskellPackages.om-time](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.om-time)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241440620) [[📱✅]](https://hydra.nixos.org/build/241421630) [[🍎❌]](https://hydra.nixos.org/build/241423658) [[🐧✅]](https://hydra.nixos.org/build/241418654) [haskellPackages.select](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.select)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241417977) [[📱✅]](https://hydra.nixos.org/build/241425056) [[🍎❌]](https://hydra.nixos.org/build/241422318) [[🐧✅]](https://hydra.nixos.org/build/241441219) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.sysinfo)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/241425934) [[📱✅]](https://hydra.nixos.org/build/241421265) [[🍎❌]](https://hydra.nixos.org/build/241429773) [[🐧✅]](https://hydra.nixos.org/build/241442363) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.FractalArt) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/241417489) [[📱❌]](https://hydra.nixos.org/build/241429480) [[🍎✅]](https://hydra.nixos.org/build/241440563) [[🐧✅]](https://hydra.nixos.org/build/241421892) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.HsASA) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241441209) [[📱✅]](https://hydra.nixos.org/build/242598214) [[🍎❌]](https://hydra.nixos.org/build/241431358) [[🐧✅]](https://hydra.nixos.org/build/242598119) [haskellPackages.al](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.al) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243322130) [[📱❌]](https://hydra.nixos.org/build/243322177) [[🍎✅]](https://hydra.nixos.org/build/243331780) [[🐧✅]](https://hydra.nixos.org/build/243326796) [haskellPackages.amazonka-docdb-elastic](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.amazonka-docdb-elastic) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243323405) [[📱❌]](https://hydra.nixos.org/build/243322826) [[🍎✅]](https://hydra.nixos.org/build/243328653) [[🐧✅]](https://hydra.nixos.org/build/243332874) [haskellPackages.amazonka-pinpoint-sms-voice-v2](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.amazonka-pinpoint-sms-voice-v2) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243326039) [[📱❌]](https://hydra.nixos.org/build/243327080) [[🍎❌]](https://hydra.nixos.org/build/243325997) [[🐧❌]](https://hydra.nixos.org/build/243328710) [haskellPackages.corenlp-types](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.corenlp-types) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241419848) [[📱✅]](https://hydra.nixos.org/build/241433182) [[🍎❌]](https://hydra.nixos.org/build/241433676) [[🐧✅]](https://hydra.nixos.org/build/241426445) [haskellPackages.env-extra](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.env-extra) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241421294) [[📱✅]](https://hydra.nixos.org/build/241443056) [[🍎❌]](https://hydra.nixos.org/build/241437354) [[🐧✅]](https://hydra.nixos.org/build/241417207) [haskellPackages.epub-metadata](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.epub-metadata) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241441889) [[📱✅]](https://hydra.nixos.org/build/241422082) [[🍎✅]](https://hydra.nixos.org/build/241430037) [[🐧✅]](https://hydra.nixos.org/build/241424436) [haskellPackages.executable-hash](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.executable-hash) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243326087) [[📱✅]](https://hydra.nixos.org/build/243331402) [[🍎❌]](https://hydra.nixos.org/build/243321006) [[🐧✅]](https://hydra.nixos.org/build/243333028) [haskellPackages.exinst-base](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.exinst-base) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241421569) [[📱✅]](https://hydra.nixos.org/build/241418686) [[🍎❌]](https://hydra.nixos.org/build/241417042) [[🐧✅]](https://hydra.nixos.org/build/241442695) [haskellPackages.float128](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.float128) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241433923) [[📱✅]](https://hydra.nixos.org/build/241432807) [[🍎❌]](https://hydra.nixos.org/build/241432286) [[🐧✅]](https://hydra.nixos.org/build/241434752) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.fudgets) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243327334) [[📱✅]](https://hydra.nixos.org/build/243331965) [[🍎❌]](https://hydra.nixos.org/build/243322858) [[🐧✅]](https://hydra.nixos.org/build/243328999) [haskellPackages.genvalidity-dirforest](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.genvalidity-dirforest) 
- [ ] [ghc-tags](https://hydra.nixos.org/eval/1802777?filter=ghc-tags) 
  - [[🍏✅]](https://hydra.nixos.org/build/243322909) [[📱✅]](https://hydra.nixos.org/build/243324145) [[🍎✅]](https://hydra.nixos.org/build/243332339) [[🐧✅]](https://hydra.nixos.org/build/243327180) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc8107.ghc-tags)
  - [[🍏❌]](https://hydra.nixos.org/build/243323053) [[📱❌]](https://hydra.nixos.org/build/243326676) [[🍎❌]](https://hydra.nixos.org/build/243323545) [[🐧❌]](https://hydra.nixos.org/build/243325393) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc902.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/243322183) [[📱✅]](https://hydra.nixos.org/build/243331350) [[🍎✅]](https://hydra.nixos.org/build/243329729) [[🐧✅]](https://hydra.nixos.org/build/243322698) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc924.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/243327812) [[📱✅]](https://hydra.nixos.org/build/243331969) [[🍎✅]](https://hydra.nixos.org/build/243325744) [[🐧✅]](https://hydra.nixos.org/build/243321107) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc925.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/243328915) [[📱✅]](https://hydra.nixos.org/build/243327414) [[🍎✅]](https://hydra.nixos.org/build/243323430) [[🐧✅]](https://hydra.nixos.org/build/243330127) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc926.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/243327524) [[📱✅]](https://hydra.nixos.org/build/243326657) [[🍎✅]](https://hydra.nixos.org/build/243324948) [[🐧✅]](https://hydra.nixos.org/build/243322593) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc927.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/243321726) [[📱✅]](https://hydra.nixos.org/build/243332312) [[🍎✅]](https://hydra.nixos.org/build/243326001) [[🐧✅]](https://hydra.nixos.org/build/243325087) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc928.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/243383513) [[📱✅]](https://hydra.nixos.org/build/243383505) [[🍎✅]](https://hydra.nixos.org/build/243383501) [[🐧✅]](https://hydra.nixos.org/build/243383507) [haskell.packages.ghc962](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc962.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/243383510) [[📱✅]](https://hydra.nixos.org/build/243383504) [[🍎✅]](https://hydra.nixos.org/build/243383503) [[🐧✅]](https://hydra.nixos.org/build/243383515) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc963.ghc-tags)
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243323294) [[🍎❌]](https://hydra.nixos.org/build/243330108) [haskellPackages.gi-gtkosxapplication](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gi-gtkosxapplication) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241834002) [[🍎❌]](https://hydra.nixos.org/build/241834248) [haskellPackages.gtk-mac-integration](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gtk-mac-integration) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241834305) [[📱✅]](https://hydra.nixos.org/build/242598417) [[🍎❌]](https://hydra.nixos.org/build/241834212) [[🐧✅]](https://hydra.nixos.org/build/242598116) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gtk-traymanager) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241834057) [[🍎❌]](https://hydra.nixos.org/build/241834287) [haskellPackages.gtk3-mac-integration](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.gtk3-mac-integration) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243321823) [[📱✅]](https://hydra.nixos.org/build/243331094) [[🍎❌]](https://hydra.nixos.org/build/243326882) [[🐧✅]](https://hydra.nixos.org/build/243329993) [haskellPackages.hdf5-lite](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hdf5-lite) 
- [ ] [hello](https://hydra.nixos.org/eval/1802777?filter=hello) 
  - [[🍏✅]](https://hydra.nixos.org/build/241438012) [[📱✅]](https://hydra.nixos.org/build/241431015) [[🍎✅]](https://hydra.nixos.org/build/241421144) [[🐧✅]](https://hydra.nixos.org/build/241418202) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hello)
  - [[🍏❌]](https://hydra.nixos.org/build/243659302)  [[🍎❌]](https://hydra.nixos.org/build/243659298) [[🐧❌]](https://hydra.nixos.org/build/243659301) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1802777?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.hello)
  - [[🍏❌]](https://hydra.nixos.org/build/243659306)  [[🍎❌]](https://hydra.nixos.org/build/243659300) [[🐧❌]](https://hydra.nixos.org/build/243659307) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1802777?filter=pkgsCross.ghcjs.haskellPackages.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/241436295) [pkgsMusl.haskellPackages](https://hydra.nixos.org/eval/1802777?filter=pkgsMusl.haskellPackages.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/243092436) [pkgsStatic.haskell.packages.native-bignum.ghc928](https://hydra.nixos.org/eval/1802777?filter=pkgsStatic.haskell.packages.native-bignum.ghc928.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/243092351) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1802777?filter=pkgsStatic.haskellPackages.hello)
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243326258) [[📱✅]](https://hydra.nixos.org/build/243325356) [[🍎❌]](https://hydra.nixos.org/build/243333044) [[🐧✅]](https://hydra.nixos.org/build/243323380) [haskellPackages.highlight](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.highlight) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243324679) [[📱✅]](https://hydra.nixos.org/build/243323150) [[🍎❌]](https://hydra.nixos.org/build/243322754) [[🐧✅]](https://hydra.nixos.org/build/243333479) [haskellPackages.hinotify-conduit](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hinotify-conduit) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243328968) [[📱❌]](https://hydra.nixos.org/build/243324202) [[🍎✅]](https://hydra.nixos.org/build/243322442) [[🐧✅]](https://hydra.nixos.org/build/243324286) [haskellPackages.hssh](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hssh) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241433357) [[📱✅]](https://hydra.nixos.org/build/241422478) [[🍎❌]](https://hydra.nixos.org/build/241439670) [[🐧✅]](https://hydra.nixos.org/build/241426451) [haskellPackages.hssourceinfo](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hssourceinfo) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241429271) [[📱✅]](https://hydra.nixos.org/build/241429102) [[🍎❌]](https://hydra.nixos.org/build/241440714) [[🐧✅]](https://hydra.nixos.org/build/241431783) [haskellPackages.hunspell-hs](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hunspell-hs) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243326679) [[📱✅]](https://hydra.nixos.org/build/243322171) [[🍎❌]](https://hydra.nixos.org/build/243320919) [[🐧✅]](https://hydra.nixos.org/build/243330907) [haskellPackages.immortal-queue](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.immortal-queue) 
- [ ] [[🍎❌]](https://hydra.nixos.org/build/243322867) [[🐧✅]](https://hydra.nixos.org/build/243333152) [haskellPackages.inline-asm](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.inline-asm) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243326703) [[📱✅]](https://hydra.nixos.org/build/243322882) [[🍎❌]](https://hydra.nixos.org/build/243332688) [[🐧✅]](https://hydra.nixos.org/build/243333225) [haskellPackages.interprocess](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.interprocess) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241440437) [[📱✅]](https://hydra.nixos.org/build/241416853) [[🍎❌]](https://hydra.nixos.org/build/241435524) [[🐧✅]](https://hydra.nixos.org/build/241442391) [haskellPackages.ipcvar](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.ipcvar) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243333585) [[📱✅]](https://hydra.nixos.org/build/243323631) [[🍎❌]](https://hydra.nixos.org/build/243326003) [[🐧✅]](https://hydra.nixos.org/build/243324444) [haskellPackages.kmonad](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.kmonad) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241429431) [[🍎❌]](https://hydra.nixos.org/build/241417265) [haskellPackages.kqueue](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.kqueue) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241422836) [[📱✅]](https://hydra.nixos.org/build/241425612) [[🍎✅]](https://hydra.nixos.org/build/241418129) [[🐧✅]](https://hydra.nixos.org/build/241434961) [haskellPackages.leveldb-haskell-fork](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.leveldb-haskell-fork) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243323682) [[📱✅]](https://hydra.nixos.org/build/243326016) [[🍎❌]](https://hydra.nixos.org/build/243328832) [[🐧✅]](https://hydra.nixos.org/build/243329324) [haskellPackages.linear-tests](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.linear-tests) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241435359) [[📱✅]](https://hydra.nixos.org/build/241427643) [[🍎❌]](https://hydra.nixos.org/build/241416796) [[🐧✅]](https://hydra.nixos.org/build/241435206) [haskellPackages.linux-framebuffer](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.linux-framebuffer) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243328956) [[📱✅]](https://hydra.nixos.org/build/243329182) [[🍎❌]](https://hydra.nixos.org/build/243326639) [[🐧✅]](https://hydra.nixos.org/build/243322613) [haskellPackages.mediawiki2latex](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.mediawiki2latex) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241432454) [[📱✅]](https://hydra.nixos.org/build/241434456) [[🍎❌]](https://hydra.nixos.org/build/241441382) [[🐧✅]](https://hydra.nixos.org/build/241435665) [haskellPackages.memzero](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.memzero) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243324149) [[📱❌]](https://hydra.nixos.org/build/243332531) [[🍎❌]](https://hydra.nixos.org/build/243333070) [[🐧❌]](https://hydra.nixos.org/build/243325450) [haskellPackages.om-plugin-imports](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.om-plugin-imports) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243326373) [[📱✅]](https://hydra.nixos.org/build/243329943) [[🍎❌]](https://hydra.nixos.org/build/243331397) [[🐧✅]](https://hydra.nixos.org/build/243322010) [haskellPackages.persistent-pagination](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.persistent-pagination) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243332592) [[📱✅]](https://hydra.nixos.org/build/243332670) [[🍎❌]](https://hydra.nixos.org/build/243322768) [[🐧✅]](https://hydra.nixos.org/build/243330118) [haskellPackages.phatsort](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.phatsort) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243324389) [[📱✅]](https://hydra.nixos.org/build/243333391) [[🍎❌]](https://hydra.nixos.org/build/243330131) [[🐧✅]](https://hydra.nixos.org/build/243330312) [haskellPackages.ping-wrapper](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.ping-wrapper) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241437112) [[📱✅]](https://hydra.nixos.org/build/241433414) [[🍎❌]](https://hydra.nixos.org/build/241438397) [[🐧✅]](https://hydra.nixos.org/build/241416503) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.posix-timer) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243323798) [[📱✅]](https://hydra.nixos.org/build/243321001) [[🍎❌]](https://hydra.nixos.org/build/243320837) [[🐧✅]](https://hydra.nixos.org/build/243326484) [haskellPackages.procex](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.procex) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241430897) [[📱✅]](https://hydra.nixos.org/build/241435590) [[🍎❌]](https://hydra.nixos.org/build/241418528) [[🐧✅]](https://hydra.nixos.org/build/241424149) [haskellPackages.pthread](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.pthread) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241439769) [[📱✅]](https://hydra.nixos.org/build/241438231) [[🍎✅]](https://hydra.nixos.org/build/241441302) [[🐧✅]](https://hydra.nixos.org/build/241420720) [haskellPackages.rdtsc-enolan](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.rdtsc-enolan) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243321032) [[📱✅]](https://hydra.nixos.org/build/243332474) [[🍎❌]](https://hydra.nixos.org/build/243325919) [[🐧✅]](https://hydra.nixos.org/build/243325516) [haskellPackages.sandwich-webdriver](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.sandwich-webdriver) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243322918) [[📱❌]](https://hydra.nixos.org/build/243322149) [[🍎❌]](https://hydra.nixos.org/build/243323962) [[🐧❌]](https://hydra.nixos.org/build/243329116) [haskellPackages.servant-xml-conduit](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.servant-xml-conduit) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241419022) [[📱✅]](https://hydra.nixos.org/build/241439147) [[🍎❌]](https://hydra.nixos.org/build/241419957) [[🐧✅]](https://hydra.nixos.org/build/241425481) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.shared-memory) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243332824) [[📱✅]](https://hydra.nixos.org/build/243329004) [[🍎✅]](https://hydra.nixos.org/build/243327264) [[🐧✅]](https://hydra.nixos.org/build/243332536) [haskellPackages.significant-figures](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.significant-figures) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/241417589) [[📱❌]](https://hydra.nixos.org/build/241433650) [[🍎✅]](https://hydra.nixos.org/build/241424588) [[🐧✅]](https://hydra.nixos.org/build/241426329) [haskellPackages.simdutf](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.simdutf) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243325303) [[📱❌]](https://hydra.nixos.org/build/243329304) [[🍎✅]](https://hydra.nixos.org/build/243329633) [[🐧✅]](https://hydra.nixos.org/build/243330495) [haskellPackages.sqlite-easy](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.sqlite-easy) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243322647) [[📱✅]](https://hydra.nixos.org/build/243329114) [[🍎❌]](https://hydra.nixos.org/build/243324054) [[🐧✅]](https://hydra.nixos.org/build/243322724) [haskellPackages.tailfile-hinotify](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.tailfile-hinotify) 
- [ ] [[📱❌]](https://hydra.nixos.org/build/241420222) [[🐧✅]](https://hydra.nixos.org/build/241433966) [haskellPackages.tasty-papi](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.tasty-papi) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243488793) [[📱❌]](https://hydra.nixos.org/build/243488769) [[🍎❌]](https://hydra.nixos.org/build/243488799) [[🐧❌]](https://hydra.nixos.org/build/243488790) [haskellPackages.temporal-csound](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.temporal-csound) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241416717) [[📱✅]](https://hydra.nixos.org/build/241442224) [[🍎✅]](https://hydra.nixos.org/build/241424811) [[🐧✅]](https://hydra.nixos.org/build/241434672) [haskellPackages.unix-simple](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.unix-simple) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/243321243) [[📱❌]](https://hydra.nixos.org/build/243329059) [[🍎❌]](https://hydra.nixos.org/build/243331948) [[🐧❌]](https://hydra.nixos.org/build/243331770) [haskellPackages.web-view](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.web-view) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241423452) [[📱❌]](https://hydra.nixos.org/build/241427685) [[🍎✅]](https://hydra.nixos.org/build/241416979) [[🐧✅]](https://hydra.nixos.org/build/241432721) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.x86-64bit) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241430363) [[📱✅]](https://hydra.nixos.org/build/241427221) [[🍎❌]](https://hydra.nixos.org/build/241432782) [[🐧✅]](https://hydra.nixos.org/build/241417328) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.xmonad-utils) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241422224) [[📱✅]](https://hydra.nixos.org/build/241433828) [[🍎❌]](https://hydra.nixos.org/build/241418484) [[🐧✅]](https://hydra.nixos.org/build/241439133) [haskellPackages.yoga](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.yoga) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241434291) [[📱✅]](https://hydra.nixos.org/build/241424397) [[🍎❌]](https://hydra.nixos.org/build/241427867) [[🐧✅]](https://hydra.nixos.org/build/241425578) [haskellPackages.zot](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.zot) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/241417248) [[📱✅]](https://hydra.nixos.org/build/241425967) [[🍎❌]](https://hydra.nixos.org/build/241419950) [[🐧✅]](https://hydra.nixos.org/build/241419853) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>56 job(s) </summary>

- [ ] [[🍏❗]](https://hydra.nixos.org/build/241431440) [[📱✅]](https://hydra.nixos.org/build/241432705) [[🍎❗]](https://hydra.nixos.org/build/241428544) [[🐧✅]](https://hydra.nixos.org/build/241423940) [haskellPackages.di-handle](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.di-handle)  ⤴️ 5 | 9
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243330380) [[📱✅]](https://hydra.nixos.org/build/243327073) [[🍎✅]](https://hydra.nixos.org/build/243332349) [[🐧✅]](https://hydra.nixos.org/build/243329048) [haskellPackages.di-monad](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.di-monad)  ⤴️ 5 | 9
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243328431) [[📱✅]](https://hydra.nixos.org/build/243325802) [[🍎✅]](https://hydra.nixos.org/build/243328210) [[🐧✅]](https://hydra.nixos.org/build/243328181) [haskellPackages.di-df1](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.di-df1)  ⤴️ 4 | 8
- [ ] [hoogle](https://hydra.nixos.org/eval/1802777?filter=hoogle)  ⤴️ 2 | 4
  - [[🍏✅]](https://hydra.nixos.org/build/243634652) [[📱✅]](https://hydra.nixos.org/build/243634646) [[🍎✅]](https://hydra.nixos.org/build/243634640) [[🐧✅]](https://hydra.nixos.org/build/243634677) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc8107.hoogle)
  - [[🍏❗]](https://hydra.nixos.org/build/243634683) [[📱✅]](https://hydra.nixos.org/build/243634694) [[🍎✅]](https://hydra.nixos.org/build/243634645) [[🐧✅]](https://hydra.nixos.org/build/243634682) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc902.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243329713) [[📱✅]](https://hydra.nixos.org/build/243330478) [[🍎✅]](https://hydra.nixos.org/build/243333020) [[🐧✅]](https://hydra.nixos.org/build/243332169) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc924.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243329602) [[📱✅]](https://hydra.nixos.org/build/243326327) [[🍎✅]](https://hydra.nixos.org/build/243322569) [[🐧✅]](https://hydra.nixos.org/build/243324936) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc925.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243324773) [[📱✅]](https://hydra.nixos.org/build/243324240) [[🍎✅]](https://hydra.nixos.org/build/243331355) [[🐧✅]](https://hydra.nixos.org/build/243321976) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc926.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243323335) [[📱✅]](https://hydra.nixos.org/build/243332955) [[🍎✅]](https://hydra.nixos.org/build/243324752) [[🐧✅]](https://hydra.nixos.org/build/243330433) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc927.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243324099) [[📱✅]](https://hydra.nixos.org/build/243322157) [[🍎✅]](https://hydra.nixos.org/build/243322508) [[🐧✅]](https://hydra.nixos.org/build/243329393) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc928.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243323619) [[📱✅]](https://hydra.nixos.org/build/243330680) [[🍎✅]](https://hydra.nixos.org/build/243327110) [[🐧✅]](https://hydra.nixos.org/build/243329005) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc945.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243333066) [[📱✅]](https://hydra.nixos.org/build/243326255) [[🍎✅]](https://hydra.nixos.org/build/243320945) [[🐧✅]](https://hydra.nixos.org/build/243320884) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc946.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243327356) [[📱✅]](https://hydra.nixos.org/build/243326209) [[🍎✅]](https://hydra.nixos.org/build/243333380) [[🐧✅]](https://hydra.nixos.org/build/243332817) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1802777?filter=haskell.packages.ghc947.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/243323812) [[📱✅]](https://hydra.nixos.org/build/243323065) [[🍎✅]](https://hydra.nixos.org/build/243333595) [[🐧✅]](https://hydra.nixos.org/build/243322692) [haskellPackages](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hoogle)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241438185) [[📱✅]](https://hydra.nixos.org/build/241425241) [[🍎❗]](https://hydra.nixos.org/build/241428644) [[🐧✅]](https://hydra.nixos.org/build/241430830) [haskellPackages.numeric-optimization](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.numeric-optimization)  ⤴️ 2 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243333563) [[📱✅]](https://hydra.nixos.org/build/243325474) [[🍎❗]](https://hydra.nixos.org/build/243333313) [[🐧✅]](https://hydra.nixos.org/build/243331463) [haskellPackages.nyan-interpolation-core](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.nyan-interpolation-core)  ⤴️ 2 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243328558) [[📱❗]](https://hydra.nixos.org/build/243328702) [[🍎✅]](https://hydra.nixos.org/build/243326268) [[🐧✅]](https://hydra.nixos.org/build/243332613) [haskellPackages.not-gloss](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.not-gloss)  ⤴️ 1 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243333312) [[📱✅]](https://hydra.nixos.org/build/243330563) [[🍎✅]](https://hydra.nixos.org/build/243324661) [[🐧✅]](https://hydra.nixos.org/build/243328778) [haskellPackages.moto](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.moto)  ⤴️ 1 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243327725) [[📱❗]](https://hydra.nixos.org/build/243327332) [[🍎❗]](https://hydra.nixos.org/build/243330840) [[🐧❗]](https://hydra.nixos.org/build/243329279) [haskellPackages.simple-cairo](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.simple-cairo)  ⤴️ 1 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243329887) [[📱❗]](https://hydra.nixos.org/build/243329843) [[🍎❗]](https://hydra.nixos.org/build/243329548) [[🐧❗]](https://hydra.nixos.org/build/243321839) [haskellPackages.waterfall-cad](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.waterfall-cad)  ⤴️ 1 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241442328) [[📱✅]](https://hydra.nixos.org/build/241435925) [[🍎❗]](https://hydra.nixos.org/build/241434139) [[🐧✅]](https://hydra.nixos.org/build/241418826) [haskellPackages.yaml-light](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.yaml-light)  ⤴️ 0 | 5
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243332738) [[📱✅]](https://hydra.nixos.org/build/243320804) [[🍎✅]](https://hydra.nixos.org/build/243327326) [[🐧✅]](https://hydra.nixos.org/build/243328628) [haskellPackages.di-polysemy](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.di-polysemy)  ⤴️ 0 | 4
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243320991) [[📱⌛🚫]](https://hydra.nixos.org/build/243328062) [[🍎✅]](https://hydra.nixos.org/build/243328749) [[🐧✅]](https://hydra.nixos.org/build/243326435) [haskellPackages.telegram-bot-simple](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.telegram-bot-simple)  ⤴️ 0 | 3
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243329797) [[📱✅]](https://hydra.nixos.org/build/243328836) [[🍎✅]](https://hydra.nixos.org/build/243331391) [[🐧✅]](https://hydra.nixos.org/build/243324222) [haskellPackages.di](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.di)  ⤴️ 0 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243333400) [[📱✅]](https://hydra.nixos.org/build/243321894) [[🍎❗]](https://hydra.nixos.org/build/243327152) [[🐧✅]](https://hydra.nixos.org/build/243331911) [haskellPackages.network-dns](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.network-dns)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243324906) [[📱✅]](https://hydra.nixos.org/build/243329115) [[🍎❗]](https://hydra.nixos.org/build/243321173) [[🐧✅]](https://hydra.nixos.org/build/243323770) [haskellPackages.render-utf8](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.render-utf8)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243333349) [[📱✅]](https://hydra.nixos.org/build/243329383) [[🍎❗]](https://hydra.nixos.org/build/243320915) [[🐧✅]](https://hydra.nixos.org/build/243331505) [haskellPackages.async-refresh-tokens](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.async-refresh-tokens) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243327462) [[📱✅]](https://hydra.nixos.org/build/243326824) [[🍎❗]](https://hydra.nixos.org/build/243321565) [[🐧✅]](https://hydra.nixos.org/build/243328698) [haskellPackages.cardano-coin-selection](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.cardano-coin-selection) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243325081) [[📱✅]](https://hydra.nixos.org/build/243321711) [[🍎❗]](https://hydra.nixos.org/build/243327395) [[🐧✅]](https://hydra.nixos.org/build/243333259) [haskellPackages.declarative](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.declarative) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241428462) [[📱✅]](https://hydra.nixos.org/build/241416184) [[🍎❗]](https://hydra.nixos.org/build/241437314) [[🐧✅]](https://hydra.nixos.org/build/241438237) [haskellPackages.discount](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.discount) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241439934) [[📱✅]](https://hydra.nixos.org/build/241424096) [[🍎❗]](https://hydra.nixos.org/build/241419594) [[🐧✅]](https://hydra.nixos.org/build/241423273) [haskellPackages.epub-tools](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.epub-tools) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243331454) [[📱✅]](https://hydra.nixos.org/build/243328922) [[🍎❗]](https://hydra.nixos.org/build/243327791) [[🐧✅]](https://hydra.nixos.org/build/243322116) [haskellPackages.exinst-aeson](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.exinst-aeson) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243322230) [[📱✅]](https://hydra.nixos.org/build/243323031) [[🍎❗]](https://hydra.nixos.org/build/243321000) [[🐧✅]](https://hydra.nixos.org/build/243324164) [haskellPackages.exinst-bytes](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.exinst-bytes) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243325244) [[📱✅]](https://hydra.nixos.org/build/243327654) [[🍎❗]](https://hydra.nixos.org/build/243326300) [[🐧✅]](https://hydra.nixos.org/build/243333197) [haskellPackages.exinst-cereal](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.exinst-cereal) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243327403) [[📱✅]](https://hydra.nixos.org/build/243324573) [[🍎❗]](https://hydra.nixos.org/build/243331890) [[🐧✅]](https://hydra.nixos.org/build/243320953) [haskellPackages.exinst-serialise](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.exinst-serialise) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243326704) [[📱✅]](https://hydra.nixos.org/build/243328742) [[🍎❗]](https://hydra.nixos.org/build/243333482) [[🐧✅]](https://hydra.nixos.org/build/243326767) [haskellPackages.fmt-terminal-colors](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.fmt-terminal-colors) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241418690) [[📱✅]](https://hydra.nixos.org/build/241439924) [[🍎❗]](https://hydra.nixos.org/build/241425232) [[🐧✅]](https://hydra.nixos.org/build/241422510) [haskellPackages.foma](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.foma) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243324438) [[📱✅]](https://hydra.nixos.org/build/243329262) [[🍎✅]](https://hydra.nixos.org/build/243331144) [[🐧✅]](https://hydra.nixos.org/build/243321735) [haskellPackages.hasql-th](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hasql-th) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241430628) [[📱❗]](https://hydra.nixos.org/build/241435255) [[🍎✅]](https://hydra.nixos.org/build/241423824) [[🐧✅]](https://hydra.nixos.org/build/241430197) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241427292) [[📱✅]](https://hydra.nixos.org/build/241417273) [[🍎❗]](https://hydra.nixos.org/build/241433162) [[🐧✅]](https://hydra.nixos.org/build/241431038) [haskellPackages.hmatrix-quadprogpp](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hmatrix-quadprogpp) 
- [ ] [[🍎❗]](https://hydra.nixos.org/build/243330744) [[🐧✅]](https://hydra.nixos.org/build/243324552) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241443245) [[📱✅]](https://hydra.nixos.org/build/241438080) [[🍎❗]](https://hydra.nixos.org/build/241421838) [[🐧✅]](https://hydra.nixos.org/build/241428748) [haskellPackages.intel-powermon](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.intel-powermon) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243325712) [[📱❗]](https://hydra.nixos.org/build/243322090) [[🍎✅]](https://hydra.nixos.org/build/243323781) [[🐧✅]](https://hydra.nixos.org/build/243333532) [haskellPackages.learn-physics](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.learn-physics) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243330904) [[📱✅]](https://hydra.nixos.org/build/243326397) [[🍎✅]](https://hydra.nixos.org/build/243325072) [[🐧✅]](https://hydra.nixos.org/build/243328192) [haskellPackages.moto-postgresql](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.moto-postgresql) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/243322940) [[📱❗]](https://hydra.nixos.org/build/243331013) [[🍎✅]](https://hydra.nixos.org/build/243326038) [[🐧✅]](https://hydra.nixos.org/build/243331718) [haskellPackages.not-gloss-examples](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.not-gloss-examples) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241524664) [[📱✅]](https://hydra.nixos.org/build/241517036) [[🍎❗]](https://hydra.nixos.org/build/241525297) [[🐧✅]](https://hydra.nixos.org/build/241515505) [haskellPackages.numeric-optimization-ad](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.numeric-optimization-ad) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243322176) [[📱✅]](https://hydra.nixos.org/build/243321854) [[🍎❗]](https://hydra.nixos.org/build/243333293) [[🐧✅]](https://hydra.nixos.org/build/243322136) [haskellPackages.numeric-optimization-backprop](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.numeric-optimization-backprop) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243320781) [[📱✅]](https://hydra.nixos.org/build/243325889) [[🍎❗]](https://hydra.nixos.org/build/243331892) [[🐧✅]](https://hydra.nixos.org/build/243323663) [haskellPackages.nyan-interpolation](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.nyan-interpolation) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243328925) [[📱✅]](https://hydra.nixos.org/build/243331345) [[🍎❗]](https://hydra.nixos.org/build/243333034) [[🐧✅]](https://hydra.nixos.org/build/243332797) [haskellPackages.nyan-interpolation-simple](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.nyan-interpolation-simple) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243327937) [[📱✅]](https://hydra.nixos.org/build/243322478) [[🍎❗]](https://hydra.nixos.org/build/243320782) [[🐧✅]](https://hydra.nixos.org/build/243329204) [haskellPackages.quickcheck-quid](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.quickcheck-quid) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243332457) [[📱✅]](https://hydra.nixos.org/build/243332629) [[🍎❗]](https://hydra.nixos.org/build/243329568) [[🐧✅]](https://hydra.nixos.org/build/243328306) [haskellPackages.rg](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.rg) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243321058) [[📱❗]](https://hydra.nixos.org/build/243327051) [[🍎❗]](https://hydra.nixos.org/build/243333566) [[🐧❗]](https://hydra.nixos.org/build/243331488) [haskellPackages.simple-pango](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.simple-pango) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243332372) [[📱✅]](https://hydra.nixos.org/build/243325715) [[🍎❗]](https://hydra.nixos.org/build/243331851) [[🐧✅]](https://hydra.nixos.org/build/243333155) [haskellPackages.sym-plot](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.sym-plot) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/243328935) [[📱❗]](https://hydra.nixos.org/build/243321546) [[🍎❗]](https://hydra.nixos.org/build/243322764) [[🐧❗]](https://hydra.nixos.org/build/243326077) [haskellPackages.waterfall-cad-examples](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.waterfall-cad-examples) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/241441990) [[📱✅]](https://hydra.nixos.org/build/241420188) [[🍎❗]](https://hydra.nixos.org/build/241434444) [[🐧✅]](https://hydra.nixos.org/build/241422896) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1802777?filter=haskellPackages.xbattbar) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) ⤴️ 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) ⤴️ 152  
[heist](https://packdeps.haskellers.com/reverse/heist) ⤴️ 72  
[snap](https://packdeps.haskellers.com/reverse/snap) ⤴️ 63  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) ⤴️ 56  
[util](https://packdeps.haskellers.com/reverse/util) ⤴️ 49  
[derive](https://packdeps.haskellers.com/reverse/derive) ⤴️ 48  
[repa](https://packdeps.haskellers.com/reverse/repa) ⤴️ 45  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) ⤴️ 42  
[syb-with-class](https://packdeps.haskellers.com/reverse/syb-with-class) ⤴️ 42  
[TypeCompose](https://packdeps.haskellers.com/reverse/TypeCompose) ⤴️ 38  
[PrimitiveArray](https://packdeps.haskellers.com/reverse/PrimitiveArray) ⤴️ 35  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) ⤴️ 33  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) ⤴️ 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) ⤴️ 30  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) ⤴️ 29  
[polysemy-time](https://packdeps.haskellers.com/reverse/polysemy-time) ⤴️ 28  
[polysemy-resume](https://packdeps.haskellers.com/reverse/polysemy-resume) ⤴️ 27  
[polysemy-conc](https://packdeps.haskellers.com/reverse/polysemy-conc) ⤴️ 26  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) ⤴️ 25  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) ⤴️ 25  
[HList](https://packdeps.haskellers.com/reverse/HList) ⤴️ 24  
[polysemy-log](https://packdeps.haskellers.com/reverse/polysemy-log) ⤴️ 24  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) ⤴️ 22  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) ⤴️ 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) ⤴️ 22  
[BiobaseTypes](https://packdeps.haskellers.com/reverse/BiobaseTypes) ⤴️ 21  
[alg](https://packdeps.haskellers.com/reverse/alg) ⤴️ 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) ⤴️ 21  
[userid](https://packdeps.haskellers.com/reverse/userid) ⤴️ 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) ⤴️ 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) ⤴️ 20  
[cheapskate](https://packdeps.haskellers.com/reverse/cheapskate) ⤴️ 20  
[openapi3](https://packdeps.haskellers.com/reverse/openapi3) ⤴️ 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) ⤴️ 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) ⤴️ 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) ⤴️ 19  
[fay](https://packdeps.haskellers.com/reverse/fay) ⤴️ 19  
[incipit](https://packdeps.haskellers.com/reverse/incipit) ⤴️ 19  
[ixset](https://packdeps.haskellers.com/reverse/ixset) ⤴️ 19  
[polysemy-chronos](https://packdeps.haskellers.com/reverse/polysemy-chronos) ⤴️ 19  
[wx](https://packdeps.haskellers.com/reverse/wx) ⤴️ 19  
[BiobaseENA](https://packdeps.haskellers.com/reverse/BiobaseENA) ⤴️ 18  
[asn1-data](https://packdeps.haskellers.com/reverse/asn1-data) ⤴️ 18  
[dbus-core](https://packdeps.haskellers.com/reverse/dbus-core) ⤴️ 18  
[digit](https://packdeps.haskellers.com/reverse/digit) ⤴️ 18  
[gtksourceview2](https://packdeps.haskellers.com/reverse/gtksourceview2) ⤴️ 18  
[polysemy-process](https://packdeps.haskellers.com/reverse/polysemy-process) ⤴️ 18  
[ukrainian-phonetics-basic](https://packdeps.haskellers.com/reverse/ukrainian-phonetics-basic) ⤴️ 18  
[BiobaseXNA](https://packdeps.haskellers.com/reverse/BiobaseXNA) ⤴️ 17  
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
