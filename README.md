# Me

## Personal
- Currently doing courses listed by [CIC](https://cincinnatus.edu.do). After I complete the technical-capacitation phase, I'll get my 1st job!
- Have an "obsession" with code refactoring. It's obvious from my GH activity 😂
- Considering leaving GH, [for many reasons](https://gavinhoward.com/2020/04/i-am-moving-away-from-github).
	- The fact that [GL nukes dead accounts](https://about.gitlab.com/privacy/#how-does-gitLab-secure-my-personal-data) is a deal-breaker for me.
	- I've just learned about [Code-Berg](https://codeberg.org), it seems interesting.

## Repos
- When my PRs are merged, **I'll delete my corresponding fork**. Therefore, links to any of my forks may be [broken](https://en.wikipedia.org/wiki/Link_rot) (not dead, because it's not permanent) in the future.
	- The exception is [.files](https://github.com/Rudxain/dotfiles)
- I could **delete any of [my Gists](https://gist.github.com/Rudxain) without warning**
- All my repos use [semver](https://semver.org)
	- except the ones that don't use versioning at all
- If I contribute to any of your repos, I hope you do the same for me and/or other people :)

## Langs
[![](https://github-readme-stats.vercel.app/api/top-langs/?username=rudxain&layout=compact&langs_count=8&size_weight=0.5&count_weight=0.5&hide=kotlin#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)
[![](https://github-readme-stats.vercel.app/api/top-langs/?username=rudxain&layout=compact&langs_count=8&size_weight=0.5&count_weight=0.5&hide=kotlin&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)

- ❤Favorites
	- in practice:
	This takes into account all the stuff related to the langs (portability, documentation, std+community tools & libraries, ecosystem, etc...):
	
		0. <img src=https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg width=16em height=16em>Python
		1. JavaScript
		2. 🦀Rust
			- I love its _honesty_: It has abstractions (like any other lang), but they are **[leaky](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions) by design**.
			> [Rust \[is\] both as low-level as C, and as high-level as Lisp, whereas most other popular languages are stuck somewhere in the middle.](https://github.com/0atman/noboilerplate/blob/1eab51863994129b0c31f1d6925c5bd6299f4dc9/scripts/03-rust-turtles-all-the-way-down.md) 
		4. POSIX Shell

	- in theory:
	This **only** takes into account the langs [in isolation](https://en.wikipedia.org/wiki/Spherical_cow) (type-system, syntax & grammar, stdlib, etc...):
	
		0. 🦀Rust. [For everything](https://github.com/ansuz/RIIR/issues/39#issuecomment-2039122371).
		1. <img src=https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg width=16em height=16em>Python. For expressing algorithms, because "haha, pseudo-code".
			- My favorite argument against [Python's colons](https://docs.python.org/3/faq/design.html#why-are-colons-required-for-the-if-while-def-class-statements) is this:
			> > _The colons are an extra visual clue to scanning the blocks. As such, they improve readability, one of Python's main strengths._
			> 
			> [Then Opening and closing braces should be called an "extra visual clue to scanning the block" in C++ and Java? Because they improved readability. Braces (`{`) then is C++, Java's main Strength.](https://wiki.c2.com/?SyntacticallySignificantWhitespaceConsideredHarmful)
			
			As a logician, I love the way they point out the fallacy!
		3. 🕊Ada
			- I fell in love with it, since it makes a [distinction between subroutines and functions](https://learn.adacore.com/courses/intro-to-ada/chapters/subprograms.html), and [supports ranged-ints](https://learn.adacore.com/courses/intro-to-ada/chapters/strongly_typed_language.html#integers) out-of-the-box. It even statically checks ranges at the type-system level! something that [Pkl](https://pkl-lang.org/main/current/language-reference/index.html#integers) does, but Rust and TS don't do it at all:
			```ada
			-- 32bit target architecture
			type Integer is range -(2 ** 31) .. +(2 ** 31 - 1);
			-- I love this so much that I hate Py and Rust in comparison 😭
			```
		4. Any lang that uses symbols rather than words (such as BrainFuck dialects), specially if the symbols have shapes that intuitively correspond to their operation.

- 🧠Expertise: This takes into account my 📕knowledge of the lang (and everything ⚙️related), and the experience making 👍useful, ⚡efficient, and ✅correct/safe software in it.
This is subject to [D.K.](https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect), I'll try my best to list in an accurate order. Assume all confidence scores are approximations (prefix "~"):

	0. Java Regular Expressions 📕15/16👍8/9⚡0xfff/0x1000✅99%, I'm expert at optimizing them; CSV \(any "dialect") 📕1/1⚙️0xff/0x100👍3/4⚡99%✅98%; JSON 📕1/1👍99%⚡0xfff/0x1000✅98%.
	1. 🦙Llamalab <img src=https://llamalab.com/img/automate/ic_launcher-128.png width=16em height=16em>Automate 📕85%👍80%⚡95%✅80%
	2. [Scratch](https://scratch.mit.edu) 📕80%👍90%✅90%
	3. JavaScript 📕98%👍0xfff/0x1000⚡95%✅\[95% 80%]\(with JSDoc+`@TScheck` and bare JS, respectively)
	4. TypeScript 📕90%👍0xfff/0x1000⚡94%✅96%
	5. <img src=https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg width=16em height=16em>Python 📕85%👍90%✅90%
	6. POSIX shell 📕90%👍3/4⚡80%✅3/4
	7. MirBSD Korn Shell 📕80%👍3/4✅80%
	8. <img src=https://raw.githubusercontent.com/odb/official-bash-logo/master/assets/Logos/Icons/SVG/16x16.svg width=16em height=16em>Bash 📕72%👍3/4✅80%
	9. HTML 📕70%👍85%⚡70%✅3/4
	10. SVG 📕70%👍80%⚡3/4✅70%
	11. CSS 📕71%⚡3/4✅2/3
	12. 🦀Rust 📕2/3👍90%⚡90%✅0xfff/0x1000
	13. <img src=https://gleam.run/images/lucy/lucy.svg width=16em height=16em>Gleam 📕80%👍70%✅80%
	14. [Go](https://github.com/golang/go) 📕2/3👍2/3⚡50%✅3/4
	15. C 📕7/10👍1/3⚡7/10✅1/0x40
	16. BrainFuck 📕1/1⚙️4/5👍1/16⚡\[1/1 1/2]✅\[1/0x80 7/8]

- 👀Interested

	0. 💾Assembly
		- 6502
		- RISC-V
	0. [V](https://github.com/vlang/v)
	1. APL
	2. <img src=https://upload.wikimedia.org/wikipedia/commons/4/48/Lisp_logo.svg width=16em height=16em>(Common Lisp)

## Editors
<img src=https://raw.githubusercontent.com/helix-editor/helix/master/logo.svg width=16em height=16em>[Helix](https://github.com/helix-editor/helix) ❤

I also have experience with VScode and GNU Nano

## OS
- ❤Favorites

	0. <img src=https://www.debian.org/logos/openlogo-nd.svg width=16em height=16em>Debian
	1. <img src=https://upload.wikimedia.org/wikipedia/commons/e/e0/Android_robot_%282014-2019%29.svg width=16em height=16em>Android
	2. <img src=https://upload.wikimedia.org/wikipedia/commons/2/25/Microsoft_icon.svg width=16em height=16em>Microsoft <img src=https://upload.wikimedia.org/wikipedia/commons/4/48/Windows_logo_-_2012_%28dark_blue%29.svg width=16em height=16em>Windows

- 🧠Expertise

	0. <img src=https://upload.wikimedia.org/wikipedia/commons/e/e0/Android_robot_%282014-2019%29.svg width=16em height=16em>Android 4 to 8.1, and 12 (0 experience with A\[9, 11])
		- Most of my experience was from using
			- TouchWiz
			- Samsung Experience
			- OneUI
		- I do have some experience with AOSP (0 Gapps)
	2. <img src=https://www.debian.org/logos/openlogo-nd.svg width=16em height=16em>Debian-based <img src=https://upload.wikimedia.org/wikipedia/commons/3/3c/TuxFlat.svg width=16em height=16em>Linux distros 
	3. ChromeOS
		- I only have basic knowledge about its internals
	5. <img src=https://upload.wikimedia.org/wikipedia/commons/2/25/Microsoft_icon.svg width=16em height=16em>Microsoft <img src=https://upload.wikimedia.org/wikipedia/commons/4/48/Windows_logo_-_2012_%28dark_blue%29.svg width=16em height=16em>Windows XP, \[7, 11] (I haven't touched Vista 💀)
		- Despite using it my entire life, this beast is so bloated/complex that I know less than ~20% about it

- 👀Interested

	0. [Redox](https://www.redox-os.org)
	1. <img src=https://raw.githubusercontent.com/NixOS/nixos-artwork/f84c13adae08e860a7c3f76ab3a9bef916d276cc/logo/nix-snowflake-colours.svg width=16em height=16em>Nix
	2. [G Fuchsia](https://fuchsia.dev)

## Browsers
- Favorites
	- in practice
		- Main: <img src=https://raw.githubusercontent.com/mdn/yari/2720d1f9998be94428a822dcc06946d6a53879d0/client/src/assets/dino.svg width=16em height=16em>Mozilla <img src=https://upload.wikimedia.org/wikipedia/commons/a/a0/Firefox_logo%2C_2019.svg width=16em height=16em>Firefox
		- Windows: <img src=https://upload.wikimedia.org/wikipedia/commons/2/25/Microsoft_icon.svg width=16em height=16em>Microsoft <img src=https://upload.wikimedia.org/wikipedia/commons/9/98/Microsoft_Edge_logo_%282019%29.svg width=16em height=16em>Edge
	- in theory
		- [LibreWolf](https://librewolf.net)

I also have expertise with Chromium-based browsers.

## Terminals

- <img src=https://upload.wikimedia.org/wikipedia/commons/3/3c/TuxFlat.svg width=16em height=16em>Linux: GNOME Terminal (not Console)
- <img src=https://upload.wikimedia.org/wikipedia/commons/e/e0/Android_robot_%282014-2019%29.svg width=16em height=16em>Android: Termux
