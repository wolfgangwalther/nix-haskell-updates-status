### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1808844](https://hydra.nixos.org/eval/1808844) of nixpkgs commit [b039994](https://github.com/NixOS/nixpkgs/commits/b039994dad3a4288dfdffe388cf97faf39240c5a) as of 2024-09-15 00:30 UTC*

🔴 **Branch not mergeable**
  * `mergeable` jobset failed.
  * `maintained` jobset failed.

#### Build summary

 | Platform | Failed ❌ | DependencyFailed ❗ | TimedOut ⌛🚫 | Unfinished ⏳ | Success ✅ | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-darwin 🍏](https://hydra.nixos.org/eval/1808844?filter=.aarch64-darwin) | 79 | 26 | 2 | 36 | 6411 | 
 | [aarch64-linux 📱](https://hydra.nixos.org/eval/1808844?filter=.aarch64-linux) | 31 | 41 | 2 | 7 | 6529 | 
 | [x86_64-darwin 🍎](https://hydra.nixos.org/eval/1808844?filter=.x86_64-darwin) | 71 | 34 | 4 | 6 | 6440 | 
 | [x86_64-linux 🐧](https://hydra.nixos.org/eval/1808844?filter=.x86_64-linux) | 21 | 8 | 1 | 8 | 6614 | 
#### Maintained Linux packages with build failure
- [ ] [dhall-docs](https://hydra.nixos.org/eval/1808844?filter=dhall-docs) @Gabriella439
  - [[📱❌]](https://hydra.nixos.org/build/272375399) [[🐧❌]](https://hydra.nixos.org/build/272386479) [toplevel](https://hydra.nixos.org/eval/1808844?filter=dhall-docs)
  - [[📱❌]](https://hydra.nixos.org/build/272369908) [[🐧❌]](https://hydra.nixos.org/build/272381297) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.dhall-docs)
- [ ] [[📱❌]](https://hydra.nixos.org/build/272385001) [[🐧❌]](https://hydra.nixos.org/build/272371936) [haskellPackages.dirstream](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.dirstream) @Gabriella439
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1808844?filter=haskell-language-server) @maralorn
  - [[📱❗]](https://hydra.nixos.org/build/272382589) [[🐧✅]](https://hydra.nixos.org/build/272370443) [toplevel](https://hydra.nixos.org/eval/1808844?filter=haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/272389096) [[🐧⏳]](https://hydra.nixos.org/build/272377057) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc925.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/272389330) [[🐧⏳]](https://hydra.nixos.org/build/272365388) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc926.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/272368652) [[🐧✅]](https://hydra.nixos.org/build/272388554) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc927.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/272379402) [[🐧✅]](https://hydra.nixos.org/build/272387405) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc928.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/272374910) [[🐧✅]](https://hydra.nixos.org/build/272386262) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc945.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/272384055) [[🐧✅]](https://hydra.nixos.org/build/272388488) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc946.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/272386239) [[🐧❌]](https://hydra.nixos.org/build/272389113) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc947.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/272385564) [[🐧✅]](https://hydra.nixos.org/build/272366355) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc948.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/272383424) [[🐧✅]](https://hydra.nixos.org/build/272377068) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc963.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/272385025) [[🐧✅]](https://hydra.nixos.org/build/272388498) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc964.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/272367863) [[🐧✅]](https://hydra.nixos.org/build/272387578) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc965.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/272383908) [[🐧✅]](https://hydra.nixos.org/build/272390036) [haskell.packages.ghc966](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc966.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/272365125) [[🐧✅]](https://hydra.nixos.org/build/272366210) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc981.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/272375550) [[🐧⏳]](https://hydra.nixos.org/build/272378237) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1808844?filter=haskell.packages.ghc982.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/272385225) [[🐧✅]](https://hydra.nixos.org/build/272373456) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.haskell-language-server)
#### Maintained Linux packages with failed dependency
- [ ] [[📱❗]](https://hydra.nixos.org/build/272373092) [[🐧✅]](https://hydra.nixos.org/build/272376857) [haskellPackages.candid](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.candid) @nomeata
- [ ] [[📱❗]](https://hydra.nixos.org/build/272571594) [[🐧✅]](https://hydra.nixos.org/build/272571621) [echidna](https://hydra.nixos.org/eval/1808844?filter=echidna) @arcz @hellwolf
- [ ] [[📱❗]](https://hydra.nixos.org/build/272363959) [[🐧✅]](https://hydra.nixos.org/build/272364894) [haskellPackages.espial](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.espial) @dalpd
- [ ] [gitit](https://hydra.nixos.org/eval/1808844?filter=gitit) @Profpatsch @sternenseemann
  - [[📱❗]](https://hydra.nixos.org/build/272373190) [[🐧✅]](https://hydra.nixos.org/build/272383845) [toplevel](https://hydra.nixos.org/eval/1808844?filter=gitit)
  - [[📱❗]](https://hydra.nixos.org/build/272386780) [[🐧✅]](https://hydra.nixos.org/build/272380375) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gitit)
- [ ] [[📱❗]](https://hydra.nixos.org/build/272571609) [[🐧✅]](https://hydra.nixos.org/build/272571616) [haskellPackages.hevm](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hevm) @arcz
- [ ] [hledger-web](https://hydra.nixos.org/eval/1808844?filter=hledger-web) @maralorn
  - [[📱❗]](https://hydra.nixos.org/build/272370558) [[🐧✅]](https://hydra.nixos.org/build/272372191) [toplevel](https://hydra.nixos.org/eval/1808844?filter=hledger-web)
  - [[📱❗]](https://hydra.nixos.org/build/272369982) [[🐧✅]](https://hydra.nixos.org/build/272367322) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hledger-web)
- [ ] [[📱❗]](https://hydra.nixos.org/build/272378713) [[🐧✅]](https://hydra.nixos.org/build/272388682) [haskellPackages.hledger-web_1_34](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hledger-web_1_34) @maralorn
- [ ] [[🐧❗]](https://hydra.nixos.org/build/272579784) [maintained](https://hydra.nixos.org/eval/1808844?filter=maintained) @cdepillabout @expipiplus1 @maralorn @ncfavier @sternenseemann
- [ ] [[📱❗]](https://hydra.nixos.org/build/272367396) [[🐧✅]](https://hydra.nixos.org/build/272378104) [haskellPackages.matrix-client](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.matrix-client) @maralorn
- [ ] [[🐧❗]](https://hydra.nixos.org/build/272615938) [mergeable](https://hydra.nixos.org/eval/1808844?filter=mergeable) @cdepillabout @expipiplus1 @maralorn @ncfavier @sternenseemann
- [ ] [[📱❗]](https://hydra.nixos.org/build/272386331) [[🐧✅]](https://hydra.nixos.org/build/272375747) [haskellPackages.unleash-client-haskell](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.unleash-client-haskell) @evenbrenden
- [ ] [[📱❗]](https://hydra.nixos.org/build/272384989) [[🐧✅]](https://hydra.nixos.org/build/272369496) [haskellPackages.unleash-client-haskell-core](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.unleash-client-haskell-core) @evenbrenden
#### Maintained Darwin packages with build failure
<details><summary>5 job(s) </summary>

- [ ] [dhall-docs](https://hydra.nixos.org/eval/1808844?filter=dhall-docs) @Gabriella439
  - [[🍏❌]](https://hydra.nixos.org/build/272388319) [[🍎❌]](https://hydra.nixos.org/build/272365822) [toplevel](https://hydra.nixos.org/eval/1808844?filter=dhall-docs)
  - [[🍏❌]](https://hydra.nixos.org/build/272383101) [[🍎❌]](https://hydra.nixos.org/build/272367550) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.dhall-docs)
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272382283) [[🍎❌]](https://hydra.nixos.org/build/272371740) [haskellPackages.dirstream](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.dirstream) @Gabriella439
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272160430) [[🍎❌]](https://hydra.nixos.org/build/272166239) [wstunnel](https://hydra.nixos.org/eval/1808844?filter=wstunnel) @NeverBehave @R-VdP
</details>

#### Unmaintained packages with build failure
<details><summary>91 job(s) </summary>

- [ ] [[🍏✅]](https://hydra.nixos.org/build/272389310) [[📱✅]](https://hydra.nixos.org/build/272363660) [[🍎❌]](https://hydra.nixos.org/build/272387429) [[🐧✅]](https://hydra.nixos.org/build/272363176) [haskellPackages.iconv](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.iconv)  ⤴️ 4 | 16
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272374819) [[📱✅]](https://hydra.nixos.org/build/272376020) [[🍎❌]](https://hydra.nixos.org/build/272381242) [[🐧✅]](https://hydra.nixos.org/build/272376256) [haskellPackages.llvm-tf](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.llvm-tf)  ⤴️ 3 | 6
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272369554) [[📱✅]](https://hydra.nixos.org/build/272389224) [[🍎❌]](https://hydra.nixos.org/build/272368028) [[🐧✅]](https://hydra.nixos.org/build/272362637) [haskellPackages.pipes-zlib](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.pipes-zlib)  ⤴️ 2 | 8
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272372173) [[📱✅]](https://hydra.nixos.org/build/272376626) [[🍎❌]](https://hydra.nixos.org/build/272386234) [[🐧✅]](https://hydra.nixos.org/build/272380705) [haskellPackages.lbfgs](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.lbfgs)  ⤴️ 2 | 3
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272365725) [[📱❌]](https://hydra.nixos.org/build/272364564) [[🍎✅]](https://hydra.nixos.org/build/272363862) [[🐧✅]](https://hydra.nixos.org/build/272387317) [haskellPackages.postgresql-syntax](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.postgresql-syntax)  ⤴️ 2 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272380400) [[📱✅]](https://hydra.nixos.org/build/272379007) [[🍎❌]](https://hydra.nixos.org/build/272373835) [[🐧✅]](https://hydra.nixos.org/build/272382857) [haskellPackages.HsSyck](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.HsSyck)  ⤴️ 1 | 10
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272372811) [[📱✅]](https://hydra.nixos.org/build/272390416) [[🍎❌]](https://hydra.nixos.org/build/272381913) [[🐧✅]](https://hydra.nixos.org/build/272372416) [haskellPackages.error-codes](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.error-codes)  ⤴️ 1 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272387132) [[📱❌]](https://hydra.nixos.org/build/272367488) [[🍎❌]](https://hydra.nixos.org/build/272370612) [[🐧❌]](https://hydra.nixos.org/build/272387706) [haskellPackages.anansi](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.anansi)  ⤴️ 1 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272380193) [[📱❌]](https://hydra.nixos.org/build/272365951) [[🍎✅]](https://hydra.nixos.org/build/272382317) [[🐧✅]](https://hydra.nixos.org/build/272362740) [haskellPackages.pcg-random](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.pcg-random)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272389683) [[📱✅]](https://hydra.nixos.org/build/272381011) [[🍎❌]](https://hydra.nixos.org/build/272377295) [[🐧✅]](https://hydra.nixos.org/build/272371037) [haskellPackages.posix-socket](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.posix-socket)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272376559) [[📱✅]](https://hydra.nixos.org/build/272384338) [[🍎❌]](https://hydra.nixos.org/build/272371406) [[🐧✅]](https://hydra.nixos.org/build/272371962) [haskellPackages.rawfilepath](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.rawfilepath)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272389019) [[📱✅]](https://hydra.nixos.org/build/272364476) [[🍎❌]](https://hydra.nixos.org/build/272371785) [[🐧✅]](https://hydra.nixos.org/build/272375829) [haskellPackages.gi-gdkx11](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gi-gdkx11)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272381389) [[📱❌]](https://hydra.nixos.org/build/272363015) [[🍎✅]](https://hydra.nixos.org/build/272387724) [[🐧✅]](https://hydra.nixos.org/build/272390583) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.nlopt-haskell)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272386191) [[📱✅]](https://hydra.nixos.org/build/272386176) [[🍎❌]](https://hydra.nixos.org/build/272380516) [[🐧✅]](https://hydra.nixos.org/build/272364240) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.openal-ffi)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272376585) [[📱❌]](https://hydra.nixos.org/build/272386383) [[🍎❌]](https://hydra.nixos.org/build/272389872) [[🐧❌]](https://hydra.nixos.org/build/272377763) [haskellPackages.si-timers](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.si-timers)  ⤴️ 1 | 1
- [ ] [[🍎❌]](https://hydra.nixos.org/build/272390008) [[🐧✅]](https://hydra.nixos.org/build/272382239) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.swisstable)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272384256) [[📱✅]](https://hydra.nixos.org/build/272380908) [[🍎❌]](https://hydra.nixos.org/build/272374983) [[🐧✅]](https://hydra.nixos.org/build/272378329) [haskellPackages.sym](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.sym)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272372837) [[📱✅]](https://hydra.nixos.org/build/272369987) [[🍎❌]](https://hydra.nixos.org/build/272385042) [[🐧✅]](https://hydra.nixos.org/build/272364948) [haskellPackages.libxml-sax](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.libxml-sax)  ⤴️ 0 | 21
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272390135) [[📱❌]](https://hydra.nixos.org/build/272378918) [[🍎✅]](https://hydra.nixos.org/build/272372419) [[🐧✅]](https://hydra.nixos.org/build/272378227) [haskellPackages.tdigest](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.tdigest)  ⤴️ 0 | 18
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272388569) [[📱❌]](https://hydra.nixos.org/build/272373050) [[🍎✅]](https://hydra.nixos.org/build/272389939) [[🐧✅]](https://hydra.nixos.org/build/272380524) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.freetype2)  ⤴️ 0 | 12
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272370987) [[📱❌]](https://hydra.nixos.org/build/272376666) [[🍎✅]](https://hydra.nixos.org/build/272375788) [[🐧✅]](https://hydra.nixos.org/build/272379269) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hw-simd)  ⤴️ 0 | 9
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272366989) [[📱✅]](https://hydra.nixos.org/build/272363413) [[🍎❌]](https://hydra.nixos.org/build/272388714) [[🐧✅]](https://hydra.nixos.org/build/272383999) [haskellPackages.bytestring-encoding](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.bytestring-encoding)  ⤴️ 0 | 6
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272364333) [[📱✅]](https://hydra.nixos.org/build/272384568) [[🍎✅]](https://hydra.nixos.org/build/272387939) [[🐧✅]](https://hydra.nixos.org/build/272369000) [haskellPackages.rdtsc](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.rdtsc)  ⤴️ 0 | 4
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272371661) [[📱✅]](https://hydra.nixos.org/build/272364326) [[🍎✅]](https://hydra.nixos.org/build/272390588) [[🐧✅]](https://hydra.nixos.org/build/272378607) [haskellPackages.folds](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.folds)  ⤴️ 0 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272368040) [[📱✅]](https://hydra.nixos.org/build/272370642) [[🍎✅]](https://hydra.nixos.org/build/272379987) [[🐧✅]](https://hydra.nixos.org/build/272385441) [haskellPackages.bindings-levmar](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.bindings-levmar)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272390422) [[📱✅]](https://hydra.nixos.org/build/272365138) [[🍎✅]](https://hydra.nixos.org/build/272382229) [[🐧✅]](https://hydra.nixos.org/build/272390640) [haskellPackages.rocksdb-haskell](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.rocksdb-haskell)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272373901) [[📱✅]](https://hydra.nixos.org/build/272385284) [[🍎❌]](https://hydra.nixos.org/build/272383105) [[🐧✅]](https://hydra.nixos.org/build/272365324) [haskellPackages.HsHTSLib](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.HsHTSLib)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272381096) [[📱❌]](https://hydra.nixos.org/build/272364365) [[🍎❌]](https://hydra.nixos.org/build/272389040) [[🐧✅]](https://hydra.nixos.org/build/272386268) [haskellPackages.dhscanner-ast](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.dhscanner-ast)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272388586) [[📱✅]](https://hydra.nixos.org/build/272380514) [[🍎❌]](https://hydra.nixos.org/build/272381878) [[🐧✅]](https://hydra.nixos.org/build/272387079) [haskellPackages.hamid](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hamid)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272389986) [[📱✅]](https://hydra.nixos.org/build/272385440) [[🍎❌]](https://hydra.nixos.org/build/272365481) [[🐧✅]](https://hydra.nixos.org/build/272369566) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hmatrix-morpheus)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272388928) [[📱✅]](https://hydra.nixos.org/build/272370846) [[🍎❌]](https://hydra.nixos.org/build/272377813) [[🐧✅]](https://hydra.nixos.org/build/272379865) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.huckleberry)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272384706) [[📱✅]](https://hydra.nixos.org/build/272390110) [[🍎❌]](https://hydra.nixos.org/build/272370111) [[🐧✅]](https://hydra.nixos.org/build/272367354) [haskellPackages.om-time](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.om-time)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272388524) [[📱❌]](https://hydra.nixos.org/build/272366302) [[🍎❌]](https://hydra.nixos.org/build/272382436) [[🐧❌]](https://hydra.nixos.org/build/272383053) [haskellPackages.propeller](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.propeller)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272389477) [[📱✅]](https://hydra.nixos.org/build/272373361) [[🍎❌]](https://hydra.nixos.org/build/272377669) [[🐧✅]](https://hydra.nixos.org/build/272364955) [haskellPackages.select](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.select)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272379050) [[📱❌]](https://hydra.nixos.org/build/272375051) [[🍎✅]](https://hydra.nixos.org/build/272371270) [[🐧✅]](https://hydra.nixos.org/build/272383217) [haskellPackages.simple-vec3](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.simple-vec3)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272368959) [[📱❌]](https://hydra.nixos.org/build/272374398) [[🍎❌]](https://hydra.nixos.org/build/272390604) [[🐧❌]](https://hydra.nixos.org/build/272377557) [haskellPackages.strict-stm](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.strict-stm)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272372844) [[📱✅]](https://hydra.nixos.org/build/272371546) [[🍎❌]](https://hydra.nixos.org/build/272367818) [[🐧✅]](https://hydra.nixos.org/build/272380311) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.sysinfo)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272385768) [[📱❌]](https://hydra.nixos.org/build/272380371) [[🍎❌]](https://hydra.nixos.org/build/272379268) [[🐧❌]](https://hydra.nixos.org/build/272386754) [haskellPackages.typed-session-state-algorithm](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.typed-session-state-algorithm)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272367966) [[📱✅]](https://hydra.nixos.org/build/272363647) [[🍎❌]](https://hydra.nixos.org/build/272388721) [[🐧✅]](https://hydra.nixos.org/build/272389532) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.FractalArt) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272377458) [[📱❌]](https://hydra.nixos.org/build/272366106) [[🍎✅]](https://hydra.nixos.org/build/272375052) [[🐧✅]](https://hydra.nixos.org/build/272370363) [haskellPackages.GOST34112012-Hash](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.GOST34112012-Hash) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272363771) [[📱❌]](https://hydra.nixos.org/build/272371244) [[🍎✅]](https://hydra.nixos.org/build/272383456) [[🐧✅]](https://hydra.nixos.org/build/272363167) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.HsASA) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272389410) [[🍎❌]](https://hydra.nixos.org/build/272383681) [haskellPackages.barbly](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.barbly) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272380776) [[📱❌]](https://hydra.nixos.org/build/272366344) [[🍎❌]](https://hydra.nixos.org/build/272378001) [[🐧❌]](https://hydra.nixos.org/build/272362921) [haskellPackages.cabal-add](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.cabal-add) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272364328) [[📱❌]](https://hydra.nixos.org/build/272378034) [[🍎❌]](https://hydra.nixos.org/build/272367331) [[🐧❌]](https://hydra.nixos.org/build/272369265) [haskellPackages.clash-multisignal](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.clash-multisignal) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272378867) [[📱❌]](https://hydra.nixos.org/build/272379551) [[🍎❌]](https://hydra.nixos.org/build/272371647) [[🐧❌]](https://hydra.nixos.org/build/272371008) [haskellPackages.clash-prelude-quickcheck](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.clash-prelude-quickcheck) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272362628) [[📱❌]](https://hydra.nixos.org/build/272380189) [[🍎❌]](https://hydra.nixos.org/build/272380306) [[🐧❌]](https://hydra.nixos.org/build/272381937) [haskellPackages.clash-systemverilog](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.clash-systemverilog) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272382220) [[📱❌]](https://hydra.nixos.org/build/272385498) [[🍎❌]](https://hydra.nixos.org/build/272385909) [[🐧❌]](https://hydra.nixos.org/build/272366159) [haskellPackages.clash-verilog](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.clash-verilog) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272383253) [[📱❌]](https://hydra.nixos.org/build/272369506) [[🍎❌]](https://hydra.nixos.org/build/272370412) [[🐧❌]](https://hydra.nixos.org/build/272377330) [haskellPackages.clash-vhdl](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.clash-vhdl) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272383558) [[📱❌]](https://hydra.nixos.org/build/272385308) [[🍎❌]](https://hydra.nixos.org/build/272370811) [[🐧❌]](https://hydra.nixos.org/build/272377943) [haskellPackages.clashilator](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.clashilator) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272390274) [[📱✅]](https://hydra.nixos.org/build/272376083) [[🍎❌]](https://hydra.nixos.org/build/272384636) [[🐧✅]](https://hydra.nixos.org/build/272376430) [haskellPackages.demangler](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.demangler) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272363442) [[📱❌]](https://hydra.nixos.org/build/272369115) [[🍎❌]](https://hydra.nixos.org/build/272385505) [[🐧❌]](https://hydra.nixos.org/build/272367423) [haskellPackages.dhall-toml](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.dhall-toml) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272387955) [[📱✅]](https://hydra.nixos.org/build/272378911) [[🍎❌]](https://hydra.nixos.org/build/272368989) [[🐧✅]](https://hydra.nixos.org/build/272373747) [haskellPackages.epub-metadata](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.epub-metadata) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272382115) [[📱✅]](https://hydra.nixos.org/build/272386705) [[🍎✅]](https://hydra.nixos.org/build/272378166) [[🐧✅]](https://hydra.nixos.org/build/272387115) [haskellPackages.executable-hash](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.executable-hash) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272366092) [[📱✅]](https://hydra.nixos.org/build/272390196) [[🍎❌]](https://hydra.nixos.org/build/272372835) [[🐧✅]](https://hydra.nixos.org/build/272362605) [haskellPackages.exinst-base](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.exinst-base) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272372345) [[📱✅]](https://hydra.nixos.org/build/272381981) [[🍎❌]](https://hydra.nixos.org/build/272381107) [[🐧✅]](https://hydra.nixos.org/build/272379473) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.fudgets) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272373489) [[📱✅]](https://hydra.nixos.org/build/272386493) [[🍎❌]](https://hydra.nixos.org/build/272376037) [[🐧✅]](https://hydra.nixos.org/build/272367171) [haskellPackages.genvalidity-dirforest](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.genvalidity-dirforest) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272389010) [[🍎❌]](https://hydra.nixos.org/build/272366426) [haskellPackages.gi-gtkosxapplication](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gi-gtkosxapplication) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272384419) [[🍎❌]](https://hydra.nixos.org/build/272388601) [haskellPackages.gtk-mac-integration](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gtk-mac-integration) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272380424) [[📱✅]](https://hydra.nixos.org/build/272389869) [[🍎❌]](https://hydra.nixos.org/build/272390719) [[🐧✅]](https://hydra.nixos.org/build/272371108) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gtk-traymanager) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272388221) [[🍎❌]](https://hydra.nixos.org/build/272374485) [haskellPackages.gtk3-mac-integration](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gtk3-mac-integration) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272389357) [[📱✅]](https://hydra.nixos.org/build/272377906) [[🍎❌]](https://hydra.nixos.org/build/272369615) [[🐧✅]](https://hydra.nixos.org/build/272369060) [haskellPackages.hdf5-lite](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hdf5-lite) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272373515) [[📱✅]](https://hydra.nixos.org/build/272388316) [[🍎❌]](https://hydra.nixos.org/build/272386490) [[🐧✅]](https://hydra.nixos.org/build/272365813) [haskellPackages.highlight](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.highlight) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272388171) [[📱❌]](https://hydra.nixos.org/build/272377711) [[🍎❌]](https://hydra.nixos.org/build/272378087) [[🐧❌]](https://hydra.nixos.org/build/272380715) [haskellPackages.hs-asapo](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hs-asapo) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272390373) [[📱✅]](https://hydra.nixos.org/build/272364795) [[🍎❌]](https://hydra.nixos.org/build/272382429) [[🐧✅]](https://hydra.nixos.org/build/272378141) [haskellPackages.hunspell-hs](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hunspell-hs) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272381466) [[📱✅]](https://hydra.nixos.org/build/272371289) [[🍎❌]](https://hydra.nixos.org/build/272375432) [[🐧✅]](https://hydra.nixos.org/build/272376591) [haskellPackages.interprocess](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.interprocess) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272380135) [[📱✅]](https://hydra.nixos.org/build/272374028) [[🍎✅]](https://hydra.nixos.org/build/272384354) [[🐧✅]](https://hydra.nixos.org/build/272385344) [haskellPackages.leveldb-haskell-fork](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.leveldb-haskell-fork) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272388865) [[📱✅]](https://hydra.nixos.org/build/272366652) [[🍎❌]](https://hydra.nixos.org/build/272388829) [[🐧✅]](https://hydra.nixos.org/build/272365706) [haskellPackages.memzero](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.memzero) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272377339) [[📱❗]](https://hydra.nixos.org/build/272385970) [[🍎❌]](https://hydra.nixos.org/build/272579854) [[🐧✅]](https://hydra.nixos.org/build/272579885) [haskellPackages.nix-serve-ng](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.nix-serve-ng) 
- [ ] [[🍏⌛🚫]](https://hydra.nixos.org/build/272362697) [[📱⌛🚫]](https://hydra.nixos.org/build/272382021) [[🍎⌛🚫]](https://hydra.nixos.org/build/272367610) [[🐧❌]](https://hydra.nixos.org/build/272388424) [haskellPackages.nspace](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.nspace) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272388102) [[📱✅]](https://hydra.nixos.org/build/272388243) [[🍎❌]](https://hydra.nixos.org/build/272370458) [[🐧✅]](https://hydra.nixos.org/build/272373411) [haskellPackages.persistent-pagination](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.persistent-pagination) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272363170) [[📱✅]](https://hydra.nixos.org/build/272371556) [[🍎❌]](https://hydra.nixos.org/build/272366804) [[🐧✅]](https://hydra.nixos.org/build/272384471) [haskellPackages.phatsort](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.phatsort) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272387714) [[📱✅]](https://hydra.nixos.org/build/272377337) [[🍎❌]](https://hydra.nixos.org/build/272383884) [[🐧✅]](https://hydra.nixos.org/build/272376204) [haskellPackages.ping-wrapper](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.ping-wrapper) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272372849) [[📱✅]](https://hydra.nixos.org/build/272369104) [[🍎❌]](https://hydra.nixos.org/build/272382091) [[🐧✅]](https://hydra.nixos.org/build/272362597) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.posix-timer) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272382604) [[📱✅]](https://hydra.nixos.org/build/272381135) [[🍎✅]](https://hydra.nixos.org/build/272365001) [[🐧✅]](https://hydra.nixos.org/build/272379896) [haskellPackages.postgrest](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.postgrest) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272385558) [[📱✅]](https://hydra.nixos.org/build/272366852) [[🍎❌]](https://hydra.nixos.org/build/272367575) [[🐧✅]](https://hydra.nixos.org/build/272369701) [haskellPackages.procex](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.procex) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272379784) [[📱✅]](https://hydra.nixos.org/build/272389469) [[🍎❌]](https://hydra.nixos.org/build/272376839) [[🐧✅]](https://hydra.nixos.org/build/272379952) [haskellPackages.pthread](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.pthread) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272378077) [[📱✅]](https://hydra.nixos.org/build/272368585) [[🍎✅]](https://hydra.nixos.org/build/272386233) [[🐧✅]](https://hydra.nixos.org/build/272385275) [haskellPackages.rdtsc-enolan](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.rdtsc-enolan) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272385384) [[📱✅]](https://hydra.nixos.org/build/272384022) [[🍎❌]](https://hydra.nixos.org/build/272364604) [[🐧✅]](https://hydra.nixos.org/build/272380412) [haskellPackages.sandwich-webdriver](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.sandwich-webdriver) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272388119) [[📱✅]](https://hydra.nixos.org/build/272374514) [[🍎❌]](https://hydra.nixos.org/build/272375357) [[🐧✅]](https://hydra.nixos.org/build/272388003) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.shared-memory) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272368580) [[📱❌]](https://hydra.nixos.org/build/272381826) [[🍎✅]](https://hydra.nixos.org/build/272383543) [[🐧✅]](https://hydra.nixos.org/build/272371329) [haskellPackages.significant-figures](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.significant-figures) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272375360) [[📱❌]](https://hydra.nixos.org/build/272385923) [[🍎✅]](https://hydra.nixos.org/build/272381510) [[🐧✅]](https://hydra.nixos.org/build/272378392) [haskellPackages.simdutf](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.simdutf) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272366572) [[📱❌]](https://hydra.nixos.org/build/272372258) [[🍎❌]](https://hydra.nixos.org/build/272371850) [[🐧❌]](https://hydra.nixos.org/build/272368132) [haskellPackages.strict-mvar](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.strict-mvar) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272368830) [[📱✅]](https://hydra.nixos.org/build/272379280) [[🍎✅]](https://hydra.nixos.org/build/272369726) [[🐧✅]](https://hydra.nixos.org/build/272389954) [haskellPackages.symbolize](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.symbolize) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272385057) [[📱✅]](https://hydra.nixos.org/build/272369795) [[🍎❌]](https://hydra.nixos.org/build/272370126) [[🐧✅]](https://hydra.nixos.org/build/272378838) [haskellPackages.tailfile-hinotify](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.tailfile-hinotify) 
- [ ] [[📱❌]](https://hydra.nixos.org/build/272375388) [[🐧✅]](https://hydra.nixos.org/build/272366243) [haskellPackages.tasty-papi](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.tasty-papi) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272367579) [[📱❗]](https://hydra.nixos.org/build/272363310) [[🍎❌]](https://hydra.nixos.org/build/272375068) [[🐧❌]](https://hydra.nixos.org/build/272370836) [haskellPackages.tiktoken](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.tiktoken) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272367173) [[📱❌]](https://hydra.nixos.org/build/272386438) [[🍎❌]](https://hydra.nixos.org/build/272363729) [[🐧❌]](https://hydra.nixos.org/build/272364728) [haskellPackages.uncertain](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.uncertain) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272389093) [[📱✅]](https://hydra.nixos.org/build/272377328) [[🍎✅]](https://hydra.nixos.org/build/272366189) [[🐧✅]](https://hydra.nixos.org/build/272373822) [haskellPackages.unix-simple](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.unix-simple) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272376879) [[📱✅]](https://hydra.nixos.org/build/272384195) [[🍎❌]](https://hydra.nixos.org/build/272386259) [[🐧✅]](https://hydra.nixos.org/build/272384764) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.xmonad-utils) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272385800) [[📱✅]](https://hydra.nixos.org/build/272382737) [[🍎❌]](https://hydra.nixos.org/build/272377415) [[🐧✅]](https://hydra.nixos.org/build/272376909) [haskellPackages.zot](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.zot) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/272369594) [[📱✅]](https://hydra.nixos.org/build/272369378) [[🍎❌]](https://hydra.nixos.org/build/272369997) [[🐧✅]](https://hydra.nixos.org/build/272367090) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>70 job(s) </summary>

- [ ] [microlens](https://hydra.nixos.org/eval/1808844?filter=microlens)  ⤴️ 154 | 597
  - [[🍏✅]](https://hydra.nixos.org/build/272374004) [[📱✅]](https://hydra.nixos.org/build/272376376) [[🍎✅]](https://hydra.nixos.org/build/272367076) [[🐧✅]](https://hydra.nixos.org/build/272376360) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.microlens)
  - [[🍏✅]](https://hydra.nixos.org/build/272379859)  [[🍎❗]](https://hydra.nixos.org/build/272374176) [[🐧✅]](https://hydra.nixos.org/build/272362933) [pkgsCross.ghcjs.haskell.packages.ghc98](https://hydra.nixos.org/eval/1808844?filter=pkgsCross.ghcjs.haskell.packages.ghc98.microlens)
  - [[🍏✅]](https://hydra.nixos.org/build/272364102)  [[🍎❗]](https://hydra.nixos.org/build/272381181) [[🐧✅]](https://hydra.nixos.org/build/272389201) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1808844?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.microlens)
  - [[🍏✅]](https://hydra.nixos.org/build/272384513)  [[🍎❗]](https://hydra.nixos.org/build/272385097) [[🐧✅]](https://hydra.nixos.org/build/272388818) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1808844?filter=pkgsCross.ghcjs.haskellPackages.microlens)
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272369513) [[📱❗]](https://hydra.nixos.org/build/272365908) [[🍎✅]](https://hydra.nixos.org/build/272386216) [[🐧✅]](https://hydra.nixos.org/build/272386106) [haskellPackages.base64](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.base64)  ⤴️ 20 | 63
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272386023) [[📱❗]](https://hydra.nixos.org/build/272363960) [[🍎✅]](https://hydra.nixos.org/build/272369417) [[🐧✅]](https://hydra.nixos.org/build/272366933) [haskellPackages.base16](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.base16)  ⤴️ 4 | 37
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272384048) [[📱❗]](https://hydra.nixos.org/build/272363611) [[🍎✅]](https://hydra.nixos.org/build/272364658) [[🐧✅]](https://hydra.nixos.org/build/272380595) [haskellPackages.murmur3](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.murmur3)  ⤴️ 4 | 21
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272571615) [[📱❗]](https://hydra.nixos.org/build/272571604) [[🍎✅]](https://hydra.nixos.org/build/272571611) [[🐧✅]](https://hydra.nixos.org/build/272571593) [haskellPackages.secp256k1-haskell](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.secp256k1-haskell)  ⤴️ 2 | 27
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272371567) [[📱❗]](https://hydra.nixos.org/build/272371446) [[🍎✅]](https://hydra.nixos.org/build/272376003) [[🐧✅]](https://hydra.nixos.org/build/272378447) [haskellPackages.hoauth2](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hoauth2)  ⤴️ 2 | 18
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272375172) [[📱❗]](https://hydra.nixos.org/build/272375961) [[🍎✅]](https://hydra.nixos.org/build/272367066) [[🐧✅]](https://hydra.nixos.org/build/272385163) [haskellPackages.HaskellNet](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.HaskellNet)  ⤴️ 2 | 6
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272381176) [[📱✅]](https://hydra.nixos.org/build/272384869) [[🍎❗]](https://hydra.nixos.org/build/272374093) [[🐧✅]](https://hydra.nixos.org/build/272381969) [haskellPackages.llvm-extra](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.llvm-extra)  ⤴️ 2 | 5
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272571597) [[📱❗]](https://hydra.nixos.org/build/272571620) [[🍎✅]](https://hydra.nixos.org/build/272571618) [[🐧✅]](https://hydra.nixos.org/build/272571627) [haskellPackages.haskoin-core](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.haskoin-core)  ⤴️ 1 | 16
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272369370) [[📱❗]](https://hydra.nixos.org/build/272371753) [[🍎✅]](https://hydra.nixos.org/build/272365295) [[🐧✅]](https://hydra.nixos.org/build/272366074) [haskellPackages.base32](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.base32)  ⤴️ 1 | 7
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272389117) [[📱❗]](https://hydra.nixos.org/build/272373631) [[🍎✅]](https://hydra.nixos.org/build/272364126) [[🐧✅]](https://hydra.nixos.org/build/272388428) [haskellPackages.HaskellNet-SSL](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.HaskellNet-SSL)  ⤴️ 1 | 4
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272364431) [[📱❗]](https://hydra.nixos.org/build/272381738) [[🍎❗]](https://hydra.nixos.org/build/272384598) [[🐧❗]](https://hydra.nixos.org/build/272387554) [haskellPackages.language-ats](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.language-ats)  ⤴️ 1 | 3
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272390099) [[📱✅]](https://hydra.nixos.org/build/272384858) [[🍎❗]](https://hydra.nixos.org/build/272370745) [[🐧✅]](https://hydra.nixos.org/build/272386359) [haskellPackages.llvm-dsl](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.llvm-dsl)  ⤴️ 1 | 3
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272389011) [[📱✅]](https://hydra.nixos.org/build/272368235) [[🍎❗]](https://hydra.nixos.org/build/272372724) [[🐧✅]](https://hydra.nixos.org/build/272378123) [haskellPackages.numeric-optimization](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.numeric-optimization)  ⤴️ 1 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272376313) [[📱✅]](https://hydra.nixos.org/build/272383658) [[🍎❗]](https://hydra.nixos.org/build/272362723) [[🐧✅]](https://hydra.nixos.org/build/272366329) [haskellPackages.soap](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.soap)  ⤴️ 1 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272371493) [[📱❗]](https://hydra.nixos.org/build/272373595) [[🍎✅]](https://hydra.nixos.org/build/272383024) [[🐧✅]](https://hydra.nixos.org/build/272380055) [haskellPackages.stan](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.stan)  ⤴️ 1 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272382583) [[📱❗]](https://hydra.nixos.org/build/272389259) [[🍎✅]](https://hydra.nixos.org/build/272390569) [[🐧✅]](https://hydra.nixos.org/build/272374672) [haskellPackages.hasql-th](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hasql-th)  ⤴️ 1 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272372473) [[📱✅]](https://hydra.nixos.org/build/272377077) [[🍎❗]](https://hydra.nixos.org/build/272384844) [[🐧✅]](https://hydra.nixos.org/build/272371761) [haskellPackages.sequence-formats](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.sequence-formats)  ⤴️ 1 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272366281) [[📱✅]](https://hydra.nixos.org/build/272373025) [[🍎❗]](https://hydra.nixos.org/build/272379276) [[🐧✅]](https://hydra.nixos.org/build/272372068) [haskellPackages.yaml-light](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.yaml-light)  ⤴️ 0 | 5
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272387970) [[📱❗]](https://hydra.nixos.org/build/272364854) [[🍎❗]](https://hydra.nixos.org/build/272385435) [[🐧❗]](https://hydra.nixos.org/build/272374768) [haskellPackages.hs2ats](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hs2ats)  ⤴️ 0 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272571599) [[📱❗]](https://hydra.nixos.org/build/272571613) [[🍎✅]](https://hydra.nixos.org/build/272571619) [[🐧✅]](https://hydra.nixos.org/build/272571605) [haskellPackages.haskoin-store-data](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.haskoin-store-data)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272376161) [[📱✅]](https://hydra.nixos.org/build/272376933) [[🍎❗]](https://hydra.nixos.org/build/272384454) [[🐧✅]](https://hydra.nixos.org/build/272381609) [haskellPackages.hsexif](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hsexif)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272384265) [[📱✅]](https://hydra.nixos.org/build/272366463) [[🍎❗]](https://hydra.nixos.org/build/272387728) [[🐧✅]](https://hydra.nixos.org/build/272372764) [haskellPackages.knead](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.knead)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272385610) [[📱✅]](https://hydra.nixos.org/build/272377035) [[🍎❗]](https://hydra.nixos.org/build/272385938) [[🐧✅]](https://hydra.nixos.org/build/272371707) [haskellPackages.network-dns](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.network-dns)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272380339) [[📱❗]](https://hydra.nixos.org/build/272365332) [[🍎✅]](https://hydra.nixos.org/build/272381621) [[🐧✅]](https://hydra.nixos.org/build/272370877) [haskellPackages.random-bytestring](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.random-bytestring)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272377709) [[📱✅]](https://hydra.nixos.org/build/272379716) [[🍎❗]](https://hydra.nixos.org/build/272382742) [[🐧✅]](https://hydra.nixos.org/build/272375367) [haskellPackages.amqp-utils](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.amqp-utils) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272377757) [[📱❗]](https://hydra.nixos.org/build/272384056) [[🍎❗]](https://hydra.nixos.org/build/272368271) [[🐧❗]](https://hydra.nixos.org/build/272373983) [haskellPackages.anansi-hscolour](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.anansi-hscolour) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272365922) [[📱✅]](https://hydra.nixos.org/build/272367682) [[🍎❗]](https://hydra.nixos.org/build/272367417) [[🐧✅]](https://hydra.nixos.org/build/272381361) [haskellPackages.cgrep](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.cgrep) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272372330) [[📱❗]](https://hydra.nixos.org/build/272381525) [[🍎❗]](https://hydra.nixos.org/build/272390622) [[🐧❗]](https://hydra.nixos.org/build/272387993) [haskellPackages.dhall-lex](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.dhall-lex) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272379187) [[📱✅]](https://hydra.nixos.org/build/272388295) [[🍎❗]](https://hydra.nixos.org/build/272388773) [[🐧✅]](https://hydra.nixos.org/build/272370940) [haskellPackages.diohsc](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.diohsc) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272380816) [[📱✅]](https://hydra.nixos.org/build/272377162) [[🍎❗]](https://hydra.nixos.org/build/272377234) [[🐧✅]](https://hydra.nixos.org/build/272375158) [haskellPackages.exinst-aeson](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.exinst-aeson) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272388497) [[📱✅]](https://hydra.nixos.org/build/272377019) [[🍎❗]](https://hydra.nixos.org/build/272374449) [[🐧✅]](https://hydra.nixos.org/build/272370614) [haskellPackages.exinst-bytes](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.exinst-bytes) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272380785) [[📱✅]](https://hydra.nixos.org/build/272378393) [[🍎❗]](https://hydra.nixos.org/build/272373280) [[🐧✅]](https://hydra.nixos.org/build/272375500) [haskellPackages.exinst-cereal](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.exinst-cereal) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272371407) [[📱✅]](https://hydra.nixos.org/build/272379790) [[🍎❗]](https://hydra.nixos.org/build/272381527) [[🐧✅]](https://hydra.nixos.org/build/272364790) [haskellPackages.exinst-serialise](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.exinst-serialise) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272372939) [[📱❗]](https://hydra.nixos.org/build/272372651) [[🍎✅]](https://hydra.nixos.org/build/272363889) [[🐧✅]](https://hydra.nixos.org/build/272386398) [haskellPackages.gemini-exports](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gemini-exports) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272389161) [[📱❗]](https://hydra.nixos.org/build/272382265) [[🍎✅]](https://hydra.nixos.org/build/272374418) [[🐧✅]](https://hydra.nixos.org/build/272376382) [haskellPackages.gmail-simple](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.gmail-simple) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272366297) [[📱❗]](https://hydra.nixos.org/build/272362590) [[🍎✅]](https://hydra.nixos.org/build/272381838) [[🐧✅]](https://hydra.nixos.org/build/272377588) [haskellPackages.hasql-mover](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hasql-mover) 
- [ ] [hello](https://hydra.nixos.org/eval/1808844?filter=hello) 
  - [[🍏✅]](https://hydra.nixos.org/build/272381146) [[📱✅]](https://hydra.nixos.org/build/272382617) [[🍎✅]](https://hydra.nixos.org/build/272384488) [[🐧✅]](https://hydra.nixos.org/build/272382002) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hello)
  - [[🍏✅]](https://hydra.nixos.org/build/272369669)  [[🍎❗]](https://hydra.nixos.org/build/272378092) [[🐧✅]](https://hydra.nixos.org/build/272377685) [pkgsCross.ghcjs.haskell.packages.ghc98](https://hydra.nixos.org/eval/1808844?filter=pkgsCross.ghcjs.haskell.packages.ghc98.hello)
  - [[🍏✅]](https://hydra.nixos.org/build/272380065)  [[🍎❗]](https://hydra.nixos.org/build/272383812) [[🐧✅]](https://hydra.nixos.org/build/272377971) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1808844?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.hello)
  - [[🍏✅]](https://hydra.nixos.org/build/272374106)  [[🍎❗]](https://hydra.nixos.org/build/272386602) [[🐧✅]](https://hydra.nixos.org/build/272371252) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1808844?filter=pkgsCross.ghcjs.haskellPackages.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/272377639) [pkgsMusl.haskellPackages](https://hydra.nixos.org/eval/1808844?filter=pkgsMusl.haskellPackages.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/272367882) [pkgsStatic.haskell.packages.native-bignum.ghc948](https://hydra.nixos.org/eval/1808844?filter=pkgsStatic.haskell.packages.native-bignum.ghc948.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/272389718) [pkgsStatic.haskell.packages.native-bignum.ghc982](https://hydra.nixos.org/eval/1808844?filter=pkgsStatic.haskell.packages.native-bignum.ghc982.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/272376848) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1808844?filter=pkgsStatic.haskellPackages.hello)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272371460) [[📱❗]](https://hydra.nixos.org/build/272377228) [[🍎✅]](https://hydra.nixos.org/build/272379475) [[🐧✅]](https://hydra.nixos.org/build/272375742) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272389861) [[📱❗]](https://hydra.nixos.org/build/272374719) [[🍎✅]](https://hydra.nixos.org/build/272390065) [[🐧✅]](https://hydra.nixos.org/build/272370845) [haskellPackages.hs-aws-lambda](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hs-aws-lambda) 
- [ ] [[🍎❗]](https://hydra.nixos.org/build/272389461) [[🐧✅]](https://hydra.nixos.org/build/272373895) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272378095) [[📱❗]](https://hydra.nixos.org/build/272379739) [[🍎❗]](https://hydra.nixos.org/build/272382474) [[🐧❗]](https://hydra.nixos.org/build/272372511) [haskellPackages.hspec-dirstream](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.hspec-dirstream) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272386830) [[📱✅]](https://hydra.nixos.org/build/272381903) [[🍎❗]](https://hydra.nixos.org/build/272382173) [[🐧✅]](https://hydra.nixos.org/build/272389347) [haskellPackages.intel-powermon](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.intel-powermon) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272366856) [[📱❗]](https://hydra.nixos.org/build/272389126) [[🍎❗]](https://hydra.nixos.org/build/272372687) [[🐧❗]](https://hydra.nixos.org/build/272390378) [haskellPackages.io-classes-mtl](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.io-classes-mtl) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272379184) [[📱❗]](https://hydra.nixos.org/build/272381197) [[🍎✅]](https://hydra.nixos.org/build/272376179) [[🐧✅]](https://hydra.nixos.org/build/272367786) [haskellPackages.mail-pool](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.mail-pool) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272366816) [[📱❗]](https://hydra.nixos.org/build/272376953) [[🍎✅]](https://hydra.nixos.org/build/272385114) [[🐧✅]](https://hydra.nixos.org/build/272377564) [haskellPackages.mailtrap](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.mailtrap) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272379066) [[📱✅]](https://hydra.nixos.org/build/272381248) [[🍎❗]](https://hydra.nixos.org/build/272371009) [[🐧✅]](https://hydra.nixos.org/build/272376359) [haskellPackages.mime-string](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.mime-string) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272366665) [[📱✅]](https://hydra.nixos.org/build/272376866) [[🍎❗]](https://hydra.nixos.org/build/272387575) [[🐧✅]](https://hydra.nixos.org/build/272372727) [haskellPackages.numeric-optimization-ad](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.numeric-optimization-ad) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272383505) [[📱✅]](https://hydra.nixos.org/build/272374462) [[🍎❗]](https://hydra.nixos.org/build/272363287) [[🐧✅]](https://hydra.nixos.org/build/272374270) [haskellPackages.redland](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.redland) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272364626) [[📱✅]](https://hydra.nixos.org/build/272366639) [[🍎❗]](https://hydra.nixos.org/build/272390491) [[🐧✅]](https://hydra.nixos.org/build/272373809) [haskellPackages.sequenceTools](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.sequenceTools) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272380445) [[📱✅]](https://hydra.nixos.org/build/272364193) [[🍎❗]](https://hydra.nixos.org/build/272371059) [[🐧✅]](https://hydra.nixos.org/build/272368169) [haskellPackages.soap-openssl](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.soap-openssl) 
- [ ] [spago](https://hydra.nixos.org/eval/1808844?filter=spago) 
  - [[🍏❗]](https://hydra.nixos.org/build/272379281) [[📱✅]](https://hydra.nixos.org/build/272373237) [[🍎❗]](https://hydra.nixos.org/build/272382649) [[🐧✅]](https://hydra.nixos.org/build/272369627) [toplevel](https://hydra.nixos.org/eval/1808844?filter=spago)
  - [[🍏❗]](https://hydra.nixos.org/build/272373874) [[📱✅]](https://hydra.nixos.org/build/272383966) [[🍎❗]](https://hydra.nixos.org/build/272378139) [[🐧✅]](https://hydra.nixos.org/build/272367832) [haskellPackages](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.spago)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272376143) [[📱✅]](https://hydra.nixos.org/build/272370926) [[🍎❗]](https://hydra.nixos.org/build/272385147) [[🐧✅]](https://hydra.nixos.org/build/272382637) [haskellPackages.sym-plot](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.sym-plot) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/272375190) [[📱✅]](https://hydra.nixos.org/build/272388386) [[🍎❗]](https://hydra.nixos.org/build/272382628) [[🐧✅]](https://hydra.nixos.org/build/272366766) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.xbattbar) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272372209) [[📱❗]](https://hydra.nixos.org/build/272382325) [[🍎✅]](https://hydra.nixos.org/build/272378403) [[🐧✅]](https://hydra.nixos.org/build/272363965) [haskellPackages.yesod-auth-oauth2](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.yesod-auth-oauth2) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/272386652) [[📱❗]](https://hydra.nixos.org/build/272369813) [[🍎✅]](https://hydra.nixos.org/build/272366425) [[🐧✅]](https://hydra.nixos.org/build/272382588) [haskellPackages.yesod-session-persist](https://hydra.nixos.org/eval/1808844?filter=haskellPackages.yesod-session-persist) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) ⤴️ 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) ⤴️ 152  
[failure](https://packdeps.haskellers.com/reverse/failure) ⤴️ 72  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) ⤴️ 56  
[connection](https://packdeps.haskellers.com/reverse/connection) ⤴️ 53  
[util](https://packdeps.haskellers.com/reverse/util) ⤴️ 49  
[derive](https://packdeps.haskellers.com/reverse/derive) ⤴️ 48  
[web-routes](https://packdeps.haskellers.com/reverse/web-routes) ⤴️ 43  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) ⤴️ 42  
[syb-with-class](https://packdeps.haskellers.com/reverse/syb-with-class) ⤴️ 42  
[MonadCatchIO-transformers](https://packdeps.haskellers.com/reverse/MonadCatchIO-transformers) ⤴️ 41  
[TypeCompose](https://packdeps.haskellers.com/reverse/TypeCompose) ⤴️ 41  
[PrimitiveArray](https://packdeps.haskellers.com/reverse/PrimitiveArray) ⤴️ 35  
[crypto-random](https://packdeps.haskellers.com/reverse/crypto-random) ⤴️ 35  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) ⤴️ 33  
[dual](https://packdeps.haskellers.com/reverse/dual) ⤴️ 32  
[hsp](https://packdeps.haskellers.com/reverse/hsp) ⤴️ 32  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) ⤴️ 31  
[language-ecmascript](https://packdeps.haskellers.com/reverse/language-ecmascript) ⤴️ 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) ⤴️ 30  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) ⤴️ 29  
[polysemy-time](https://packdeps.haskellers.com/reverse/polysemy-time) ⤴️ 29  
[composite-base](https://packdeps.haskellers.com/reverse/composite-base) ⤴️ 28  
[polysemy-resume](https://packdeps.haskellers.com/reverse/polysemy-resume) ⤴️ 28  
[polysemy-conc](https://packdeps.haskellers.com/reverse/polysemy-conc) ⤴️ 27  
[regexpr](https://packdeps.haskellers.com/reverse/regexpr) ⤴️ 27  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) ⤴️ 25  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) ⤴️ 25  
[polysemy-log](https://packdeps.haskellers.com/reverse/polysemy-log) ⤴️ 25  
[HList](https://packdeps.haskellers.com/reverse/HList) ⤴️ 24  
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
[hsx2hs](https://packdeps.haskellers.com/reverse/hsx2hs) ⤴️ 19  
[incipit](https://packdeps.haskellers.com/reverse/incipit) ⤴️ 19  
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
