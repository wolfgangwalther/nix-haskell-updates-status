### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1806462](https://hydra.nixos.org/eval/1806462) of nixpkgs commit [7d41da6](https://github.com/NixOS/nixpkgs/commits/7d41da6c40a280a4fee0d203fec44952033dea6c) as of 2024-05-22 18:11 UTC*

🔴 **Branch not mergeable**
  * `mergeable` jobset failed.
  * Too many outstanding jobs on x86_64-linux.
  * `maintained` jobset failed.

#### Build summary

 | Platform | Failed ❌ | DependencyFailed ❗ | TimedOut ⌛🚫 | Unfinished ⏳ | Success ✅ | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-darwin 🍏](https://hydra.nixos.org/eval/1806462?filter=.aarch64-darwin) | 30 | 20 |  | 3120 | 3234 | 
 | [aarch64-linux 📱](https://hydra.nixos.org/eval/1806462?filter=.aarch64-linux) | 12 | 4 | 1 | 36 | 6422 | 
 | [x86_64-darwin 🍎](https://hydra.nixos.org/eval/1806462?filter=.x86_64-darwin) | 25 | 15 |  | 3136 | 3235 | 
 | [x86_64-linux 🐧](https://hydra.nixos.org/eval/1806462?filter=.x86_64-linux) | 2 |  | 881 | 2049 | 3606 | 
#### Maintained Linux packages with build failure
- [ ] [hlint](https://hydra.nixos.org/eval/1806462?filter=hlint) @maralorn
  - [[📱✅]](https://hydra.nixos.org/build/260714925) [[🐧⏳]](https://hydra.nixos.org/build/260716840) [toplevel](https://hydra.nixos.org/eval/1806462?filter=hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260707506) [[🐧⏳]](https://hydra.nixos.org/build/260721001) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc925.hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260715995) [[🐧⏳]](https://hydra.nixos.org/build/260704447) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc926.hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260728231) [[🐧⏳]](https://hydra.nixos.org/build/260709171) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc927.hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260720349) [[🐧⏳]](https://hydra.nixos.org/build/260712677) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc928.hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260717602) [[🐧⏳]](https://hydra.nixos.org/build/260704162) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc945.hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260707738) [[🐧⏳]](https://hydra.nixos.org/build/260706439) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc946.hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260721745) [[🐧⏳]](https://hydra.nixos.org/build/260704204) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc947.hlint)
  - [[📱⏳]](https://hydra.nixos.org/build/260726173) [[🐧⏳]](https://hydra.nixos.org/build/260718871) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc948.hlint)
  - [[📱❌]](https://hydra.nixos.org/build/260713093) [[🐧⏳]](https://hydra.nixos.org/build/260716481) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc963.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/260709153) [[🐧⏳]](https://hydra.nixos.org/build/260709802) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc964.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/260725081) [[🐧⏳]](https://hydra.nixos.org/build/260721768) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc965.hlint)
  - [[📱✅]](https://hydra.nixos.org/build/260708978) [[🐧⏳]](https://hydra.nixos.org/build/260717121) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hlint)
#### Maintained Linux packages with failed dependency
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1806462?filter=haskell-language-server) @maralorn
  - [[📱✅]](https://hydra.nixos.org/build/260722178) [[🐧⌛🚫]](https://hydra.nixos.org/build/260718461) [toplevel](https://hydra.nixos.org/eval/1806462?filter=haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260721293) [[🐧⏳]](https://hydra.nixos.org/build/260713024) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc925.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260707091) [[🐧⏳]](https://hydra.nixos.org/build/260711071) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc926.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260702632) [[🐧⏳]](https://hydra.nixos.org/build/260723549) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc927.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260713972) [[🐧⏳]](https://hydra.nixos.org/build/260722873) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc928.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260717305) [[🐧⏳]](https://hydra.nixos.org/build/260707271) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc945.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260724339) [[🐧⏳]](https://hydra.nixos.org/build/260718523) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc946.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260705858) [[🐧⏳]](https://hydra.nixos.org/build/260703416) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc947.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260702784) [[🐧⏳]](https://hydra.nixos.org/build/260728871) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc948.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/260707796) [[🐧⏳]](https://hydra.nixos.org/build/260705616) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc963.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/260703620) [[🐧⏳]](https://hydra.nixos.org/build/260715262) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc964.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/260703019) [[🐧⌛🚫]](https://hydra.nixos.org/build/260702937) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc965.haskell-language-server)
  - [[📱⏳]](https://hydra.nixos.org/build/260703013) [[🐧⏳]](https://hydra.nixos.org/build/260713380) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc981.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/260715592) [[🐧⏳]](https://hydra.nixos.org/build/260710397) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc982.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/260717517) [[🐧⌛🚫]](https://hydra.nixos.org/build/260703522) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.haskell-language-server)
#### Maintained Darwin packages with failed dependency
<details><summary>81 job(s) </summary>

- [ ] [funcmp](https://hydra.nixos.org/eval/1806462?filter=funcmp) @peti
  - [[🍏⏳]](https://hydra.nixos.org/build/260708111) [[🍎⏳]](https://hydra.nixos.org/build/260717682) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc8107.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260713117) [[🍎⏳]](https://hydra.nixos.org/build/260716726) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc902.funcmp)
  - [[🍏❗]](https://hydra.nixos.org/build/260723889) [[🍎⏳]](https://hydra.nixos.org/build/260723152) [haskell.packages.ghc9101](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc9101.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260722615) [[🍎⏳]](https://hydra.nixos.org/build/260705341) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc925.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260702256) [[🍎⏳]](https://hydra.nixos.org/build/260724859) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc926.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260702142) [[🍎⏳]](https://hydra.nixos.org/build/260709216) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc927.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260718528) [[🍎⏳]](https://hydra.nixos.org/build/260716592) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc928.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260719950) [[🍎⏳]](https://hydra.nixos.org/build/260727228) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc945.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260728423) [[🍎⏳]](https://hydra.nixos.org/build/260719813) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc946.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260709269) [[🍎⏳]](https://hydra.nixos.org/build/260703695) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc947.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260709888) [[🍎⏳]](https://hydra.nixos.org/build/260705388) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc948.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260718899) [[🍎⏳]](https://hydra.nixos.org/build/260703320) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc963.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260715464) [[🍎⏳]](https://hydra.nixos.org/build/260720664) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc964.funcmp)
  - [[🍏✅]](https://hydra.nixos.org/build/260708430) [[🍎✅]](https://hydra.nixos.org/build/260713934) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc965.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260718830) [[🍎⏳]](https://hydra.nixos.org/build/260725512) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc981.funcmp)
  - [[🍏⏳]](https://hydra.nixos.org/build/260710066) [[🍎⏳]](https://hydra.nixos.org/build/260703165) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc982.funcmp)
  - [[🍏✅]](https://hydra.nixos.org/build/260718860) [[🍎✅]](https://hydra.nixos.org/build/260713959) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.funcmp)
- [ ] [ghc910](https://hydra.nixos.org/eval/1806462?filter=ghc910) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏❗]](https://hydra.nixos.org/build/260727539) [[🍎⏳]](https://hydra.nixos.org/build/260702838) [haskell.compiler](https://hydra.nixos.org/eval/1806462?filter=haskell.compiler.ghc910)
  - [[🍏❗]](https://hydra.nixos.org/build/260720802) [[🍎⏳]](https://hydra.nixos.org/build/260714812) [haskell.compiler.native-bignum](https://hydra.nixos.org/eval/1806462?filter=haskell.compiler.native-bignum.ghc910)
- [ ] [ghc9101](https://hydra.nixos.org/eval/1806462?filter=ghc9101) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏❗]](https://hydra.nixos.org/build/260703959) [[🍎⏳]](https://hydra.nixos.org/build/260711530) [haskell.compiler](https://hydra.nixos.org/eval/1806462?filter=haskell.compiler.ghc9101)
  - [[🍏❗]](https://hydra.nixos.org/build/260706657) [[🍎⏳]](https://hydra.nixos.org/build/260706569) [haskell.compiler.native-bignum](https://hydra.nixos.org/eval/1806462?filter=haskell.compiler.native-bignum.ghc9101)
- [ ] [ghcHEAD](https://hydra.nixos.org/eval/1806462?filter=ghcHEAD) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏❗]](https://hydra.nixos.org/build/260709010) [[🍎⏳]](https://hydra.nixos.org/build/260729157) [haskell.compiler](https://hydra.nixos.org/eval/1806462?filter=haskell.compiler.ghcHEAD)
  - [[🍏❗]](https://hydra.nixos.org/build/260715997) [[🍎⏳]](https://hydra.nixos.org/build/260728469) [haskell.compiler.native-bignum](https://hydra.nixos.org/eval/1806462?filter=haskell.compiler.native-bignum.ghcHEAD)
- [ ] [hsdns](https://hydra.nixos.org/eval/1806462?filter=hsdns) @peti
  - [[🍏⏳]](https://hydra.nixos.org/build/260705505) [[🍎⏳]](https://hydra.nixos.org/build/260708965) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc8107.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260725193) [[🍎⏳]](https://hydra.nixos.org/build/260715841) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc902.hsdns)
  - [[🍏❗]](https://hydra.nixos.org/build/260726636) [[🍎⏳]](https://hydra.nixos.org/build/260702773) [haskell.packages.ghc9101](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc9101.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260711423) [[🍎⏳]](https://hydra.nixos.org/build/260713924) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc925.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260719798) [[🍎⏳]](https://hydra.nixos.org/build/260712505) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc926.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260725522) [[🍎⏳]](https://hydra.nixos.org/build/260716965) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc927.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260716003) [[🍎⏳]](https://hydra.nixos.org/build/260728812) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc928.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260728691) [[🍎⏳]](https://hydra.nixos.org/build/260703315) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc945.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260712452) [[🍎⏳]](https://hydra.nixos.org/build/260724669) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc946.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260705258) [[🍎⏳]](https://hydra.nixos.org/build/260708645) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc947.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260708096) [[🍎⏳]](https://hydra.nixos.org/build/260711196) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc948.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260716408) [[🍎⏳]](https://hydra.nixos.org/build/260702411) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc963.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260715376) [[🍎⏳]](https://hydra.nixos.org/build/260711018) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc964.hsdns)
  - [[🍏✅]](https://hydra.nixos.org/build/260714006) [[🍎✅]](https://hydra.nixos.org/build/260719226) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc965.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260707633) [[🍎⏳]](https://hydra.nixos.org/build/260729213) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc981.hsdns)
  - [[🍏⏳]](https://hydra.nixos.org/build/260709491) [[🍎⏳]](https://hydra.nixos.org/build/260711235) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc982.hsdns)
  - [[🍏✅]](https://hydra.nixos.org/build/260709453) [[🍎✅]](https://hydra.nixos.org/build/260719452) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hsdns)
- [ ] [jailbreak-cabal](https://hydra.nixos.org/eval/1806462?filter=jailbreak-cabal) @sternenseemann
  - [[🍏✅]](https://hydra.nixos.org/build/260712778) [[🍎✅]](https://hydra.nixos.org/build/260709537) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc8107.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260717605) [[🍎⏳]](https://hydra.nixos.org/build/260724440) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc902.jailbreak-cabal)
  - [[🍏❗]](https://hydra.nixos.org/build/260725073) [[🍎⏳]](https://hydra.nixos.org/build/260708301) [haskell.packages.ghc9101](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc9101.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260713237) [[🍎⏳]](https://hydra.nixos.org/build/260712534) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc925.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260715123) [[🍎⏳]](https://hydra.nixos.org/build/260716248) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc926.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260725731) [[🍎⏳]](https://hydra.nixos.org/build/260723355) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc927.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260719162) [[🍎⏳]](https://hydra.nixos.org/build/260710249) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc928.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260721560) [[🍎⏳]](https://hydra.nixos.org/build/260707768) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc945.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260717744) [[🍎⏳]](https://hydra.nixos.org/build/260704842) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc946.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260713130) [[🍎⏳]](https://hydra.nixos.org/build/260704089) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc947.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260703334) [[🍎⏳]](https://hydra.nixos.org/build/260703175) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc948.jailbreak-cabal)
  - [[🍏✅]](https://hydra.nixos.org/build/260717141) [[🍎✅]](https://hydra.nixos.org/build/260728288) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc963.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260725166) [[🍎✅]](https://hydra.nixos.org/build/260721072) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc964.jailbreak-cabal)
  - [[🍏✅]](https://hydra.nixos.org/build/260728378) [[🍎✅]](https://hydra.nixos.org/build/260711546) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc965.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260712324) [[🍎⏳]](https://hydra.nixos.org/build/260726305) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc981.jailbreak-cabal)
  - [[🍏⏳]](https://hydra.nixos.org/build/260723564) [[🍎⏳]](https://hydra.nixos.org/build/260719580) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc982.jailbreak-cabal)
  - [[🍏✅]](https://hydra.nixos.org/build/260723690) [[🍎✅]](https://hydra.nixos.org/build/260714442) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.jailbreak-cabal)
- [ ] [nix-paths](https://hydra.nixos.org/eval/1806462?filter=nix-paths) @peti
  - [[🍏⏳]](https://hydra.nixos.org/build/260718792) [[🍎⏳]](https://hydra.nixos.org/build/260718935) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc8107.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260717150) [[🍎⏳]](https://hydra.nixos.org/build/260711618) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc902.nix-paths)
  - [[🍏❗]](https://hydra.nixos.org/build/260713052) [[🍎⏳]](https://hydra.nixos.org/build/260708917) [haskell.packages.ghc9101](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc9101.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260727512) [[🍎⏳]](https://hydra.nixos.org/build/260706897) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc925.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260716374) [[🍎⏳]](https://hydra.nixos.org/build/260724164) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc926.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260719761) [[🍎⏳]](https://hydra.nixos.org/build/260720982) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc927.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260709528) [[🍎⏳]](https://hydra.nixos.org/build/260716882) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc928.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260718715) [[🍎⏳]](https://hydra.nixos.org/build/260702559) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc945.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260720369) [[🍎⏳]](https://hydra.nixos.org/build/260706381) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc946.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260702372) [[🍎⏳]](https://hydra.nixos.org/build/260720548) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc947.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260703721) [[🍎⏳]](https://hydra.nixos.org/build/260705681) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc948.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260703402) [[🍎⏳]](https://hydra.nixos.org/build/260707643) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc963.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260717505) [[🍎⏳]](https://hydra.nixos.org/build/260711372) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc964.nix-paths)
  - [[🍏✅]](https://hydra.nixos.org/build/260715038) [[🍎✅]](https://hydra.nixos.org/build/260709363) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc965.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260702748) [[🍎⏳]](https://hydra.nixos.org/build/260709187) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc981.nix-paths)
  - [[🍏⏳]](https://hydra.nixos.org/build/260724668) [[🍎⏳]](https://hydra.nixos.org/build/260723610) [haskell.packages.ghc982](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc982.nix-paths)
  - [[🍏✅]](https://hydra.nixos.org/build/260706780) [[🍎✅]](https://hydra.nixos.org/build/260719345) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.nix-paths)
</details>

#### Unmaintained packages with build failure
<details><summary>44 job(s) </summary>

- [ ] [[🍏❌]](https://hydra.nixos.org/build/260717825) [[📱✅]](https://hydra.nixos.org/build/260719723) [[🍎❌]](https://hydra.nixos.org/build/260727648) [[🐧✅]](https://hydra.nixos.org/build/260710529) [haskellPackages.di-core](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.di-core)  ⤴️ 6 | 13
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260719402) [[📱✅]](https://hydra.nixos.org/build/260706684) [[🍎❌]](https://hydra.nixos.org/build/260708992) [[🐧✅]](https://hydra.nixos.org/build/260708936) [haskellPackages.iconv](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.iconv)  ⤴️ 4 | 16
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260728208) [[📱❌]](https://hydra.nixos.org/build/260720701) [[🍎⏳]](https://hydra.nixos.org/build/260722320) [[🐧⏳]](https://hydra.nixos.org/build/260723678) [haskellPackages.ghc-internal](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.ghc-internal)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260704144) [[📱✅]](https://hydra.nixos.org/build/260720801) [[🍎❌]](https://hydra.nixos.org/build/260708855) [[🐧✅]](https://hydra.nixos.org/build/260713580) [haskellPackages.rawfilepath](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.rawfilepath)  ⤴️ 1 | 2
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260723748) [[📱❌]](https://hydra.nixos.org/build/260715824) [[🍎⏳]](https://hydra.nixos.org/build/260708033) [[🐧⏳]](https://hydra.nixos.org/build/260714117) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.nlopt-haskell)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260717856) [[📱✅]](https://hydra.nixos.org/build/260723636) [[🍎❌]](https://hydra.nixos.org/build/260712649) [[🐧✅]](https://hydra.nixos.org/build/260717612) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.openal-ffi)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260728155) [[📱✅]](https://hydra.nixos.org/build/260721435) [[🍎❌]](https://hydra.nixos.org/build/260727840) [[🐧✅]](https://hydra.nixos.org/build/260722994) [haskellPackages.libxml-sax](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.libxml-sax)  ⤴️ 0 | 21
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260726767) [[📱❌]](https://hydra.nixos.org/build/260723868) [[🍎✅]](https://hydra.nixos.org/build/260705316) [[🐧✅]](https://hydra.nixos.org/build/260719991) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.freetype2)  ⤴️ 0 | 12
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260715829) [[📱❌]](https://hydra.nixos.org/build/260702947) [[🍎⏳]](https://hydra.nixos.org/build/260709472) [[🐧⏳]](https://hydra.nixos.org/build/260711103) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hw-simd)  ⤴️ 0 | 9
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260714489) [[📱✅]](https://hydra.nixos.org/build/260714240) [[🍎❌]](https://hydra.nixos.org/build/260703403) [[🐧✅]](https://hydra.nixos.org/build/260715665) [haskellPackages.bytestring-encoding](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.bytestring-encoding)  ⤴️ 0 | 6
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260702463) [[📱✅]](https://hydra.nixos.org/build/260711465) [[🍎✅]](https://hydra.nixos.org/build/260714170) [[🐧✅]](https://hydra.nixos.org/build/260721462) [haskellPackages.rdtsc](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.rdtsc)  ⤴️ 0 | 4
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260725613) [[📱✅]](https://hydra.nixos.org/build/260704362) [[🍎❌]](https://hydra.nixos.org/build/260716339) [[🐧✅]](https://hydra.nixos.org/build/260710931) [haskellPackages.error-codes](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.error-codes)  ⤴️ 0 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260718914) [[📱✅]](https://hydra.nixos.org/build/260703125) [[🍎✅]](https://hydra.nixos.org/build/260712227) [[🐧✅]](https://hydra.nixos.org/build/260706473) [haskellPackages.bindings-levmar](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.bindings-levmar)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260709571) [[📱✅]](https://hydra.nixos.org/build/260710665) [[🍎✅]](https://hydra.nixos.org/build/260702560) [[🐧✅]](https://hydra.nixos.org/build/260719690) [haskellPackages.rocksdb-haskell](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.rocksdb-haskell)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260706961) [[📱✅]](https://hydra.nixos.org/build/260727429) [[🍎❌]](https://hydra.nixos.org/build/260720667) [[🐧✅]](https://hydra.nixos.org/build/260727815) [haskellPackages.hamid](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hamid)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260713617) [[📱✅]](https://hydra.nixos.org/build/260717575) [[🍎❌]](https://hydra.nixos.org/build/260706302) [[🐧✅]](https://hydra.nixos.org/build/260708297) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.huckleberry)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260708543) [[📱✅]](https://hydra.nixos.org/build/260725178) [[🍎❌]](https://hydra.nixos.org/build/260713262) [[🐧✅]](https://hydra.nixos.org/build/260728275) [haskellPackages.select](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.select)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260719932) [[📱✅]](https://hydra.nixos.org/build/260717923) [[🍎❌]](https://hydra.nixos.org/build/260720612) [[🐧✅]](https://hydra.nixos.org/build/260707009) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.sysinfo)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260704001) [[📱❌]](https://hydra.nixos.org/build/260721746) [[🍎✅]](https://hydra.nixos.org/build/260705535) [[🐧✅]](https://hydra.nixos.org/build/260708213) [haskellPackages.GOST34112012-Hash](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.GOST34112012-Hash) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260726716) [[📱❌]](https://hydra.nixos.org/build/260717963) [[🍎✅]](https://hydra.nixos.org/build/260716075) [[🐧✅]](https://hydra.nixos.org/build/260721114) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.HsASA) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260727298) [[📱✅]](https://hydra.nixos.org/build/260707006) [[🍎❌]](https://hydra.nixos.org/build/260728670) [[🐧❌]](https://hydra.nixos.org/build/260723484) [haskellPackages.bluefin-algae](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.bluefin-algae) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260712765) [[📱❌]](https://hydra.nixos.org/build/260710134) [[🍎⏳]](https://hydra.nixos.org/build/260712418) [[🐧⏳]](https://hydra.nixos.org/build/260724402) [haskellPackages.changelog-d](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.changelog-d) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260710815) [[📱✅]](https://hydra.nixos.org/build/260705348) [[🍎❌]](https://hydra.nixos.org/build/260724521) [[🐧✅]](https://hydra.nixos.org/build/260708585) [haskellPackages.env-extra](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.env-extra) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260713593) [[📱✅]](https://hydra.nixos.org/build/260721826) [[🍎✅]](https://hydra.nixos.org/build/260723914) [[🐧✅]](https://hydra.nixos.org/build/260705654) [haskellPackages.executable-hash](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.executable-hash) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260714893) [[📱✅]](https://hydra.nixos.org/build/260728403) [[🍎❌]](https://hydra.nixos.org/build/260720945) [[🐧✅]](https://hydra.nixos.org/build/260725488) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.fudgets) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260717542) [[📱✅]](https://hydra.nixos.org/build/260715295) [[🍎❌]](https://hydra.nixos.org/build/260728884) [[🐧✅]](https://hydra.nixos.org/build/260723285) [haskellPackages.hunspell-hs](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hunspell-hs) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260720528) [[📱✅]](https://hydra.nixos.org/build/260715633) [[🍎❌]](https://hydra.nixos.org/build/260720944) [[🐧✅]](https://hydra.nixos.org/build/260723779) [haskellPackages.interprocess](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.interprocess) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260706724) [[🍎❌]](https://hydra.nixos.org/build/260716903) [haskellPackages.kqueue](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.kqueue) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260705324) [[📱✅]](https://hydra.nixos.org/build/260709008) [[🍎✅]](https://hydra.nixos.org/build/260725620) [[🐧✅]](https://hydra.nixos.org/build/260713197) [haskellPackages.leveldb-haskell-fork](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.leveldb-haskell-fork) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260719569) [[📱✅]](https://hydra.nixos.org/build/260722181) [[🍎❌]](https://hydra.nixos.org/build/260728270) [[🐧✅]](https://hydra.nixos.org/build/260726954) [haskellPackages.memzero](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.memzero) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260729187) [[📱❌]](https://hydra.nixos.org/build/260709430) [[🍎⏳]](https://hydra.nixos.org/build/260706249) [[🐧⏳]](https://hydra.nixos.org/build/260711915) [haskellPackages.no-recursion](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.no-recursion) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260726051) [[📱✅]](https://hydra.nixos.org/build/260705904) [[🍎❌]](https://hydra.nixos.org/build/260706211) [[🐧✅]](https://hydra.nixos.org/build/260717772) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.posix-timer) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260728139) [[📱✅]](https://hydra.nixos.org/build/260715093) [[🍎❌]](https://hydra.nixos.org/build/260724915) [[🐧✅]](https://hydra.nixos.org/build/260720275) [haskellPackages.procex](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.procex) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260725824) [[📱✅]](https://hydra.nixos.org/build/260724778) [[🍎❌]](https://hydra.nixos.org/build/260726411) [[🐧✅]](https://hydra.nixos.org/build/260705143) [haskellPackages.pthread](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.pthread) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260718157) [[📱✅]](https://hydra.nixos.org/build/260702660) [[🍎✅]](https://hydra.nixos.org/build/260712663) [[🐧❌]](https://hydra.nixos.org/build/260706413) [haskellPackages.random-strings](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.random-strings) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260725956) [[📱✅]](https://hydra.nixos.org/build/260713387) [[🍎✅]](https://hydra.nixos.org/build/260709504) [[🐧✅]](https://hydra.nixos.org/build/260721631) [haskellPackages.rdtsc-enolan](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.rdtsc-enolan) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260718708) [[📱❌]](https://hydra.nixos.org/build/260718103) [[🍎⏳]](https://hydra.nixos.org/build/260726428) [[🐧⏳]](https://hydra.nixos.org/build/260725788) [haskellPackages.real-dice](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.real-dice) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260706071) [[📱✅]](https://hydra.nixos.org/build/260713394) [[🍎❌]](https://hydra.nixos.org/build/260710132) [[🐧✅]](https://hydra.nixos.org/build/260705063) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.shared-memory) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260704606) [[📱❌]](https://hydra.nixos.org/build/260728163) [[🍎✅]](https://hydra.nixos.org/build/260715056) [[🐧✅]](https://hydra.nixos.org/build/260709411) [haskellPackages.simdutf](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.simdutf) 
- [ ] [[📱❌]](https://hydra.nixos.org/build/260714901) [[🐧✅]](https://hydra.nixos.org/build/260711534) [haskellPackages.tasty-papi](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.tasty-papi) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260709939) [[📱✅]](https://hydra.nixos.org/build/260706089) [[🍎✅]](https://hydra.nixos.org/build/260715200) [[🐧✅]](https://hydra.nixos.org/build/260727802) [haskellPackages.unix-simple](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.unix-simple) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260710325) [[📱✅]](https://hydra.nixos.org/build/260706895) [[🍎❌]](https://hydra.nixos.org/build/260706485) [[🐧✅]](https://hydra.nixos.org/build/260725292) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.xmonad-utils) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260702228) [[📱✅]](https://hydra.nixos.org/build/260715988) [[🍎❌]](https://hydra.nixos.org/build/260710850) [[🐧✅]](https://hydra.nixos.org/build/260718778) [haskellPackages.zot](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.zot) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/260719943) [[📱✅]](https://hydra.nixos.org/build/260711991) [[🍎❌]](https://hydra.nixos.org/build/260724444) [[🐧✅]](https://hydra.nixos.org/build/260725460) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>46 job(s) </summary>

- [ ] [microlens](https://hydra.nixos.org/eval/1806462?filter=microlens)  ⤴️ 145 | 588
  - [[🍏✅]](https://hydra.nixos.org/build/260710332) [[📱✅]](https://hydra.nixos.org/build/260726561) [[🍎✅]](https://hydra.nixos.org/build/260704519) [[🐧✅]](https://hydra.nixos.org/build/260709370) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.microlens)
  - [[🍏⏳]](https://hydra.nixos.org/build/260724287)  [[🍎⏳]](https://hydra.nixos.org/build/260705620) [[🐧⏳]](https://hydra.nixos.org/build/260727418) [pkgsCross.ghcjs.haskell.packages.ghc98](https://hydra.nixos.org/eval/1806462?filter=pkgsCross.ghcjs.haskell.packages.ghc98.microlens)
  - [[🍏❗]](https://hydra.nixos.org/build/260723481)  [[🍎⏳]](https://hydra.nixos.org/build/260702879) [[🐧⏳]](https://hydra.nixos.org/build/260712287) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1806462?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.microlens)
  - [[🍏⏳]](https://hydra.nixos.org/build/260724347)  [[🍎⏳]](https://hydra.nixos.org/build/260712352) [[🐧⏳]](https://hydra.nixos.org/build/260723135) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1806462?filter=pkgsCross.ghcjs.haskellPackages.microlens)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260722344) [[📱✅]](https://hydra.nixos.org/build/260726688) [[🍎❗]](https://hydra.nixos.org/build/260715484) [[🐧✅]](https://hydra.nixos.org/build/260716422) [haskellPackages.di-handle](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.di-handle)  ⤴️ 4 | 11
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260727645) [[📱✅]](https://hydra.nixos.org/build/260707829) [[🍎❗]](https://hydra.nixos.org/build/260713090) [[🐧⏳]](https://hydra.nixos.org/build/260719309) [haskellPackages.di-monad](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.di-monad)  ⤴️ 4 | 11
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260721895) [[📱✅]](https://hydra.nixos.org/build/260728398) [[🍎❗]](https://hydra.nixos.org/build/260709845) [[🐧⏳]](https://hydra.nixos.org/build/260723739) [haskellPackages.di-df1](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.di-df1)  ⤴️ 3 | 10
- [ ] [hoogle](https://hydra.nixos.org/eval/1806462?filter=hoogle)  ⤴️ 1 | 5
  - [[🍏⏳]](https://hydra.nixos.org/build/260705921) [[📱✅]](https://hydra.nixos.org/build/260720682) [[🍎⏳]](https://hydra.nixos.org/build/260710542) [[🐧⏳]](https://hydra.nixos.org/build/260710818) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc8107.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260728081) [[📱⏳]](https://hydra.nixos.org/build/260720671) [[🍎⏳]](https://hydra.nixos.org/build/260719420) [[🐧⏳]](https://hydra.nixos.org/build/260714375) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc902.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260718110) [[📱⏳]](https://hydra.nixos.org/build/260722373) [[🍎⏳]](https://hydra.nixos.org/build/260722746) [[🐧⏳]](https://hydra.nixos.org/build/260714191) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc925.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260716337) [[📱⏳]](https://hydra.nixos.org/build/260720412) [[🍎⏳]](https://hydra.nixos.org/build/260719682) [[🐧⏳]](https://hydra.nixos.org/build/260711411) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc926.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260715660) [[📱⏳]](https://hydra.nixos.org/build/260703542) [[🍎⏳]](https://hydra.nixos.org/build/260703900) [[🐧⏳]](https://hydra.nixos.org/build/260721437) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc927.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260707426) [[📱⏳]](https://hydra.nixos.org/build/260724775) [[🍎⏳]](https://hydra.nixos.org/build/260714596) [[🐧⏳]](https://hydra.nixos.org/build/260709723) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc928.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260702052) [[📱⏳]](https://hydra.nixos.org/build/260718013) [[🍎⏳]](https://hydra.nixos.org/build/260725245) [[🐧⏳]](https://hydra.nixos.org/build/260725326) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc945.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260713378) [[📱⏳]](https://hydra.nixos.org/build/260726563) [[🍎⏳]](https://hydra.nixos.org/build/260721002) [[🐧⏳]](https://hydra.nixos.org/build/260724552) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc946.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260727591) [[📱⏳]](https://hydra.nixos.org/build/260715207) [[🍎⏳]](https://hydra.nixos.org/build/260715789) [[🐧⏳]](https://hydra.nixos.org/build/260720291) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc947.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260712198) [[📱⏳]](https://hydra.nixos.org/build/260722558) [[🍎⏳]](https://hydra.nixos.org/build/260720661) [[🐧⏳]](https://hydra.nixos.org/build/260713492) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc948.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260728909) [[📱❗]](https://hydra.nixos.org/build/260710180) [[🍎⏳]](https://hydra.nixos.org/build/260715328) [[🐧⏳]](https://hydra.nixos.org/build/260720121) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc963.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260721948) [[📱✅]](https://hydra.nixos.org/build/260720902) [[🍎⏳]](https://hydra.nixos.org/build/260715216) [[🐧⏳]](https://hydra.nixos.org/build/260724983) [haskell.packages.ghc964](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc964.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260725733) [[📱✅]](https://hydra.nixos.org/build/260722679) [[🍎⏳]](https://hydra.nixos.org/build/260719009) [[🐧⌛🚫]](https://hydra.nixos.org/build/260718210) [haskell.packages.ghc965](https://hydra.nixos.org/eval/1806462?filter=haskell.packages.ghc965.hoogle)
  - [[🍏⏳]](https://hydra.nixos.org/build/260712194) [[📱✅]](https://hydra.nixos.org/build/260705830) [[🍎⏳]](https://hydra.nixos.org/build/260725186) [[🐧⌛🚫]](https://hydra.nixos.org/build/260717236) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hoogle)
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260720694) [[📱✅]](https://hydra.nixos.org/build/260713539) [[🍎❗]](https://hydra.nixos.org/build/260716822) [[🐧⌛🚫]](https://hydra.nixos.org/build/260726377) [haskellPackages.soap](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.soap)  ⤴️ 1 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260702611) [[📱✅]](https://hydra.nixos.org/build/260705480) [[🍎❗]](https://hydra.nixos.org/build/260713828) [[🐧⏳]](https://hydra.nixos.org/build/260723404) [haskellPackages.di-polysemy](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.di-polysemy)  ⤴️ 0 | 4
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260712580) [[📱✅]](https://hydra.nixos.org/build/260728062) [[🍎❗]](https://hydra.nixos.org/build/260722202) [[🐧⏳]](https://hydra.nixos.org/build/260718207) [haskellPackages.di](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.di)  ⤴️ 0 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260713410) [[📱✅]](https://hydra.nixos.org/build/260709226) [[🍎❗]](https://hydra.nixos.org/build/260703064) [[🐧✅]](https://hydra.nixos.org/build/260704625) [haskellPackages.hsexif](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hsexif)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260709352) [[📱✅]](https://hydra.nixos.org/build/260727273) [[🍎❗]](https://hydra.nixos.org/build/260722829) [[🐧⏳]](https://hydra.nixos.org/build/260710645) [haskellPackages.amqp-utils](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.amqp-utils) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260715049) [[📱✅]](https://hydra.nixos.org/build/260709310) [[🍎❗]](https://hydra.nixos.org/build/260724808) [[🐧⏳]](https://hydra.nixos.org/build/260710496) [haskellPackages.cgrep](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.cgrep) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260711826) [[📱✅]](https://hydra.nixos.org/build/260712007) [[🍎❗]](https://hydra.nixos.org/build/260711933) [[🐧⏳]](https://hydra.nixos.org/build/260706114) [haskellPackages.di-wai](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.di-wai) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260724336) [[📱✅]](https://hydra.nixos.org/build/260727515) [[🍎❗]](https://hydra.nixos.org/build/260715189) [[🐧✅]](https://hydra.nixos.org/build/260724364) [haskellPackages.foma](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.foma) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260723198) [[📱❗]](https://hydra.nixos.org/build/260712501) [[🍎⏳]](https://hydra.nixos.org/build/260703438) [[🐧⏳]](https://hydra.nixos.org/build/260702092) [haskellPackages.ghc-experimental](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.ghc-experimental) 
- [ ] [hello](https://hydra.nixos.org/eval/1806462?filter=hello) 
  - [[🍏✅]](https://hydra.nixos.org/build/260722533) [[📱✅]](https://hydra.nixos.org/build/260720932) [[🍎✅]](https://hydra.nixos.org/build/260715495) [[🐧✅]](https://hydra.nixos.org/build/260707264) [haskellPackages](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hello)
  - [[🍏⏳]](https://hydra.nixos.org/build/260711815)  [[🍎⏳]](https://hydra.nixos.org/build/260726472) [[🐧⏳]](https://hydra.nixos.org/build/260726389) [pkgsCross.ghcjs.haskell.packages.ghc98](https://hydra.nixos.org/eval/1806462?filter=pkgsCross.ghcjs.haskell.packages.ghc98.hello)
  - [[🍏❗]](https://hydra.nixos.org/build/260725989)  [[🍎⏳]](https://hydra.nixos.org/build/260704041) [[🐧⏳]](https://hydra.nixos.org/build/260705286) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1806462?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.hello)
  - [[🍏⏳]](https://hydra.nixos.org/build/260709372)  [[🍎⏳]](https://hydra.nixos.org/build/260705946) [[🐧⏳]](https://hydra.nixos.org/build/260724045) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1806462?filter=pkgsCross.ghcjs.haskellPackages.hello)
  -    [[🐧⏳]](https://hydra.nixos.org/build/260702798) [pkgsMusl.haskellPackages](https://hydra.nixos.org/eval/1806462?filter=pkgsMusl.haskellPackages.hello)
  -    [[🐧⏳]](https://hydra.nixos.org/build/260723697) [pkgsStatic.haskell.packages.native-bignum.ghc948](https://hydra.nixos.org/eval/1806462?filter=pkgsStatic.haskell.packages.native-bignum.ghc948.hello)
  -    [[🐧⏳]](https://hydra.nixos.org/build/260717716) [pkgsStatic.haskell.packages.native-bignum.ghc982](https://hydra.nixos.org/eval/1806462?filter=pkgsStatic.haskell.packages.native-bignum.ghc982.hello)
  -    [[🐧⏳]](https://hydra.nixos.org/build/260728727) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1806462?filter=pkgsStatic.haskellPackages.hello)
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260728250) [[📱❗]](https://hydra.nixos.org/build/260704417) [[🍎⏳]](https://hydra.nixos.org/build/260704666) [[🐧⏳]](https://hydra.nixos.org/build/260724092) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260716660) [[📱✅]](https://hydra.nixos.org/build/260710032) [[🍎❗]](https://hydra.nixos.org/build/260725638) [[🐧✅]](https://hydra.nixos.org/build/260720337) [haskellPackages.intel-powermon](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.intel-powermon) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/260710785) [[📱✅]](https://hydra.nixos.org/build/260703653) [[🍎❗]](https://hydra.nixos.org/build/260717168) [[🐧✅]](https://hydra.nixos.org/build/260717347) [haskellPackages.mime-string](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.mime-string) 
- [ ] [[🍏⏳]](https://hydra.nixos.org/build/260726449) [[📱✅]](https://hydra.nixos.org/build/260710125) [[🍎❗]](https://hydra.nixos.org/build/260720736) [[🐧⌛🚫]](https://hydra.nixos.org/build/260710248) [haskellPackages.soap-openssl](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.soap-openssl) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/260713745) [[📱✅]](https://hydra.nixos.org/build/260703928) [[🍎❗]](https://hydra.nixos.org/build/260725015) [[🐧✅]](https://hydra.nixos.org/build/260706018) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1806462?filter=haskellPackages.xbattbar) 
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
[regexpr](https://packdeps.haskellers.com/reverse/regexpr) ⤴️ 26  
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
